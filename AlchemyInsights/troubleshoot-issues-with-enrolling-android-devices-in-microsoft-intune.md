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
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Řešení problémů s registrací zařízení s Androidem v Microsoft Intune

Chcete-li problém vyřešit, zkontrolujte níže uvedené zdroje.
  
Některé běžné problémy a kroky řešení:
  
 **Chyba Zařízení není šifrovaná na portálu společnosti:** Novější verze systému Android, zejména počínaje verzí v7.0, vyžadují přístupový kód pro spuštění, aby bylo zajištěno, že je vaše zařízení plně šifrované. Běžnými řešeními je povolit spouštěcí pin nebo plně šifrovat zařízení. Další informace naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android)
  
 **Zařízení se nedaří vrátit se změnami pomocí služby Intune nebo se v konzole pro správu Intune zobrazit jako "Není v pořádku":** Některá zařízení Samsung 4.4 a 5.5 se nemusí do služby přihlásit. Existují 3 možná řešení tohoto problému:
  
1. Ručně otevřete aplikaci Portál společnosti Intune, která automaticky zahájí synchronizaci zařízení.

2. Aktualizujte zařízení na Android 6.0 nebo vyšší.

3. Zakažte samsung smart manageru ve správě portálu společnosti Intune. Další podrobnosti o těchto problémech a řešeních naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console)

 **Neplatná chyba typu uživatelské licence** nebo **Nerozpoznané uživatelské jméno:** Uživateli musí být přiřazena licence Intune nebo EMS. Zkontrolujte tyto dokumenty a přiřaďte licenci prostřednictvím: Office Admin Center nebo Portál Azure.
  
Další zdroje informací, které vám pomohou problém vyřešit:
  
1. Pomocí [portálu pro řešení potíží intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) můžete diagnostikovat a řešit běžné chyby registrace. Další podrobnosti naleznete v [tomto dokumentu.](https://docs.microsoft.com/intune/help-desk-operators)

2. Zkontrolujte, co se v [tomto dokumentu](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) neuvádí, a seznam běžných chyb, které brání zápisu a řešení jednotlivých chyb.

3. [Přečtěte si, jak zaregistrovat zařízení s Androidem v Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).
