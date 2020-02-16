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
- "9000734"
- "2657"
ms.openlocfilehash: 509bd0c686830c04ed27f97372411677c0a7f4a4
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/15/2020
ms.locfileid: "42042837"
---
# <a name="manage-meeting-policies-in-microsoft-teams"></a>Správa zásad schůzek v Microsoft Teams

**Poznámka: Změny zásad mohou trvat až 24 hodin, než se změny zásad projeví pro uživatele.** Je možné, že nebude možné okamžitě provést změny nově vytvořených zásad. počkejte 4 hodiny a pokuste se znovu upravit nově vytvořenou zásadu.

Zásady schůzky se používají k řízení funkcí, které jsou k dispozici účastníkům schůzky pro schůzky, které jsou naplánovány uživateli ve vaší organizaci. Některé funkce zásad schůzky nemusí být ještě implementovány v Centru pro správu Týmů (ty jsou v dokumentaci označeny jako "již brzy"). V takovém případě nebo pokud se zobrazuje chyba jako "Zásady nemůžeme aktualizovat právě teď, ale zkuste to znovu" v Centru pro správu Microsoft Teams, doporučujeme použít PowerShell k vytvoření nebo úpravě zásad schůzky Teams. 

Další informace o zásadách schůzky naleznete v následujících zdrojích:

- Informace o vytváření zásad, provádění změn a přiřazování uživatelů k zásadám najdete v [tématu Správa zásad schůzky v Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).

- Změny zásad můžete provádět pomocí rutin prostředí PowerShell, přečtěte si v [tématu Přehled prostředí Teams PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview). 
    - Pro zásady schůzek Teams musíte použít [modul PowerShell skypu pro firmy.](https://www.microsoft.com/download/details.aspx?id=39366) 
    - Další informace naleznete [v dokumentaci k rutinám *-CsTeamsMeetingPolicy.](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps)

