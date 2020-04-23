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
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Řešení problémů s registrací iOS zařízení v Microsoft Intune

Chcete-li problém vyřešit, zkontrolujte níže uvedené zdroje. 
  
Některé běžné chybové zprávy a kroky řešení:
  
- **Bylo dosaženo krytu zařízení** Uživatel má více zařízení zaregistrovaných, než je limit zařízení. Zkontrolujte tyto [dokumenty, chcete-li odebrat zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- **Tato služba není podporována. Žádné zásady registrace:** Službu nabízených oznámení Apple (APNS) je třeba nakonfigurovat nebo obnovit. V [tomto dokumentu](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) naleznete pokyny, jak to provést. 
    
- **Typ uživatelské licence neplatný nebo uživatelské jméno nebylo rozpoznáno:** Uživateli musí být přiřazena licence Intune nebo EMS. Zkontrolujte tyto dokumenty a přiřaďte licenci prostřednictvím: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) nebo Portál [Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).
    
Další zdroje informací, které vám pomohou problém vyřešit:
  
1. Pomocí [portálu pro řešení potíží intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a řešit běžné chyby registrace. Další podrobnosti naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune/help-desk-operators) 
    
2. V těchto dokumentech naleznete seznam běžných chyb, které brání zápisu a řešení jednotlivých chyb: [Průvodce odstraňováním potíží](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [dokument pro řešení potíží](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
3. [Přečtěte si, jak zaregistrovat iOS zařízení v Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).
    

