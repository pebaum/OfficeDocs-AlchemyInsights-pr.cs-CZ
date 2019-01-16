---
title: Obnova odstraněné kolekce webů
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 5/1/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: b3c72033dfcc093dd0c2837d2866c6a78d64449c
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281437"
---
# <a name="restore-a-deleted-site-collection"></a><span data-ttu-id="89626-102">Obnova odstraněné kolekce webů</span><span class="sxs-lookup"><span data-stu-id="89626-102">Restore a deleted site collection</span></span>

<span data-ttu-id="89626-p101">Pokud správce odstraní kolekci webů classic, je umístěn do koše, kde je držena 93 dní před trvalým odstraněním kolekce webů. Chcete-li obnovit kolekci webů:</span><span class="sxs-lookup"><span data-stu-id="89626-p101">When an admin deletes a classic site collection, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted. To restore the site collection:</span></span>
  
1. <span data-ttu-id="89626-105">V centru klasické správy služby SharePoint klepněte na položku **Koš** na pásu karet.</span><span class="sxs-lookup"><span data-stu-id="89626-105">In the classic SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="89626-106">Zaškrtněte políčko u kolekce webů, kterou chcete obnovit.</span><span class="sxs-lookup"><span data-stu-id="89626-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="89626-107">Klepněte na tlačítko **Obnovení odstraněných položek**.</span><span class="sxs-lookup"><span data-stu-id="89626-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="89626-p102">Chcete-li obnovit odstraněné komunikační web, můžete použít nový náhled center Správce služby SharePoint. Jinak je třeba použít PowerShell. Chcete-li obnovit na server, který patří do skupiny Office 365, musíte obnovit skupině ve středisku pro správce serveru Exchange. Skupiny lze obnovit 30 dní po jejich jsou odstraněny.</span><span class="sxs-lookup"><span data-stu-id="89626-p102">To restore a deleted communication site, you can use the new SharePoint admin center preview. Otherwise, you need to use PowerShell. To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center. Groups can be restored for 30 days after they're deleted.</span></span>
  

