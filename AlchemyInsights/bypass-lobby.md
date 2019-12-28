---
title: Obejít lobby
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: 311af365a94b788182bb6870bca3f67b2ad802d0
ms.sourcegitcommit: 932981641dd8e973e28dfe346bbdf9c923111b13
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/27/2019
ms.locfileid: "40889075"
---
# <a name="control-lobby-settings-and-level-of-participation-in-teams"></a>Řídit nastavení lobby a úroveň účasti v týmech

Chcete-li všem uživatelům, včetně telefonických, externích a anonymních uživatelů, umožnit **obejít lobby**, použijte k provedení této úlohy nástroj PowerShell. Zde je příklad úpravy globálních zásad schůzek v organizaci.

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

Tato rutina v současné době vyžaduje použití modulu Skype for Business PowerShell. Chcete-li nastavit použití této rutiny, podívejte se na [správu zásad prostřednictvím prostředí PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).

Po nastavení zásad je nutné tuto zásadu použít pro uživatele. Pokud jste změnili globální zásadu, bude se automaticky vztahovat i na uživatele. Chcete-li, aby se zásady projevily, je třeba u každé změny zásad počkat minimálně **4 hodiny až 24 hodin** . 

Před provedením těchto změn si přečtěte následující dokumentaci, abyste přesně pochopili, co to umožňuje.


## <a name="understanding-teams-meeting-lobby-policy-controls"></a>Principy týmů, které se řídí zásadami lobby

Toto nastavení řídí, kteří účastníci schůzky čekají v hale před tím, než jsou přijati na schůzku, a úroveň účasti, kterou jsou na schůzce oprávněni. Pomocí prostředí PowerShell můžete aktualizovat nastavení zásad schůzky, které ještě nebylo implementováno (označeno "brzy") v centru pro správu týmů. Viz níže příklad rutiny prostředí PowerShell, která umožňuje všem uživatelům obejít halu.

- [Automaticky přiznat](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , že lidé jsou zásady pro organizátora, které řídí, zda se lidé připojí ke schůzce přímo nebo čekají v hale, dokud nejsou přijati ověřeným uživatelem.

- [Umožnit anonymním uživatelům zahájit schůzku](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je zásada pro jednotlivé organizátora, která řídí, zda se anonymní osoby, včetně B2B a federovaných uživatelů, mohou připojit ke schůzce uživatele bez ověřeného uživatele z organizace.

- [Umožnit uživatelům s telefonickým připojením obejít lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (která se**brzy blíží**) je politika jednotlivých organizátorů, která řídí, zda se lidé, kteří telefonuje telefonicky, připojí ke schůzce přímo nebo čekají v hale bez ohledu na nastavení **automaticky přiznali osoby** .

- [Umožnit organizátorům přepsání nastavení v hale](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**již brzy**) je politika pro jednotlivé organizátora, která řídí, zda organizátor schůzky může přepsat nastavení v hale, které správce nastavil v **automatickém přiznání osob** a **umožnit uživatelům telefonického připojení obejít lobby** při plánování nové schůzky.

**Poznámka:** Chcete-li získat úplný přehled o zásadách schůzky společnosti Microsoft, přečtěte si [správu zásad schůzek v týmech](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) .
