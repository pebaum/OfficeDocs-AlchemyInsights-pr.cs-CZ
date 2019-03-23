---
title: Obnova odstraněné kolekce webů
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 5/1/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: 1f9a66daf7bee43291b785b6260aec8725ee782f
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30753779"
---
# <a name="restore-a-deleted-site-collection"></a><span data-ttu-id="c90b2-102">Obnova odstraněné kolekce webů</span><span class="sxs-lookup"><span data-stu-id="c90b2-102">Restore a deleted site collection</span></span>

<span data-ttu-id="c90b2-103">Pokud správce odstraní kolekci webů classic, je umístěn do koše, kde je držena 93 dní před trvalým odstraněním kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="c90b2-103">When an admin deletes a classic site collection, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="c90b2-104">Chcete-li obnovit kolekci webů:</span><span class="sxs-lookup"><span data-stu-id="c90b2-104">To restore the site collection:</span></span>
  
1. <span data-ttu-id="c90b2-105">V centru klasické správy služby SharePoint klepněte na položku **Koš** na pásu karet.</span><span class="sxs-lookup"><span data-stu-id="c90b2-105">In the classic SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="c90b2-106">Zaškrtněte políčko u kolekce webů, kterou chcete obnovit.</span><span class="sxs-lookup"><span data-stu-id="c90b2-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="c90b2-107">Klepněte na tlačítko **Obnovení odstraněných položek**.</span><span class="sxs-lookup"><span data-stu-id="c90b2-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="c90b2-108">Chcete-li obnovit odstraněné komunikační web, můžete použít nový náhled center Správce služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c90b2-108">To restore a deleted communication site, you can use the new SharePoint admin center preview.</span></span> <span data-ttu-id="c90b2-109">Jinak je třeba použít PowerShell.</span><span class="sxs-lookup"><span data-stu-id="c90b2-109">Otherwise, you need to use PowerShell.</span></span> <span data-ttu-id="c90b2-110">Chcete-li obnovit na server, který patří do skupiny Office 365, musíte obnovit skupině ve středisku pro správce serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="c90b2-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="c90b2-111">Skupiny lze obnovit 30 dní po jejich jsou odstraněny.</span><span class="sxs-lookup"><span data-stu-id="c90b2-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

