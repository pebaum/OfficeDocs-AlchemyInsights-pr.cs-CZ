---
title: Trvalé odstranění webu v SharePointu
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.custom: ''
ms.assetid:
- "5200006"
- "4391"
ms.openlocfilehash: 263317339d965d173a5a038fa006e0ce6f8476cc
ms.sourcegitcommit: da04e79b6072321caa16a6ceea6eb5f15de22394
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/25/2020
ms.locfileid: "42955131"
---
# <a name="permanently-delete-a-site-in-sharepoint"></a><span data-ttu-id="3bc0a-102">Trvalé odstranění webu v SharePointu</span><span class="sxs-lookup"><span data-stu-id="3bc0a-102">Permanently delete a site in SharePoint</span></span>

<span data-ttu-id="3bc0a-103">Pokud chcete znovu použít adresu URL z odstraněného webu (pro jeho opětovné vytvoření) nebo trvale odstranit web, protože už nepoužíváte, můžete využít funkci \*\*trvalého odstranění \*\* v novém Centru pro správu SharePointu.</span><span class="sxs-lookup"><span data-stu-id="3bc0a-103">To reuse a URL from a deleted site (to recreate a site), or to permanently delete a site because it's no longer in use, you can use **Permanently Delete** from the New SharePoint Admin Center.</span></span> 

1. <span data-ttu-id="3bc0a-104">Přejděte na stránku [Odstraněné weby v novém Centru pro správu SharePointu](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) a přihlaste se pomocí účtu, který má pro vaši organizaci oprávnění správce.</span><span class="sxs-lookup"><span data-stu-id="3bc0a-104">Go to the [Deleted sites page of the new SharePoint admin center](https://admin.microsoft.com/sharepoint?page=recycleBin&modern=true) and sign in with an account that has admin permissions for your organization.</span></span> 

2. <span data-ttu-id="3bc0a-105">V levém sloupci vyberte web.</span><span class="sxs-lookup"><span data-stu-id="3bc0a-105">In the left column, select a site.</span></span> 

3. <span data-ttu-id="3bc0a-106">Klikněte na **Trvale odstranit**.</span><span class="sxs-lookup"><span data-stu-id="3bc0a-106">Click **Permanently Delete**.</span></span> 

<span data-ttu-id="3bc0a-107">**Poznámka**: Weby spojené se skupinou se nedají z nového Centra pro správu SharePointu odstranit trvale.</span><span class="sxs-lookup"><span data-stu-id="3bc0a-107">**Note**: Group-connected sites cannot be permanently deleted from the New SharePoint Admin Center.</span></span> <span data-ttu-id="3bc0a-108">Místo toho bude potřeba použít [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite).</span><span class="sxs-lookup"><span data-stu-id="3bc0a-108">[Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-spodeletedsite) will need to be used instead.</span></span>  

<span data-ttu-id="3bc0a-109">Další informace najdete v článku [Trvalé odstranění webu](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="3bc0a-109">For more info, see [Permanently delete a site](https://docs.microsoft.com/sharepoint/delete-site-collection#permanently-delete-a-site).</span></span> 
