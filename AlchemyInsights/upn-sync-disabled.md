---
title: Synchronizace UPN je zakázána.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 33bc7e30d41ff70e2ce55d946202acf45dbcb0f2
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43726097"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="3d087-102">Synchronizace UPN je zakázána.</span><span class="sxs-lookup"><span data-stu-id="3d087-102">UPN sync disabled</span></span>

<span data-ttu-id="3d087-103">Pokud jste začali synchronizovat s Azure AD před 30.</span><span class="sxs-lookup"><span data-stu-id="3d087-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="3d087-104">**Set-MsolDirSyncFeature -Funkce EnableSoftMatchOnUpn -Povolit $True**</span><span class="sxs-lookup"><span data-stu-id="3d087-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="3d087-105">Měkká shoda UPN se automaticky zapne pro organizace, které začaly synchronizovat s Azure AD na nebo po 30 března 2016.</span><span class="sxs-lookup"><span data-stu-id="3d087-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="3d087-106">Další informace o povolení měkké shody na UPN a dalších funkcí synchronizace, naleznete v [tématu Azure AD Connect funkce synchronizace služby](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="3d087-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  

