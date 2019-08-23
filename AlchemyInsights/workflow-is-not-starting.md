---
title: Pracovní postup nelze spustit.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: d4bfdb44c04eb6838f4a265e55a4873d14c78f6d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36557962"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="bb98c-102">Pracovní postup nelze spustit.</span><span class="sxs-lookup"><span data-stu-id="bb98c-102">Workflow is not starting</span></span>

- <span data-ttu-id="bb98c-103">Pracovní postupy služby SharePoint 2010 a SharePoint 2013 nejsou počáteční.</span><span class="sxs-lookup"><span data-stu-id="bb98c-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="bb98c-104">Pokud váš pracovní postup nelze spustit, pravděpodobně problém s dočasnou službu kde uživatelů může docházet k občasným zpožděním s průběh pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="bb98c-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="bb98c-105">Kontrola [Řídicí panel stavu služeb](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) zobrazíte, pokud vaše organizace klesá.</span><span class="sxs-lookup"><span data-stu-id="bb98c-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="bb98c-106">Pokud více než 24 hodin uplynulo od poprvé viděli tento problém, zkontrolujte protokolu lístek podpory.</span><span class="sxs-lookup"><span data-stu-id="bb98c-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="bb98c-107">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="bb98c-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="bb98c-108">Uveďte, prosím, nás alespoň 24 hodin, řešení.</span><span class="sxs-lookup"><span data-stu-id="bb98c-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="bb98c-109">Pracovní postupy služby SharePoint 2010 odloženo na start.</span><span class="sxs-lookup"><span data-stu-id="bb98c-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="bb98c-110">K tomu dochází, pokud je aktivován pracovní postup ve velkých dávkách.</span><span class="sxs-lookup"><span data-stu-id="bb98c-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="bb98c-111">(například když některé položky jsou přidány najednou).</span><span class="sxs-lookup"><span data-stu-id="bb98c-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="bb98c-112">Pracovní postupy nejsou určeny ke spuštění v reálném čase, takže zpoždění je chování podle návrhu.</span><span class="sxs-lookup"><span data-stu-id="bb98c-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="bb98c-113">Pokud pracovní postup je složité Extensible objekt Markup Language (XMOL), může být pomalé kompilace.</span><span class="sxs-lookup"><span data-stu-id="bb98c-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="bb98c-114">Zkontrolujte, zda [v tomto](https://support.microsoft.com/en-us/kb/3043697) článku.</span><span class="sxs-lookup"><span data-stu-id="bb98c-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    - <span data-ttu-id="bb98c-115">By měla zjednodušit pracovního postupu nebo změnit návrh pomocí typ platformy Microsoft SharePoint 2013 pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="bb98c-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="bb98c-116">Rozrostla se vaše historie pracovního postupu, můžete vymazat položky nebo vytvořit nový seznam historie.</span><span class="sxs-lookup"><span data-stu-id="bb98c-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="bb98c-117">Další informace: [Odstranění historie pracovního postupu](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="bb98c-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="bb98c-118">Související témata</span><span class="sxs-lookup"><span data-stu-id="bb98c-118">Related topics</span></span>
<span data-ttu-id="bb98c-119">Chcete vyzkoušet Microsoft Flow v Online služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="bb98c-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="bb98c-120">Vytvoření toku</span><span class="sxs-lookup"><span data-stu-id="bb98c-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="bb98c-121">SharePoint a toku</span><span class="sxs-lookup"><span data-stu-id="bb98c-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


