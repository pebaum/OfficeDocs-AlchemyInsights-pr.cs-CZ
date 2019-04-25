---
title: Řešení problémů s zápis zařízení iOS v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: d28dca4fccf823e627dd179f828ba3b8baf843a6
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32391000"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="01778-102">Řešení problémů s zápis zařízení iOS v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="01778-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="01778-103">Zobrazit zdroje uvedené níže nyní vyřešit váš problém.</span><span class="sxs-lookup"><span data-stu-id="01778-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="01778-104">Některé běžné chybové zprávy a postup řešení:</span><span class="sxs-lookup"><span data-stu-id="01778-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="01778-105">**Zařízení Cap dosaženo** Uživatel má více zařízení, než je limit zařízení zapsán.</span><span class="sxs-lookup"><span data-stu-id="01778-105">**Device Cap Reached** The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="01778-106">Zkontrolujte tyto dokumenty k [odebrání zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="01778-106">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="01778-107">**Této služby není podporován. Žádné zásady zápisu:** názvy Apple Push oznámení služby (APN) je nutné nakonfigurovat nebo obnoven.</span><span class="sxs-lookup"><span data-stu-id="01778-107">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed.</span></span> <span data-ttu-id="01778-108">Přečtěte [dokument](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) pro pokyny, jak na to.</span><span class="sxs-lookup"><span data-stu-id="01778-108">Review [this document](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="01778-109">**Neplatný typ licence uživatele nebo uživatelské jméno není rozpoznán:** Uživatel musí být přiřazen licenci pro Intune a EMS.</span><span class="sxs-lookup"><span data-stu-id="01778-109">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="01778-110">Zkontrolujte přiřazení licence prostřednictvím tyto dokumenty: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) nebo [portálu Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="01778-110">Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="01778-111">Další zdroje pomoci vyřešit váš problém:</span><span class="sxs-lookup"><span data-stu-id="01778-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="01778-112">Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu.</span><span class="sxs-lookup"><span data-stu-id="01778-112">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="01778-113">Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti.</span><span class="sxs-lookup"><span data-stu-id="01778-113">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="01778-114">Zkontrolujte tyto dokumenty seznam běžné chyby, které brání každému zápisu a usnesení: [Poradce při potížích Průvodce](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [Poradce při potížích s doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="01778-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="01778-115">[Zjistěte, jak zapsat zařízení iOS v Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="01778-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span></span>
    

