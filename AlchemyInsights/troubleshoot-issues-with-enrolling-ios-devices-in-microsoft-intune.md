---
title: Řešení problémů s registrací iOS zařízení v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 664c18daca5d8e0ad4a88f41db3ff0dbced606e5
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43736151"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="d9c8d-102">Řešení problémů s registrací iOS zařízení v Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="d9c8d-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="d9c8d-103">Chcete-li problém vyřešit, zkontrolujte níže uvedené zdroje.</span><span class="sxs-lookup"><span data-stu-id="d9c8d-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="d9c8d-104">Některé běžné chybové zprávy a kroky řešení:</span><span class="sxs-lookup"><span data-stu-id="d9c8d-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="d9c8d-105">**Bylo dosaženo krytu zařízení** Uživatel má více zařízení zaregistrovaných, než je limit zařízení.</span><span class="sxs-lookup"><span data-stu-id="d9c8d-105">**Device Cap Reached** The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="d9c8d-106">Zkontrolujte tyto [dokumenty, chcete-li odebrat zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="d9c8d-106">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="d9c8d-107">**Tato služba není podporována. Žádné zásady registrace:** Službu nabízených oznámení Apple (APNS) je třeba nakonfigurovat nebo obnovit.</span><span class="sxs-lookup"><span data-stu-id="d9c8d-107">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed.</span></span> <span data-ttu-id="d9c8d-108">V [tomto dokumentu](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) naleznete pokyny, jak to provést.</span><span class="sxs-lookup"><span data-stu-id="d9c8d-108">Review [this document](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="d9c8d-109">**Typ uživatelské licence neplatný nebo uživatelské jméno nebylo rozpoznáno:** Uživateli musí být přiřazena licence Intune nebo EMS.</span><span class="sxs-lookup"><span data-stu-id="d9c8d-109">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license.</span></span> <span data-ttu-id="d9c8d-110">Zkontrolujte tyto dokumenty a přiřaďte licenci prostřednictvím: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) nebo Portál [Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="d9c8d-110">Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="d9c8d-111">Další zdroje informací, které vám pomohou problém vyřešit:</span><span class="sxs-lookup"><span data-stu-id="d9c8d-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="d9c8d-112">Pomocí [portálu pro řešení potíží intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a řešit běžné chyby registrace.</span><span class="sxs-lookup"><span data-stu-id="d9c8d-112">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="d9c8d-113">Další podrobnosti naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune/help-desk-operators)</span><span class="sxs-lookup"><span data-stu-id="d9c8d-113">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="d9c8d-114">V těchto dokumentech naleznete seznam běžných chyb, které brání zápisu a řešení jednotlivých chyb: [Průvodce odstraňováním potíží](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [dokument pro řešení potíží](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="d9c8d-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="d9c8d-115">[Přečtěte si, jak zaregistrovat iOS zařízení v Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="d9c8d-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).</span></span>
    

