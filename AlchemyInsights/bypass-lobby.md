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
ms.openlocfilehash: 5ee77e57b3bc64d7a04256ab67b691e5205eac56
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/27/2019
ms.locfileid: "39626341"
---
# <a name="control-lobby-settings-and-level-of-participation"></a>Řídit nastavení lobby a úroveň účasti

Pokud chcete všem, včetně telefonických, externích a anonymních uživatelů, umožnit obejít halu v týmu Microsoft týmy, můžete k tomu použít prostředí PowerShell. Zde je příklad úpravy globálních zásad schůzky pro vaši organizaci:

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

Tato rutina v současné době vyžaduje použití modulu Skype for Business PowerShell. Chcete-li nastavit použití této rutiny, podívejte se na [správu zásad prostřednictvím prostředí PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).

Můžete vytvořit novou zásadu, kterou pak budete muset použít pro uživatele. Pokud upravíte globální zásadu, bude automaticky použita i pro uživatele. U každé změny zásad je třeba vyčkat nejméně 4 hodiny a až 24 hodin, aby se zásady projevily.

Před provedením těchto změn si přečtěte následující dokumentaci, abyste přesně pochopili, co to umožňuje.

## <a name="understanding-teams-meeting-lobby-policy-controls"></a>Principy týmů, které se řídí zásadami lobby

- [Automaticky přiznat](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , že lidé jsou zásady pro organizátora, které řídí, zda se lidé připojí ke schůzce přímo nebo čekají v hale, dokud nejsou přijati ověřeným uživatelem.

- [Umožnit anonymním uživatelům zahájit schůzku](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je zásada pro jednotlivé organizátora, která řídí, zda se anonymní osoby, včetně B2B a federovaných uživatelů, mohou připojit ke schůzce uživatele bez ověřeného uživatele z organizace.

- [Umožnit uživatelům s telefonickým připojením obejít lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (která se**brzy blíží**) je politika jednotlivých organizátorů, která řídí, zda se lidé, kteří telefonuje telefonicky, připojí ke schůzce přímo nebo čekají v hale bez ohledu na nastavení **automaticky přiznali osoby** .

- [Umožnit organizátorům přepsání nastavení v hale](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**již brzy**) je politika pro jednotlivé organizátora, která řídí, zda organizátor schůzky může přepsat nastavení v hale, které správce nastavil v **automatickém přiznání osob** a **umožnit uživatelům telefonického připojení obejít lobby** při plánování nové schůzky.

**Poznámka:** Chcete-li získat úplný přehled o zásadách schůzky společnosti Microsoft, přečtěte si [správu zásad schůzek v týmech](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) .
