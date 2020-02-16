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
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="d84b5-102">Správa zásad schůzek v Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="d84b5-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="d84b5-103">**Poznámka: Změny zásad mohou trvat až 24 hodin, než se změny zásad projeví pro uživatele.**</span><span class="sxs-lookup"><span data-stu-id="d84b5-103">**Note: It can take up to 24 hours for policy changes to take effect for users.**</span></span> <span data-ttu-id="d84b5-104">Je možné, že nebude možné okamžitě provést změny nově vytvořených zásad. počkejte 4 hodiny a pokuste se znovu upravit nově vytvořenou zásadu.</span><span class="sxs-lookup"><span data-stu-id="d84b5-104">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span>

<span data-ttu-id="d84b5-105">Zásady schůzky se používají k řízení funkcí, které jsou k dispozici účastníkům schůzky pro schůzky, které jsou naplánovány uživateli ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="d84b5-105">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="d84b5-106">Některé funkce zásad schůzky nemusí být ještě implementovány v Centru pro správu Týmů (ty jsou v dokumentaci označeny jako "již brzy").</span><span class="sxs-lookup"><span data-stu-id="d84b5-106">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="d84b5-107">V takovém případě nebo pokud se zobrazuje chyba jako "Zásady nemůžeme aktualizovat právě teď, ale zkuste to znovu" v Centru pro správu Microsoft Teams, doporučujeme použít PowerShell k vytvoření nebo úpravě zásad schůzky Teams.</span><span class="sxs-lookup"><span data-stu-id="d84b5-107">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="d84b5-108">Další informace o zásadách schůzky naleznete v následujících zdrojích:</span><span class="sxs-lookup"><span data-stu-id="d84b5-108">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="d84b5-109">Informace o vytváření zásad, provádění změn a přiřazování uživatelů k zásadám najdete v [tématu Správa zásad schůzky v Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="d84b5-109">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="d84b5-110">Změny zásad můžete provádět pomocí rutin prostředí PowerShell, přečtěte si v [tématu Přehled prostředí Teams PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="d84b5-110">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="d84b5-111">Pro zásady schůzek Teams musíte použít [modul PowerShell skypu pro firmy.](https://www.microsoft.com/download/details.aspx?id=39366)</span><span class="sxs-lookup"><span data-stu-id="d84b5-111">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="d84b5-112">Další informace naleznete [v dokumentaci k rutinám \*-CsTeamsMeetingPolicy.](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps)</span><span class="sxs-lookup"><span data-stu-id="d84b5-112">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

