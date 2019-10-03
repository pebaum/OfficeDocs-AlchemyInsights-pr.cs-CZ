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
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="05f3b-102">Řídit nastavení lobby a úroveň účasti</span><span class="sxs-lookup"><span data-stu-id="05f3b-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="05f3b-103">Toto nastavení řídí, kteří účastníci schůzky čekají v hale před tím, než jsou přijati na schůzku, a úroveň účasti, kterou jsou na schůzce oprávněni.</span><span class="sxs-lookup"><span data-stu-id="05f3b-103">These settings control which meeting participants wait in the lobby before they are admitted to the meeting and the level of participation they are allowed in a meeting.</span></span> <span data-ttu-id="05f3b-104">Pomocí nástroje PowerShell můžete aktualizovat nastavení zásad schůzky, které ještě nebylo implementováno (označeno "brzy") v centru pro správu týmů.</span><span class="sxs-lookup"><span data-stu-id="05f3b-104">You can use Powershell to update meeting policy settings that haven't yet been implemented (labeled "coming soon") in the Teams admin center.</span></span>  <span data-ttu-id="05f3b-105">Viz níže příklad rutiny prostředí PowerShell, která umožňuje všem uživatelům obejít halu.</span><span class="sxs-lookup"><span data-stu-id="05f3b-105">See below for an example PowerShell cmdlet that allows all users to bypass the lobby.</span></span>  

- <span data-ttu-id="05f3b-106">[Automaticky přiznat](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , že lidé jsou zásady pro organizátora, které řídí, zda se lidé připojí ke schůzce přímo nebo čekají v hale, dokud nejsou přijati ověřeným uživatelem.</span><span class="sxs-lookup"><span data-stu-id="05f3b-106">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="05f3b-107">[Umožnit anonymním uživatelům zahájit schůzku](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je zásada pro jednotlivé organizátora, která řídí, zda se anonymní osoby, včetně B2B a federovaných uživatelů, mohou připojit ke schůzce uživatele bez ověřeného uživatele z organizace.</span><span class="sxs-lookup"><span data-stu-id="05f3b-107">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="05f3b-108">[Umožnit uživatelům s telefonickým připojením obejít lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (která se**brzy blíží**) je politika jednotlivých organizátorů, která řídí, zda se lidé, kteří telefonuje telefonicky, připojí ke schůzce přímo nebo čekají v hale bez ohledu na nastavení **automaticky přiznali osoby** .</span><span class="sxs-lookup"><span data-stu-id="05f3b-108">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="05f3b-109">[Umožnit organizátorům přepsání nastavení lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**brzy přijde**) je politika pro jednotlivé organizátora, která řídí, zda organizátor schůzky může přepsat nastavení v hale, které správce nastavil v **automatickém přiznání osob** a **Povolit telefonické připojení uživatelům obejít lobby** při plánování nové schůzky.</span><span class="sxs-lookup"><span data-stu-id="05f3b-109">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="05f3b-110">**Poznámka:** Chcete-li získat úplný přehled o zásadách schůzky společnosti Microsoft, přečtěte si [správu zásad schůzek v týmech](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) .</span><span class="sxs-lookup"><span data-stu-id="05f3b-110">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span> 


<span data-ttu-id="05f3b-111">**Příklad prostředí PowerShell**</span><span class="sxs-lookup"><span data-stu-id="05f3b-111">**PowerShell example**</span></span>

<span data-ttu-id="05f3b-112">Chcete-li všem uživatelům, včetně externích nebo anonymních uživatelů, umožnit obejít lobby, můžete k provedení této úlohy použít také prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="05f3b-112">If you'd like to allow everyone, including external or anonymous users, to bypass the lobby, you can also use PowerShell to accomplish this task.</span></span>  <span data-ttu-id="05f3b-113">Zde je příklad úpravy globálních zásad schůzek v organizaci.</span><span class="sxs-lookup"><span data-stu-id="05f3b-113">Here's an example of modifying the global meeting policy for your organization.</span></span>   

<span data-ttu-id="05f3b-114">(Přečtěte si předchozí dokumentaci, než tyto změny přesně pochopíte, co to umožňuje.)</span><span class="sxs-lookup"><span data-stu-id="05f3b-114">(Be sure to review the documentation above before making these changes to understand exactly what this allows.)</span></span>

<span data-ttu-id="05f3b-115">Set-Cparsmeetingpolicy-identita Global-Autovvv \ uživatelé "Everyone"-AllowPSTNUsersToBypassLobby $True</span><span class="sxs-lookup"><span data-stu-id="05f3b-115">Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True</span></span>

<span data-ttu-id="05f3b-116">Další informace naleznete v tématu [set-Cparsmeetingpolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span><span class="sxs-lookup"><span data-stu-id="05f3b-116">For more information, see [Set-CsTeamsMeetingPolicy](https://docs.microsoft.com/powershell/module/skype/set-csteamsmeetingpolicy?view=skype-ps).</span></span>
