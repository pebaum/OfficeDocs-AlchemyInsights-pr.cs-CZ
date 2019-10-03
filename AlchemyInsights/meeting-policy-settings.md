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
# <a name="manage-meeting-policies-in-microsoft-teams"></a><span data-ttu-id="fc50a-102">Správa zásad schůzky v týmu společnosti Microsoft</span><span class="sxs-lookup"><span data-stu-id="fc50a-102">Manage meeting policies in Microsoft Teams</span></span>

<span data-ttu-id="fc50a-103">Zásady schůzky slouží k řízení funkcí, které jsou k dispozici účastníkům schůzky pro schůzky naplánované uživateli v organizaci.</span><span class="sxs-lookup"><span data-stu-id="fc50a-103">Meeting policies are used to control the features that are available to meeting participants for meetings that are scheduled by users in your organization.</span></span> <span data-ttu-id="fc50a-104">Některé funkce zásad schůzky nemusí být implementovány v centru pro správu týmů (v dokumentaci jsou označeny "brzy").</span><span class="sxs-lookup"><span data-stu-id="fc50a-104">Some features of meeting policies might not be implemented in the Teams admin center yet (these are labeled "coming soon" in the documentation).</span></span> <span data-ttu-id="fc50a-105">V tomto případě nebo pokud se zobrazí chybová zpráva "tuto zásadu nyní nelze aktualizovat, ale opakujte akci později" v centru pro správu týmů společnosti Microsoft doporučujeme použít nástroj PowerShell k vytvoření nebo úpravě zásad schůzky.</span><span class="sxs-lookup"><span data-stu-id="fc50a-105">In this case, or if you are getting an error like "We can't update the policy right now but try it again later" in the Microsoft Teams admin center, we recommend that you use PowerShell to create or modify Teams meeting policies.</span></span> 

<span data-ttu-id="fc50a-106">Další informace o zásadách schůzky naleznete v následujících zdrojích informací:</span><span class="sxs-lookup"><span data-stu-id="fc50a-106">For more information about meeting policies, see the following resources:</span></span>

- <span data-ttu-id="fc50a-107">Informace o vytváření zásad, provádění změn a přiřazování uživatelů k zásadám naleznete [v tématu Správa zásad schůzek v týmech](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="fc50a-107">To learn about creating policies, making changes, and assigning users to the policy, see [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams).</span></span>

- <span data-ttu-id="fc50a-108">Chcete-li provést změny zásad pomocí rutin prostředí PowerShell, viz [Přehled modulu PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span><span class="sxs-lookup"><span data-stu-id="fc50a-108">To make policy changes using PowerShell cmdlets, see [Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview).</span></span> 
    - <span data-ttu-id="fc50a-109">Je třeba použít [modul Skype for Business PowerShell](https://www.microsoft.com/download/details.aspx?id=39366) pro zásady schůzek.</span><span class="sxs-lookup"><span data-stu-id="fc50a-109">You need to use the [Skype for Business PowerShell module](https://www.microsoft.com/download/details.aspx?id=39366) for Teams meeting policies.</span></span> 
    - <span data-ttu-id="fc50a-110">Další informace naleznete v [dokumentaci rutiny \*-cparsmeetingpolicy](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) .</span><span class="sxs-lookup"><span data-stu-id="fc50a-110">Review the [\*-CsTeamsMeetingPolicy cmdlets documentation](https://docs.microsoft.com/search/?search=CsTeamsMeetingPolicy&view=skype-ps) for more information.</span></span>

<span data-ttu-id="fc50a-111">**Poznámka:** Změna zásad může pro uživatele platit až 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="fc50a-111">**Note:** It can take up to 24 hours for policy changes to take effect for users.</span></span> <span data-ttu-id="fc50a-112">Je možné, že nebudete moci okamžitě provést změny nově vytvořených zásad. Vyčkejte 4 hodiny a pokuste se znovu upravit nově vytvořenou zásadu.</span><span class="sxs-lookup"><span data-stu-id="fc50a-112">You might not be able to make changes to newly created policies immediately; wait 4 hours and attempt to modify a newly created policy again.</span></span> <span data-ttu-id="fc50a-113">Pokud potíže přetrvávají, zkuste prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="fc50a-113">If you're still having problems, try PowerShell.</span></span>  