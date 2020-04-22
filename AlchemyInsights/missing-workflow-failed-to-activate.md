---
title: Aktivace chybějícího pracovního postupu se nezdařila.
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 2598111005c219c398b63ca374e8e99348efc02c
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43762094"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="86527-102">Aktivace chybějícího pracovního postupu se nezdařila.</span><span class="sxs-lookup"><span data-stu-id="86527-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="86527-103">V kolekci webů služby Microsoft SharePoint nelze do seznamu nebo knihovny přidat globálně opakovaně použitelný pracovní postup (například Schválení – SharePoint 2010).</span><span class="sxs-lookup"><span data-stu-id="86527-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="86527-104">Chcete-li tento problém vyřešit, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="86527-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="86527-105">Otevřete kořenový web kolekce webů v SharePoint Designeru 2013.</span><span class="sxs-lookup"><span data-stu-id="86527-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="86527-106">V části **Objekty webu**vyberte **Pracovní postupy**.</span><span class="sxs-lookup"><span data-stu-id="86527-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="86527-107">V části **Nový** pás **u pásu karet Pracovní postupy** vyberte opakovaně použitelný pracovní **postup**.</span><span class="sxs-lookup"><span data-stu-id="86527-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="86527-108">Ve formuláři **Vytvořit opakovaně použitelný pracovní postup** zadejte název \*\* *Repair2010* \*\*.</span><span class="sxs-lookup"><span data-stu-id="86527-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="86527-109">V **položce Typ platformy**klikněte na **Pracovní postup SharePointu 2010**a potom klikněte na **OK**.</span><span class="sxs-lookup"><span data-stu-id="86527-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="86527-110">V části **Uložit** na pásu **karet pracovního postupu** vyberte **Publikovat**.</span><span class="sxs-lookup"><span data-stu-id="86527-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="86527-111">V části **Spravovat** na pásu **karet pracovního postupu** vyberte Publikovat **globálně**.</span><span class="sxs-lookup"><span data-stu-id="86527-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="86527-112">V zobrazeném potvrzovacím dialogovém okně vyberte **ok**.</span><span class="sxs-lookup"><span data-stu-id="86527-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="86527-113">Ve webovém prohlížeči vyhledejte kořenový web kolekce webů a potom získejte přístup k **funkcím kolekce webů** **Nastavení** \> webu .</span><span class="sxs-lookup"><span data-stu-id="86527-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="86527-114">Potom přepněte funkci **Pracovní postupy:**</span><span class="sxs-lookup"><span data-stu-id="86527-114">Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="86527-115">· Pokud je funkce *aktivována* , klepněte na **tlačítko Deaktivovat** a potom klepněte na tlačítko **Aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="86527-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="86527-116">· Pokud je funkce *deaktivována* , klepněte na **tlačítko Aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="86527-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="86527-117">Další informace naleznete v následujícím [článku](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="86527-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

