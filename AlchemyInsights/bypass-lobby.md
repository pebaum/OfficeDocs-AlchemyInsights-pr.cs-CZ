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
ms.openlocfilehash: de665ca6defcd0d00d227435473e5a4ccf61bc82
ms.sourcegitcommit: 0495112ad4fd0e695140ec66d190e62f03030584
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/02/2019
ms.locfileid: "37376573"
---
# <a name="control-lobby-settings-and-level-of-participation"></a>Řídit nastavení lobby a úroveň účasti

Toto nastavení řídí, kteří účastníci schůzky čekají v hale před tím, než jsou přijati na schůzku, a úroveň účasti, kterou jsou na schůzce oprávněni. Pomocí nástroje PowerShell můžete aktualizovat nastavení zásad schůzky, které ještě nebylo implementováno (označeno "brzy") v centru pro správu týmů.  Viz níže příklad rutiny prostředí PowerShell, která umožňuje všem uživatelům obejít halu.  

- [Automaticky přiznat](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , že lidé jsou zásady pro organizátora, které řídí, zda se lidé připojí ke schůzce přímo nebo čekají v hale, dokud nejsou přijati ověřeným uživatelem.

- [Umožnit anonymním uživatelům zahájit schůzku](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je zásada pro jednotlivé organizátora, která řídí, zda se anonymní osoby, včetně B2B a federovaných uživatelů, mohou připojit ke schůzce uživatele bez ověřeného uživatele z organizace.

- [Umožnit uživatelům s telefonickým připojením obejít lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (která se**brzy blíží**) je politika jednotlivých organizátorů, která řídí, zda se lidé, kteří telefonuje telefonicky, připojí ke schůzce přímo nebo čekají v hale bez ohledu na nastavení **automaticky přiznali osoby** .

- [Umožnit organizátorům přepsání nastavení lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**brzy přijde**) je politika pro jednotlivé organizátora, která řídí, zda organizátor schůzky může přepsat nastavení v hale, které správce nastavil v **automatickém přiznání osob** a **Povolit telefonické připojení uživatelům obejít lobby** při plánování nové schůzky.

**Poznámka:** Chcete-li získat úplný přehled o zásadách schůzky společnosti Microsoft, přečtěte si [správu zásad schůzek v týmech](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) . 


**Příklad prostředí PowerShell**

Chcete-li všem uživatelům, včetně externích nebo anonymních uživatelů, umožnit obejít lobby, můžete k provedení této úlohy použít také prostředí PowerShell.  Zde je příklad úpravy globálních zásad schůzek v organizaci.   

(Přečtěte si předchozí dokumentaci, než tyto změny přesně pochopíte, co to umožňuje.)

Set-Cparsmeetingpolicy-identita Global-Autovvv \ uživatelé "Everyone"-AllowPSTNUsersToBypassLobby $True

Další informace naleznete v tématu [set-Cparsmeetingpolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).
