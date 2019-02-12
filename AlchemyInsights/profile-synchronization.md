---
title: Synchronizace profilů
ms.author: arnek
author: arnek
ms.date: 6/20/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: d1a72a85767e36fefbfa8eee266befcaf2e48af0
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29920081"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="0abdb-102">Při změny profilu aplikace profilů uživatelů služby SharePoint synchronizovat?</span><span class="sxs-lookup"><span data-stu-id="0abdb-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="0abdb-103">SharePoint Online používá Active Directory Import úlohy časovače (AD Import) Import uživatelů a skupin do aplikace profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="0abdb-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="0abdb-p101">AD Import synchronizuje změny z úložiště služby SharePoint Online adresáře aplikace profilů uživatelů. Tyto změny jsou zpracovány v dávkách.</span><span class="sxs-lookup"><span data-stu-id="0abdb-p101">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application. These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="0abdb-106">Úloha časovače se spustí, až budou změny synchronizovány.</span><span class="sxs-lookup"><span data-stu-id="0abdb-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="0abdb-p102">Čas potřebný ke spuštění úlohy závisí na počtu změn ke zpracování. Velký počet změn trvá déle. Smlouvy úrovně služeb (SLA) uvádí, že změna k uživateli v adresáři služby SharePoint Online se odrazí v aplikaci profilů uživatelů do 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="0abdb-p102">The time it takes the job to run depends on the number of changes to process. A large number of changes takes longer. The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="0abdb-110">Další informace o synchronizace profilů uživatelů v Online služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="0abdb-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

