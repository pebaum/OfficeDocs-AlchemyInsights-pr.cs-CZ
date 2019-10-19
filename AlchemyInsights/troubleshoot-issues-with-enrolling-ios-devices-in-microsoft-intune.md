---
title: Poradce při potížích s připojením zařízení iOS v systému Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: bdbfe7bae00a4c5cfa0edbe9a37522cc98e52401
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36506914"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="18f2b-102">Poradce při potížích s připojením zařízení iOS v systému Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="18f2b-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="18f2b-103">Chcete-li problém vyřešit nyní, Prohlédněte si níže uvedené zdroje.</span><span class="sxs-lookup"><span data-stu-id="18f2b-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="18f2b-104">Některé běžné chybové zprávy a kroky řešení:</span><span class="sxs-lookup"><span data-stu-id="18f2b-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="18f2b-105">**Zakončení zařízení bylo dosaženo** Uživatel má k zaregistrováni více zařízení, než je limit zařízení.</span><span class="sxs-lookup"><span data-stu-id="18f2b-105">**Device Cap Reached** The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="18f2b-106">Prohlédněte si tyto dokumenty a [odeberte zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změňte omezení zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="18f2b-106">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="18f2b-107">**Tato služba není podporována. Žádné zásady zápisu:** služba oznámení Apple Push (APNS) musí být nakonfigurována nebo obnovena.</span><span class="sxs-lookup"><span data-stu-id="18f2b-107">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed.</span></span> <span data-ttu-id="18f2b-108">V [tomto dokumentu](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) naleznete pokyny k tomuto postupu.</span><span class="sxs-lookup"><span data-stu-id="18f2b-108">Review [this document](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="18f2b-109">**Neplatný typ licence uživatele nebo nebylo rozpoznáno uživatelské jméno:** Uživateli musí být přidělena licence Intune nebo EMS.</span><span class="sxs-lookup"><span data-stu-id="18f2b-109">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="18f2b-110">Zkontrolujte tyto dokumenty a přiřaďte licenci prostřednictvím: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) nebo [portál Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="18f2b-110">Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="18f2b-111">Další zdroje informací, které vám pomohou vyřešit váš problém:</span><span class="sxs-lookup"><span data-stu-id="18f2b-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="18f2b-112">Pomocí [portálu pro řešení potíží Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a vyřešit běžné chyby zápisu.</span><span class="sxs-lookup"><span data-stu-id="18f2b-112">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="18f2b-113">Další podrobnosti naleznete v [tomto dokumentu](https://docs.microsoft.com/intune/help-desk-operators) .</span><span class="sxs-lookup"><span data-stu-id="18f2b-113">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="18f2b-114">V těchto dokumentech si můžete prohlédnout seznam běžných chyb, které zabraňují zápisu a řešení pro každý z nich: [Průvodce odstraňováním potíží](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [dokument o odstraňování potíží](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="18f2b-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="18f2b-115">[Naučte se zapisovat zařízení iOS do společnosti Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="18f2b-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span></span>
    

