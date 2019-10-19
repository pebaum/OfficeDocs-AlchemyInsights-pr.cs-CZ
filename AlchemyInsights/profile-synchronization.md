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
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36554326"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="edf52-102">Kdy se můj profil změní v synchronizaci s aplikací profilů uživatelů služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="edf52-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="edf52-103">Služba SharePoint Online používá k importu uživatelů a skupin do aplikace profilů uživatelů úlohu časovače importu služby Active Directory (AD Import).</span><span class="sxs-lookup"><span data-stu-id="edf52-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="edf52-104">Import adresáře AD synchronizuje změny z úložiště adresářů online služby SharePoint s aplikací profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="edf52-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="edf52-105">Tyto změny jsou zpracovány v dávkách.</span><span class="sxs-lookup"><span data-stu-id="edf52-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="edf52-106">Úloha časovače bude spuštěna, dokud nebudou změny synchronizovány.</span><span class="sxs-lookup"><span data-stu-id="edf52-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="edf52-107">Doba, po kterou je úloha spouštěna, závisí na počtu změn procesů.</span><span class="sxs-lookup"><span data-stu-id="edf52-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="edf52-108">Velký počet změn trvá déle.</span><span class="sxs-lookup"><span data-stu-id="edf52-108">A large number of changes takes longer.</span></span> <span data-ttu-id="edf52-109">Smlouva o rozsahu služeb (SLA) uvádí, že změna uživatele v adresáři služby SharePoint Online se odrazí v aplikaci profilů uživatelů za 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="edf52-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="edf52-110">Další informace o synchronizaci profilů uživatelů ve službě SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="edf52-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  

