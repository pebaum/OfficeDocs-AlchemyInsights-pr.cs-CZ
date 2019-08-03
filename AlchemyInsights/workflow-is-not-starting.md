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
ms.openlocfilehash: efd17c302ae6d857207e87e94d74d3794e94a83a
ms.sourcegitcommit: 204be4a6ae03700b75eae6b09b4e9ab283089fbf
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/03/2019
ms.locfileid: "36171769"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="b0356-102">Pracovní postup nelze spustit.</span><span class="sxs-lookup"><span data-stu-id="b0356-102">Workflow is not starting</span></span>

- <span data-ttu-id="b0356-103">Pracovní postupy služby SharePoint 2010 a SharePoint 2013 nejsou počáteční.</span><span class="sxs-lookup"><span data-stu-id="b0356-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    <span data-ttu-id="b0356-104">Pokud váš pracovní postup nelze spustit, pravděpodobně problém s dočasnou službu kde uživatelů může docházet k občasným zpožděním s průběh pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="b0356-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="b0356-105">Kontrola [Řídicí panel stavu služeb](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) zobrazíte, pokud vaše organizace klesá.</span><span class="sxs-lookup"><span data-stu-id="b0356-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    <span data-ttu-id="b0356-106">Pokud více než 24 hodin uplynulo od poprvé viděli tento problém, zkontrolujte protokolu lístek podpory.</span><span class="sxs-lookup"><span data-stu-id="b0356-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="b0356-107">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="b0356-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="b0356-108">Uveďte, prosím, nás alespoň 24 hodin, řešení.</span><span class="sxs-lookup"><span data-stu-id="b0356-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="b0356-109">Pracovní postupy služby SharePoint 2010 odloženo na start.</span><span class="sxs-lookup"><span data-stu-id="b0356-109">SharePoint 2010 workflows delayed on start.</span></span>

    <span data-ttu-id="b0356-110">K tomu dochází, pokud je aktivován pracovní postup ve velkých dávkách.</span><span class="sxs-lookup"><span data-stu-id="b0356-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="b0356-111">(například když některé položky jsou přidány najednou).</span><span class="sxs-lookup"><span data-stu-id="b0356-111">(for example, when several items are added at once).</span></span>

    <span data-ttu-id="b0356-112">Pracovní postupy nejsou určeny ke spuštění v reálném čase, takže zpoždění je chování podle návrhu.</span><span class="sxs-lookup"><span data-stu-id="b0356-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

    <span data-ttu-id="b0356-113">Pokud pracovní postup je složité Extensible objekt Markup Language (XMOL), může být pomalé kompilace.</span><span class="sxs-lookup"><span data-stu-id="b0356-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="b0356-114">Zkontrolujte, zda [v tomto](https://support.microsoft.com/en-us/kb/3043697) článku.</span><span class="sxs-lookup"><span data-stu-id="b0356-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    <span data-ttu-id="b0356-115">By měla zjednodušit pracovního postupu nebo změnit návrh pomocí typ platformy Microsoft SharePoint 2013 pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="b0356-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    <span data-ttu-id="b0356-116">Také rozrostla historie pracovního postupu, můžete chtít vymazat položky nebo vytvořit nový seznam historie.</span><span class="sxs-lookup"><span data-stu-id="b0356-116">Also, if your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

    <span data-ttu-id="b0356-117">Další informace: [Odstranění historie pracovního postupu](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="b0356-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="b0356-118">Související témata</span><span class="sxs-lookup"><span data-stu-id="b0356-118">Related topics</span></span>
<span data-ttu-id="b0356-119">Chcete zkusit aplikaci Microsoft toku v Online služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="b0356-119">Want to try Micrsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="b0356-120">Vytvoření toku</span><span class="sxs-lookup"><span data-stu-id="b0356-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="b0356-121">SharePoint a toku</span><span class="sxs-lookup"><span data-stu-id="b0356-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


