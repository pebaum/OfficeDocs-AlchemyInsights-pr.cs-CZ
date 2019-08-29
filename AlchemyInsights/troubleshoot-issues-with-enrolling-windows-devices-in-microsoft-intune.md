---
title: Řešení problémů s zápis Windows zařízení v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: 7b298360fe31d3f52ef382e5b8f25ee3588c36c8
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36665825"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Řešení problémů s zápis Windows zařízení v Microsoft Intune

Zobrazit zdroje uvedené níže nyní vyřešit váš problém.
  
Některé běžné chybové zprávy a postup řešení:
  
 **Nelze nainstalovat software, 0x80cf4017:** Váš certifikát účtu vypršela. Znovu stáhněte balíček klientského počítače v konzole pro správu Intune. Další informace v této dokumentaci.
  
 **Kód chyby 0x801c0003:** Došlo k chybě může dojít v následujících situacích:
  
-  Uživatel má více zařízení, než je limit zařízení zapsán. Zkontrolujte tyto dokumenty k [odebrání zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).

-  "Uživatelé mohou připojit zařízení k Azure AD" je nastavena na "none." Nastaven na hodnotu vše nebo vyberte uživatele. Zkontrolujte [tuto dokumentaci](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) Další informace.

-  Zařízení je již zapsán jiným uživatelem. Pokud tomu tak je, odebrání zařízení z konzoly Azure Intune nebo ručně unenroll zařízení před dalším pokusem.

-  Zařízení se systém Windows 10 Home. Azure Active Directory se může účastnit pouze Pro systém Windows 10, vzdělávání a Enterprise SKU.

Další zdroje pomoci vyřešit váš problém:
  
-  Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu. Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti.

-  Zkontrolujte tyto dokumenty seznam běžné chyby, které brání každému zápisu a usnesení: [Poradce při potížích Průvodce](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) a [Poradce při potížích s doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).

[Zjistěte, jak zapsat Windows zařízení v Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).
