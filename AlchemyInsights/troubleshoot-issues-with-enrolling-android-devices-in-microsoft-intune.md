---
title: Řešení problémů s registrací zařízení s Androidem v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: bd6d278ebf6cca7fb6e4ac1049deae600b516707
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759613"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="0e415-102">Řešení problémů s registrací zařízení s Androidem v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="0e415-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="0e415-103">Chcete-li problém vyřešit, zkontrolujte níže uvedené zdroje.</span><span class="sxs-lookup"><span data-stu-id="0e415-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="0e415-104">Některé běžné problémy a kroky řešení:</span><span class="sxs-lookup"><span data-stu-id="0e415-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="0e415-105">**Chyba Zařízení není šifrovaná na portálu společnosti:** Novější verze systému Android, zejména počínaje verzí v7.0, vyžadují přístupový kód pro spuštění, aby bylo zajištěno, že je vaše zařízení plně šifrované.</span><span class="sxs-lookup"><span data-stu-id="0e415-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="0e415-106">Běžnými řešeními je povolit spouštěcí pin nebo plně šifrovat zařízení.</span><span class="sxs-lookup"><span data-stu-id="0e415-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="0e415-107">Další informace naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android)</span><span class="sxs-lookup"><span data-stu-id="0e415-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span>
  
 <span data-ttu-id="0e415-108">**Zařízení se nedaří vrátit se změnami pomocí služby Intune nebo se v konzole pro správu Intune zobrazit jako "Není v pořádku":** Některá zařízení Samsung 4.4 a 5.5 se nemusí do služby přihlásit.</span><span class="sxs-lookup"><span data-stu-id="0e415-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="0e415-109">Existují 3 možná řešení tohoto problému:</span><span class="sxs-lookup"><span data-stu-id="0e415-109">There are 3 possible solutions to this issue:</span></span>
  
1. <span data-ttu-id="0e415-110">Ručně otevřete aplikaci Portál společnosti Intune, která automaticky zahájí synchronizaci zařízení.</span><span class="sxs-lookup"><span data-stu-id="0e415-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>

2. <span data-ttu-id="0e415-111">Aktualizujte zařízení na Android 6.0 nebo vyšší.</span><span class="sxs-lookup"><span data-stu-id="0e415-111">Update the device to Android 6.0 or higher.</span></span>

3. <span data-ttu-id="0e415-112">Zakažte samsung smart manageru ve správě portálu společnosti Intune.</span><span class="sxs-lookup"><span data-stu-id="0e415-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="0e415-113">Další podrobnosti o těchto problémech a řešeních naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console)</span><span class="sxs-lookup"><span data-stu-id="0e415-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span>

 <span data-ttu-id="0e415-114">**Neplatná chyba typu uživatelské licence** nebo **Nerozpoznané uživatelské jméno:** Uživateli musí být přiřazena licence Intune nebo EMS.</span><span class="sxs-lookup"><span data-stu-id="0e415-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="0e415-115">Zkontrolujte tyto dokumenty a přiřaďte licenci prostřednictvím: Office Admin Center nebo Portál Azure.</span><span class="sxs-lookup"><span data-stu-id="0e415-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span>
  
<span data-ttu-id="0e415-116">Další zdroje informací, které vám pomohou problém vyřešit:</span><span class="sxs-lookup"><span data-stu-id="0e415-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="0e415-117">Pomocí [portálu pro řešení potíží intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a řešit běžné chyby registrace.</span><span class="sxs-lookup"><span data-stu-id="0e415-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="0e415-118">Další podrobnosti naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune/help-desk-operators)</span><span class="sxs-lookup"><span data-stu-id="0e415-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="0e415-119">Zkontrolujte, co se v [tomto dokumentu](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) neuvádí, a seznam běžných chyb, které brání zápisu a řešení jednotlivých chyb.</span><span class="sxs-lookup"><span data-stu-id="0e415-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span>

3. <span data-ttu-id="0e415-120">[Přečtěte si, jak zaregistrovat zařízení s Androidem v Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="0e415-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
