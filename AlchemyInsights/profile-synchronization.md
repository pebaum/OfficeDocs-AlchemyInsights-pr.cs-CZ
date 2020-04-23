---
title: Synchronizace profilu
ms.author: arnek
author: arnek
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: dc6e0280961d14aa3e6bd466afbe0cbe89418d17
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43768106"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="9c7ed-102">Kdy se změny profilu synchronizují s aplikací profilu uživatele služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="9c7ed-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="9c7ed-103">SharePoint Online používá úlohu časovače importu služby Active Directory (Import služby AD) k importu uživatelů a skupin do aplikace profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="9c7ed-104">Import služby AD synchronizuje změny z úložiště adresářů SharePointu Online do aplikace profiluživatele.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="9c7ed-105">Tyto změny jsou zpracovány v dávkách.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="9c7ed-106">Úloha časovače se spustí, dokud nejsou synchronizovány změny.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="9c7ed-107">Čas potřebný ke spuštění úlohy závisí na počtu změn procesu.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="9c7ed-108">Velký počet změn trvá déle.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-108">A large number of changes takes longer.</span></span> <span data-ttu-id="9c7ed-109">Smlouva o úrovni služeb (SLA) uvádí, že změna uživatele v adresáři SharePointu Online se projeví v aplikaci profil uživatele do 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="9c7ed-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="9c7ed-110">Další informace o synchronizaci profilu uživatelů v SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="9c7ed-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

