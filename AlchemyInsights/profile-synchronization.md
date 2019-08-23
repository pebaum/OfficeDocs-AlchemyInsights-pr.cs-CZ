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
ms.openlocfilehash: b9b90dad6c5fa41afcd4e4c9a929594735eca066
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36554326"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="6b9a4-102">Při změny profilu aplikace profilů uživatelů služby SharePoint synchronizovat?</span><span class="sxs-lookup"><span data-stu-id="6b9a4-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="6b9a4-103">SharePoint Online používá Active Directory Import úlohy časovače (AD Import) Import uživatelů a skupin do aplikace profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="6b9a4-104">AD Import synchronizuje změny z úložiště služby SharePoint Online adresáře aplikace profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="6b9a4-105">Tyto změny jsou zpracovány v dávkách.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="6b9a4-106">Úloha časovače se spustí, až budou změny synchronizovány.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="6b9a4-107">Čas potřebný ke spuštění úlohy závisí na počtu změn ke zpracování.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="6b9a4-108">Velký počet změn trvá déle.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-108">A large number of changes takes longer.</span></span> <span data-ttu-id="6b9a4-109">Smlouvy úrovně služeb (SLA) uvádí, že změna k uživateli v adresáři služby SharePoint Online se odrazí v aplikaci profilů uživatelů do 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="6b9a4-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="6b9a4-110">Další informace o synchronizace profilů uživatelů v Online služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="6b9a4-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

