---
title: Pracovní postup se nespouští.
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: 941e6349c98278a1a8cdac77457ec1cc72cdef8b
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766090"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="34cc9-102">Pracovní postup se nespouští.</span><span class="sxs-lookup"><span data-stu-id="34cc9-102">Workflow is not starting</span></span>

- <span data-ttu-id="34cc9-103">Pracovní postupy SharePointu 2010 a SharePointu 2013 se nespouštějí.</span><span class="sxs-lookup"><span data-stu-id="34cc9-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="34cc9-104">Pokud se pracovní postup nespouští, může se vyskytnout dočasný problém se službou, kdy uživatelé mohou zaznamenat občasné zpoždění s průběhem pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="34cc9-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="34cc9-105">Zkontrolujte [řídicí panel stavu služby](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) a zjistěte, zda má vliv na vaši organizaci.</span><span class="sxs-lookup"><span data-stu-id="34cc9-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="34cc9-106">Pokud uplynulo více než 24 hodin od prvního usty, přihlaste se k lístku podpory.</span><span class="sxs-lookup"><span data-stu-id="34cc9-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="34cc9-107">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="34cc9-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="34cc9-108">Dejte nám prosím alespoň 24 hodin na dokončení řešení.</span><span class="sxs-lookup"><span data-stu-id="34cc9-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="34cc9-109">Pracovní postupy SharePointu 2010 se při spuštění zpozdily.</span><span class="sxs-lookup"><span data-stu-id="34cc9-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="34cc9-110">K tomu dochází, pokud je pracovní postup spuštěn ve velkých dávkách.</span><span class="sxs-lookup"><span data-stu-id="34cc9-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="34cc9-111">(například při přidání několika položek najednou).</span><span class="sxs-lookup"><span data-stu-id="34cc9-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="34cc9-112">Pracovní postupy nejsou navrženy tak, aby spouštěli v reálném čase, takže zpoždění je chování podle návrhu.</span><span class="sxs-lookup"><span data-stu-id="34cc9-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="34cc9-113">Pokud je pracovní postup složitý jazyk xmlible object markup language (XMOL), kompilace může být pomalá.</span><span class="sxs-lookup"><span data-stu-id="34cc9-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="34cc9-114">Podívejte se na [tento](https://support.microsoft.com//kb/3043697) článek.</span><span class="sxs-lookup"><span data-stu-id="34cc9-114">Check [this](https://support.microsoft.com//kb/3043697) article.</span></span>

    - <span data-ttu-id="34cc9-115">Pracovní postup byste měli zjednodušit nebo jej přepracovat pomocí platformy pracovního postupu Microsoft SharePointu 2013.</span><span class="sxs-lookup"><span data-stu-id="34cc9-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="34cc9-116">Pokud se historie pracovního postupu rozrostla, můžete položky vymazat nebo vytvořit nový seznam historie.</span><span class="sxs-lookup"><span data-stu-id="34cc9-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="34cc9-117">Další informace : [Vymazání historie pracovního postupu](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="34cc9-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="34cc9-118">Související témata</span><span class="sxs-lookup"><span data-stu-id="34cc9-118">Related topics</span></span>
<span data-ttu-id="34cc9-119">Chcete vyzkoušet Microsoft Flow na SharePointu Online?</span><span class="sxs-lookup"><span data-stu-id="34cc9-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="34cc9-120">Vytvořit tok</span><span class="sxs-lookup"><span data-stu-id="34cc9-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="34cc9-121">SharePoint a tok</span><span class="sxs-lookup"><span data-stu-id="34cc9-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


