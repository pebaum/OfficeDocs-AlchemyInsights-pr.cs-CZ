---
title: Obnovení odstraněného webu
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: d37fd903c91c8cd6ac6137e815cb253f7edb4494
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/27/2020
ms.locfileid: "43912668"
---
# <a name="restore-a-deleted-site"></a><span data-ttu-id="a26aa-102">Obnovení odstraněného webu</span><span class="sxs-lookup"><span data-stu-id="a26aa-102">Restore a deleted site</span></span>

<span data-ttu-id="a26aa-103">Když správce odstraní sharepointový web, umístí se do koše kolekce webů, kde je uchováván 93 dní před jeho trvalým odstraněním.</span><span class="sxs-lookup"><span data-stu-id="a26aa-103">When an admin deletes a SharePoint site, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="a26aa-104">Obnovení webu:</span><span class="sxs-lookup"><span data-stu-id="a26aa-104">To restore the site:</span></span>
  
1. <span data-ttu-id="a26aa-105">V novém Centru pro správu SharePointu klikněte na pásu karet na **Koš.**</span><span class="sxs-lookup"><span data-stu-id="a26aa-105">In the new SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="a26aa-106">Zaškrtněte políčko vedle kolekce webů, kterou chcete obnovit.</span><span class="sxs-lookup"><span data-stu-id="a26aa-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="a26aa-107">Klepněte na **tlačítko Obnovit odstraněné položky**.</span><span class="sxs-lookup"><span data-stu-id="a26aa-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="a26aa-108">Chcete-li obnovit odstraněný komunikační web, můžete použít nové Centrum pro správu SharePointu.</span><span class="sxs-lookup"><span data-stu-id="a26aa-108">To restore a deleted communication site, you can use the new SharePoint admin center.</span></span> <span data-ttu-id="a26aa-109">V opačném případě je třeba použít prostředí Microsoft PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a26aa-109">Otherwise, you need to use Microsoft PowerShell.</span></span> <span data-ttu-id="a26aa-110">Pokud chcete obnovit web, který patří do skupiny Microsoft 365, je třeba ji obnovit v Centru pro správu Exchange.</span><span class="sxs-lookup"><span data-stu-id="a26aa-110">To restore a site that belongs to an Microsoft 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="a26aa-111">Skupiny lze obnovit po dobu 30 dnů po jejich odstranění.</span><span class="sxs-lookup"><span data-stu-id="a26aa-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

