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
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="c5964-102">Správa zásad schůzky v týmu společnosti Microsoft</span><span class="sxs-lookup"><span data-stu-id="c5964-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="c5964-103">Zásady schůzky slouží k řízení funkcí, které jsou k dispozici účastníkům schůzky pro schůzky naplánované uživateli v organizaci.</span><span class="sxs-lookup"><span data-stu-id="c5964-103">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="c5964-104">Některé funkce zásad schůzky nemusí být implementovány v centru pro správu týmů (v dokumentaci jsou označeny "brzy").</span><span class="sxs-lookup"><span data-stu-id="c5964-104">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="c5964-105">V tomto případě nebo pokud se zobrazí chybová zpráva "tuto zásadu nyní nelze aktualizovat, ale opakujte akci později" v centru pro správu týmů společnosti Microsoft doporučujeme použít nástroj PowerShell k vytvoření nebo úpravě zásad schůzky.</span><span class="sxs-lookup"><span data-stu-id="c5964-105">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="c5964-106">Další informace o zásadách schůzky naleznete v následujících zdrojích informací:</span><span class="sxs-lookup"><span data-stu-id="c5964-106">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="c5964-107">Informace o vytváření zásad, provádění změn a přiřazování uživatelů k zásadám naleznete [v tématu Správa zásad schůzek v týmech](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="c5964-107">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="c5964-108">Chcete-li provést změny zásad pomocí rutin prostředí PowerShell, viz [Přehled modulu PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="c5964-108">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="c5964-109">Je třeba použít [modul Skype for Business PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) pro zásady schůzek.</span><span class="sxs-lookup"><span data-stu-id="c5964-109">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="c5964-110">Další informace naleznete v [dokumentaci rutiny \*-cparsmeetingpolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) .</span><span class="sxs-lookup"><span data-stu-id="c5964-110">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

<span data-ttu-id="c5964-111">**Poznámka:** Změna zásad může pro uživatele platit až 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="c5964-111">**Note:** It can take up to 24 hours for policy changes to take effect for users.</span></span> <span data-ttu-id="c5964-112">Je možné, že nebudete moci okamžitě provést změny nově vytvořených zásad. Vyčkejte 4 hodiny a pokuste se znovu upravit nově vytvořenou zásadu.</span><span class="sxs-lookup"><span data-stu-id="c5964-112">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span> <span data-ttu-id="c5964-113">Pokud potíže přetrvávají, zkuste prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="c5964-113">If you're still having problems, try PowerShell.</span></span>  