---
title: Řešení problémů s zápis Android zařízení v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: 9cdfda0d7dd45af260f46738cbc85aac46f53960
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35367282"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a><span data-ttu-id="23f55-102">Řešení problémů s zápis Android zařízení v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="23f55-102">Troubleshoot issues with enrolling Android devices in Microsoft Intune</span></span>

<span data-ttu-id="23f55-103">Zobrazit zdroje uvedené níže nyní vyřešit váš problém.</span><span class="sxs-lookup"><span data-stu-id="23f55-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="23f55-104">Některé běžné problémy a jejich řešení takto:</span><span class="sxs-lookup"><span data-stu-id="23f55-104">Some common issues and resolution steps:</span></span>
  
 <span data-ttu-id="23f55-105">**Zařízení nejsou šifrovaná Chyba v portálu společnosti:** Novější verze systému Android, zejména od verze 7.0, vyžadují spouštěcí kód a ujistěte se, že zařízení jsou zašifrovány.</span><span class="sxs-lookup"><span data-stu-id="23f55-105">**Device not Encrypted error in Company Portal:** Newer versions of Android, particularly starting with v7.0, require a startup passcode to make sure that your device is fully encrypted.</span></span> <span data-ttu-id="23f55-106">Povolení spuštění kódu pin nebo plně šifrování zařízení jsou společné řešení.</span><span class="sxs-lookup"><span data-stu-id="23f55-106">Common solutions are to enable a startup pin or fully encrypt the device.</span></span> <span data-ttu-id="23f55-107">Přečtěte [dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) pro další informace.</span><span class="sxs-lookup"><span data-stu-id="23f55-107">Review [this document](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) for more information.</span></span>
  
 <span data-ttu-id="23f55-108">**Zařízení se nepodařilo kontaktovat službu Intune nebo jako "Unhealthy" v konzole pro správu Intune:** 4.4 některé Samsung a 5.5 zařízení nemusí vrátit do služby.</span><span class="sxs-lookup"><span data-stu-id="23f55-108">**Devices fail to check in with the Intune service or display as "Unhealthy" in the Intune admin console:** Some Samsung 4.4 and 5.5 devices may not check into the service.</span></span> <span data-ttu-id="23f55-109">Existují 3 možná řešení tohoto problému:</span><span class="sxs-lookup"><span data-stu-id="23f55-109">There are 3 possible solutions to this issue:</span></span>
  
1. <span data-ttu-id="23f55-110">Ruční otevření bude aplikace portál společnosti Intune automaticky zahájí synchronizaci zařízení.</span><span class="sxs-lookup"><span data-stu-id="23f55-110">Manually open the Intune Company Portal app, which will automatically initiate a device sync.</span></span>

2. <span data-ttu-id="23f55-111">Aktualizace zařízení Android 6.0 nebo vyšší.</span><span class="sxs-lookup"><span data-stu-id="23f55-111">Update the device to Android 6.0 or higher.</span></span>

3. <span data-ttu-id="23f55-112">Samsung Smart Manager zakážete od správy portálu společnosti Intune.</span><span class="sxs-lookup"><span data-stu-id="23f55-112">Disable Samsung Smart Manager from managing the Intune Company Portal.</span></span> <span data-ttu-id="23f55-113">Přečtěte [dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) pro další podrobnosti o těchto problémech a jejich řešení.</span><span class="sxs-lookup"><span data-stu-id="23f55-113">Review [this document](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) for further details on these issues and resolutions.</span></span>

 <span data-ttu-id="23f55-114">**Uživatelské licence typu neplatná** nebo **uživatelské jméno není rozpoznána chyba:** , uživatel musí být přiřazen licenci pro Intune a EMS.</span><span class="sxs-lookup"><span data-stu-id="23f55-114">**User License Type Invalid** or **User Name Not Recognized error:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="23f55-115">Zkontrolujte přiřazení licence prostřednictvím tyto dokumenty: portál Office Admin Center nebo Azure.</span><span class="sxs-lookup"><span data-stu-id="23f55-115">Review these documents to assign a license through: Office Admin Center or Azure portal.</span></span>
  
<span data-ttu-id="23f55-116">Další zdroje pomoci vyřešit váš problém:</span><span class="sxs-lookup"><span data-stu-id="23f55-116">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="23f55-117">Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu.</span><span class="sxs-lookup"><span data-stu-id="23f55-117">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="23f55-118">Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti.</span><span class="sxs-lookup"><span data-stu-id="23f55-118">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

2. <span data-ttu-id="23f55-119">Přečtěte [dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) seznam běžné chyby, které brání každému zápisu a usnesení.</span><span class="sxs-lookup"><span data-stu-id="23f55-119">Review [this document](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) for a list of common errors that prevent enrollment and resolutions to each.</span></span>

3. <span data-ttu-id="23f55-120">[Zjistěte, jak zapsat Android zařízení v Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span><span class="sxs-lookup"><span data-stu-id="23f55-120">[Learn how to enroll Android devices in Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).</span></span>
