---
title: Řešení problémů s zápis Windows zařízení v Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: aa2262ed487ae4160f13490e92163a145e657862
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32390636"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a>Řešení problémů s zápis Windows zařízení v Microsoft Intune

Zobrazit zdroje uvedené níže nyní vyřešit váš problém. 
  
Některé běžné chybové zprávy a postup řešení:
  
 **Nelze nainstalovat software, 0x80cf4017:** Váš certifikát účtu vypršela. Znovu stáhněte balíček klientského počítače v konzole pro správu Intune. Další informace v této dokumentaci. 
  
 **Kód chyby 0x801c0003:** Došlo k chybě může dojít v následujících situacích: 
  
1. Uživatel má více zařízení, než je limit zařízení zapsán. Zkontrolujte tyto dokumenty k [odebrání zařízení](https://docs.microsoft.com/intune/devices-wipe) nebo [změnit limit zařízení](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
2. "Uživatelé mohou připojit zařízení k Azure AD" je nastavena na "none". Nastaven na hodnotu vše nebo vyberte uživatele. Zkontrolujte [tuto dokumentaci](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) Další informace. 
    
3. Zařízení je již zapsán jiným uživatelem. Pokud tomu tak je, odebrání zařízení z konzoly Azure Intune nebo ručně unenroll zařízení před dalším pokusem.
    
4. Zařízení se systém Windows 10 Home. Azure Active Directory se může účastnit pouze Pro systém Windows 10, vzdělávání a Enterprise SKU.
    
Další zdroje pomoci vyřešit váš problém:
  
1. Pomocí [Poradce při potížích s portál Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostikovat a vyřešit běžné chyby zápisu. Přečtěte [dokument](https://docs.microsoft.com/intune/help-desk-operators) pro další podrobnosti. 
    
2. Zkontrolujte tyto dokumenty seznam běžné chyby, které brání každému zápisu a usnesení: [Poradce při potížích Průvodce](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) a [Poradce při potížích s doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
[Zjistěte, jak zapsat Windows zařízení v Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).
  

