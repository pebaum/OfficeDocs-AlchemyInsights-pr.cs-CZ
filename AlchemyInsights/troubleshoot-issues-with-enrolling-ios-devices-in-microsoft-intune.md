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
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Poradce při potížích s připojením zařízení iOS v systému Microsoft Intune

Chcete-li problém vyřešit nyní, Prohlédněte si níže uvedené zdroje. 
  
Některé běžné chybové zprávy a kroky řešení:
  
- **Zakončení zařízení bylo dosaženo** Uživatel má k zaregistrováni více zařízení, než je limit zařízení. Prohlédněte si tyto dokumenty a [odeberte zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změňte omezení zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- **Tato služba není podporována. Žádné zásady zápisu:** služba oznámení Apple Push (APNS) musí být nakonfigurována nebo obnovena. V [tomto dokumentu](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) naleznete pokyny k tomuto postupu. 
    
- **Neplatný typ licence uživatele nebo nebylo rozpoznáno uživatelské jméno:** Uživateli musí být přidělena licence Intune nebo EMS. Zkontrolujte tyto dokumenty a přiřaďte licenci prostřednictvím: [Office Admin Center](https://docs.microsoft.com/intune/licenses-assign) nebo [portál Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).
    
Další zdroje informací, které vám pomohou vyřešit váš problém:
  
1. Pomocí [portálu pro řešení potíží Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a vyřešit běžné chyby zápisu. Další podrobnosti naleznete v [tomto dokumentu](https://docs.microsoft.com/intune/help-desk-operators) . 
    
2. V těchto dokumentech si můžete prohlédnout seznam běžných chyb, které zabraňují zápisu a řešení pro každý z nich: [Průvodce odstraňováním potíží](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) a [dokument o odstraňování potíží](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
3. [Naučte se zapisovat zařízení iOS do společnosti Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).
    

