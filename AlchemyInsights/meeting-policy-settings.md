---
title: Nastavení zásad schůzky
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2657"
- "9000734"
ms.openlocfilehash: dac06690b51459ca166c15a5ef0f4c7e7a6d36f0
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376568"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a>Správa zásad schůzky v týmu společnosti Microsoft

Zásady schůzky slouží k řízení funkcí, které jsou k dispozici účastníkům schůzky pro schůzky naplánované uživateli v organizaci. Některé funkce zásad schůzky nemusí být implementovány v centru pro správu týmů (v dokumentaci jsou označeny "brzy"). V tomto případě nebo pokud se zobrazí chybová zpráva "tuto zásadu nyní nelze aktualizovat, ale opakujte akci později" v centru pro správu týmů společnosti Microsoft doporučujeme použít nástroj PowerShell k vytvoření nebo úpravě zásad schůzky. 

Další informace o zásadách schůzky naleznete v následujících zdrojích informací:

- Informace o vytváření zásad, provádění změn a přiřazování uživatelů k zásadám naleznete [v tématu Správa zásad schůzek v týmech](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams).

- Chcete-li provést změny zásad pomocí rutin prostředí PowerShell, viz [Přehled modulu PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview). 
    - Je třeba použít [modul Skype for Business PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) pro zásady schůzek. 
    - Další informace naleznete v [dokumentaci rutiny *-cparsmeetingpolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) .

**Poznámka:** Změna zásad může pro uživatele platit až 24 hodin. Je možné, že nebudete moci okamžitě provést změny nově vytvořených zásad. Vyčkejte 4 hodiny a pokuste se znovu upravit nově vytvořenou zásadu. Pokud potíže přetrvávají, zkuste prostředí PowerShell.  