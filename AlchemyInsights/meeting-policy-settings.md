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
ms.openlocfilehash: b5599c9974eb1c112835a9f42e4ebdc926071ea2
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627567"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a>Správa zásad schůzky v týmu společnosti Microsoft

Zásady schůzky slouží k řízení funkcí, které jsou k dispozici účastníkům schůzky pro schůzky naplánované uživateli v organizaci. Některé funkce zásad schůzky nemusí být implementovány v centru pro správu týmů (v dokumentaci jsou označeny "brzy"). V tomto případě nebo pokud se zobrazí chybová zpráva "tuto zásadu nyní nelze aktualizovat, ale opakujte akci později" v centru pro správu týmů společnosti Microsoft doporučujeme použít nástroj PowerShell k vytvoření nebo úpravě zásad schůzky. 

Další informace o zásadách schůzky naleznete v následujících zdrojích informací:

- Informace o vytváření zásad, provádění změn a přiřazování uživatelů k zásadám naleznete [v tématu Správa zásad schůzek v týmech](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).

- Chcete-li provést změny zásad pomocí rutin prostředí PowerShell, viz [Přehled modulu PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview). 
    - Je třeba použít [modul Skype for Business PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) pro zásady schůzek. 
    - Další informace naleznete v [dokumentaci rutiny *-cparsmeetingpolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) .

**Poznámka:** Změna zásad může pro uživatele platit až 24 hodin. Je možné, že nebudete moci okamžitě provést změny nově vytvořených zásad. Vyčkejte 4 hodiny a pokuste se znovu upravit nově vytvořenou zásadu. Pokud potíže přetrvávají, zkuste prostředí PowerShell.  