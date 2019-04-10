---
title: Obnovení odstraněných webů
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
ms.openlocfilehash: 0cf10a3a0effc1774d8a07c5d0be96384362c175
ms.sourcegitcommit: 228c986911ecf73217116a5d1fdcd2e89362774e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/09/2019
ms.locfileid: "31747771"
---
# <a name="restore-a-deleted-site"></a><span data-ttu-id="f70a0-102">Obnovení odstraněných webů</span><span class="sxs-lookup"><span data-stu-id="f70a0-102">Restore a deleted site</span></span>

<span data-ttu-id="f70a0-103">Pokud správce odstraní web, je umístěn do koše, kde je držena 93 dní před trvalým odstraněním kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="f70a0-103">When an admin deletes a site , it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="f70a0-104">Chcete-li obnovit na webu:</span><span class="sxs-lookup"><span data-stu-id="f70a0-104">To restore the site:</span></span>
  
1. <span data-ttu-id="f70a0-105">V centru nového správce služby SharePoint na pásu karet klepněte na tlačítko **Koš** .</span><span class="sxs-lookup"><span data-stu-id="f70a0-105">In the new SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="f70a0-106">Zaškrtněte políčko u kolekce webů, kterou chcete obnovit.</span><span class="sxs-lookup"><span data-stu-id="f70a0-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="f70a0-107">Klepněte na tlačítko **Obnovení odstraněných položek**.</span><span class="sxs-lookup"><span data-stu-id="f70a0-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="f70a0-108">Chcete-li obnovit odstraněné komunikační web, můžete použít nové Centrum správy služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f70a0-108">To restore a deleted communication site, you can use the new SharePoint admin center.</span></span> <span data-ttu-id="f70a0-109">V ostatních případech je nutné použít Microsoft PowerShell.</span><span class="sxs-lookup"><span data-stu-id="f70a0-109">Otherwise, you need to use Microsoft PowerShell.</span></span> <span data-ttu-id="f70a0-110">Chcete-li obnovit na server, který patří do skupiny Office 365, musíte obnovit skupině ve středisku pro správce serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="f70a0-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="f70a0-111">Skupiny lze obnovit 30 dní po jejich jsou odstraněny.</span><span class="sxs-lookup"><span data-stu-id="f70a0-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

