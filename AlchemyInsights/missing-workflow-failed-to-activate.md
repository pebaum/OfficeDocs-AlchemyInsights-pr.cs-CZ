---
title: Při aktivaci nenalezeného pracovního postupu došlo k chybě.
ms.author: pebaum
author: pebaum
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 3df1ddc1059c4cd6cc3f9f42dc157d20be79a63a
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052606"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="62f62-102">Při aktivaci nenalezeného pracovního postupu došlo k chybě.</span><span class="sxs-lookup"><span data-stu-id="62f62-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="62f62-103">V kolekci webů služby Microsoft SharePoint nelze přidat globálně opakovaně použitelný pracovní postup (například "schválení-SharePoint 2010") do seznamu nebo knihovny.</span><span class="sxs-lookup"><span data-stu-id="62f62-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="62f62-104">Tento problém vyřešíte následujícím postupem:</span><span class="sxs-lookup"><span data-stu-id="62f62-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="62f62-105">Otevřete kořenový web kolekce webů v aplikaci SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="62f62-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="62f62-106">V části **objekty webu**vyberte **pracovní postupy**.</span><span class="sxs-lookup"><span data-stu-id="62f62-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="62f62-107">V **nové** části pásu karet **pracovních postupů** vyberte možnost **opakovaně použitelný pracovní postup**.</span><span class="sxs-lookup"><span data-stu-id="62f62-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="62f62-108">Ve formuláři **vytvořit opakovaně použitelný pracovní postup** zadejte název \* \* *Repair2010* \* \*.</span><span class="sxs-lookup"><span data-stu-id="62f62-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="62f62-109">Pro **typ platformy**klepněte na možnost **pracovní postup služby SharePoint 2010**a pak klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="62f62-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="62f62-110">V části **Uložit** v pásu karet **pracovního postupu** vyberte možnost **publikovat**.</span><span class="sxs-lookup"><span data-stu-id="62f62-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="62f62-111">V části **Správa** pásu karet **pracovního postupu** vyberte možnost **publikovat globálně**.</span><span class="sxs-lookup"><span data-stu-id="62f62-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="62f62-112">V potvrzovacím dialogovém okně, které se zobrazí, klepněte na **tlačítko OK**.</span><span class="sxs-lookup"><span data-stu-id="62f62-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="62f62-113">Ve webovém prohlížeči vyhledejte kořenový web kolekce webů a potom přejděte k \> **funkcím kolekce webů** **Nastavení webu** .</span><span class="sxs-lookup"><span data-stu-id="62f62-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="62f62-114">Potom přepněte funkci **pracovních postupů** :</span><span class="sxs-lookup"><span data-stu-id="62f62-114">Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="62f62-115">· Pokud je tato funkce *aktivována* , klepněte na tlačítko **deaktivovat** a pak klepněte na tlačítko **aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="62f62-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="62f62-116">· Pokud je funkce *dezaktivována* , klepněte na tlačítko **aktivovat**.</span><span class="sxs-lookup"><span data-stu-id="62f62-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="62f62-117">Další informace naleznete v následujícím [článku](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="62f62-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

