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
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="8a935-102">Řídit nastavení lobby a úroveň účasti</span><span class="sxs-lookup"><span data-stu-id="8a935-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="8a935-103">Pokud chcete všem, včetně telefonických, externích a anonymních uživatelů, umožnit obejít halu v týmu Microsoft týmy, můžete k tomu použít prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="8a935-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users to bypass the lobby in Microsoft Teams, you can use PowerShell to do it.</span></span> <span data-ttu-id="8a935-104">Zde je příklad úpravy globálních zásad schůzky pro vaši organizaci:</span><span class="sxs-lookup"><span data-stu-id="8a935-104">Here's an example of modifying the global meeting policy for your organization:</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="8a935-105">Tato rutina v současné době vyžaduje použití modulu Skype for Business PowerShell.</span><span class="sxs-lookup"><span data-stu-id="8a935-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="8a935-106">Chcete-li nastavit použití této rutiny, podívejte se na [správu zásad prostřednictvím prostředí PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span><span class="sxs-lookup"><span data-stu-id="8a935-106">To get setup to use this cmdlet, check out [Managing policies via PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span></span>

<span data-ttu-id="8a935-107">Můžete vytvořit novou zásadu, kterou pak budete muset použít pro uživatele.</span><span class="sxs-lookup"><span data-stu-id="8a935-107">You can set up a new policy, which you'll then need to apply it to users.</span></span> <span data-ttu-id="8a935-108">Pokud upravíte globální zásadu, bude automaticky použita i pro uživatele.</span><span class="sxs-lookup"><span data-stu-id="8a935-108">If you modify the Global policy it'll automatically apply to users.</span></span> <span data-ttu-id="8a935-109">U každé změny zásad je třeba vyčkat nejméně 4 hodiny a až 24 hodin, aby se zásady projevily.</span><span class="sxs-lookup"><span data-stu-id="8a935-109">For any policy change you need to wait at least 4 hours and up to 24 hours for the policies to take effect.</span></span>

<span data-ttu-id="8a935-110">Před provedením těchto změn si přečtěte následující dokumentaci, abyste přesně pochopili, co to umožňuje.</span><span class="sxs-lookup"><span data-stu-id="8a935-110">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>

## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="8a935-111">Principy týmů, které se řídí zásadami lobby</span><span class="sxs-lookup"><span data-stu-id="8a935-111">Understanding Teams meeting lobby policy controls</span></span>

- <span data-ttu-id="8a935-112">[Automaticky přiznat](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , že lidé jsou zásady pro organizátora, které řídí, zda se lidé připojí ke schůzce přímo nebo čekají v hale, dokud nejsou přijati ověřeným uživatelem.</span><span class="sxs-lookup"><span data-stu-id="8a935-112">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="8a935-113">[Umožnit anonymním uživatelům zahájit schůzku](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) je zásada pro jednotlivé organizátora, která řídí, zda se anonymní osoby, včetně B2B a federovaných uživatelů, mohou připojit ke schůzce uživatele bez ověřeného uživatele z organizace.</span><span class="sxs-lookup"><span data-stu-id="8a935-113">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="8a935-114">[Umožnit uživatelům s telefonickým připojením obejít lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (která se**brzy blíží**) je politika jednotlivých organizátorů, která řídí, zda se lidé, kteří telefonuje telefonicky, připojí ke schůzce přímo nebo čekají v hale bez ohledu na nastavení **automaticky přiznali osoby** .</span><span class="sxs-lookup"><span data-stu-id="8a935-114">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="8a935-115">[Umožnit organizátorům přepsání nastavení v hale](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**již brzy**) je politika pro jednotlivé organizátora, která řídí, zda organizátor schůzky může přepsat nastavení v hale, které správce nastavil v **automatickém přiznání osob** a **umožnit uživatelům telefonického připojení obejít lobby** při plánování nové schůzky.</span><span class="sxs-lookup"><span data-stu-id="8a935-115">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="8a935-116">**Poznámka:** Chcete-li získat úplný přehled o zásadách schůzky společnosti Microsoft, přečtěte si [správu zásad schůzek v týmech](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) .</span><span class="sxs-lookup"><span data-stu-id="8a935-116">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>
