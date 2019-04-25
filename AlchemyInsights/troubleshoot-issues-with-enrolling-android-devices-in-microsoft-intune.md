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
ms.openlocfilehash: 0e727bd47a7d549a439e4666fa9dbb8a02e39778
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420585"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Řešení problémů s zápis Android zařízení v Microsoft Intune

Zobrazit zdroje uvedené níže nyní vyřešit váš problém.
  
Některé běžné problémy a jejich řešení takto:
  
 **Zařízení nejsou šifrovaná Chyba v portálu společnosti:** Novější verze systému Android, zejména od verze 7.0, vyžadují spouštěcí kód a ujistěte se, že zařízení jsou zašifrovány. Povolení spuštění kódu pin nebo plně šifrování zařízení jsou společné řešení. Přečtěte [dokument](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) pro další informace. 
  
 **Zařízení se nepodařilo kontaktovat službu Intune nebo jako "Unhealthy" v konzole pro správu Intune:** 4.4 některé Samsung a 5.5 zařízení nemusí vrátit do služby. Existují 3 možná řešení tohoto problému: 
  
1. Ruční otevření bude aplikace portál společnosti Intune automaticky zahájí synchronizaci zařízení.
    
2. Aktualizace zařízení Android 6.0 nebo vyšší.
    
3. Samsung Smart Manager zakážete od správy portálu společnosti Intune. Přečtěte [dokument](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) pro další podrobnosti o těchto problémech a jejich řešení. 
    
 **Uživatelské licence typu neplatná** nebo **uživatelské jméno není rozpoznána chyba:** , uživatel musí být přiřazen licenci pro Intune a EMS. Zkontrolujte přiřazení licence prostřednictvím tyto dokumenty: portál Office Admin Center nebo Azure. 
  
Další zdroje pomoci vyřešit váš problém:
  
1. Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu. Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti. 
    
2. Přečtěte [dokument](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) seznam běžné chyby, které brání každému zápisu a usnesení. 
    
3. [Zjistěte, jak zapsat Android zařízení v Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).
    

