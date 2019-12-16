---
title: Problémy s oprávněními při migraci
ms.author: pebaum
author: pebaum
ms.date: 9/18/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: cbec51a7-5513-4848-a9ae-cdf993e000a8
ms.openlocfilehash: 95bfbfdf002e457230479a860058c1cf7ab1f8c2
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40054407"
---
# <a name="user-profile-and-photo-synchronization"></a><span data-ttu-id="02387-102">Synchronizace profilů uživatelů a fotografií</span><span class="sxs-lookup"><span data-stu-id="02387-102">User Profile and Photo synchronization</span></span>

 <span data-ttu-id="02387-103">**Profil synchronizace fotografií** -uživatelé si mohou všimnout, že fotografie jejich profilu není synchronizována se službou SharePoint.</span><span class="sxs-lookup"><span data-stu-id="02387-103">**Profile Photo Synchronization** - Users may notice that their profile photo is not synchronizing to SharePoint.</span></span> <span data-ttu-id="02387-104">Nebo se možná pokusili aktualizovat fotografii a Fotografie se stále zobrazuje jako stará fotka.</span><span class="sxs-lookup"><span data-stu-id="02387-104">Or, they may have tried to update their profile photo and the photo still appears as the old photo.</span></span> <span data-ttu-id="02387-105">Chcete-li zajistit, aby fotografie profilu byla zobrazena očekávaným způsobem, bude nutné, aby uživatel zahájil synchronizaci fotografií.</span><span class="sxs-lookup"><span data-stu-id="02387-105">To ensure the profile photo shows as expected, the user will need to initiate a photo sync.</span></span> 
  
<span data-ttu-id="02387-106">Další informace o procesu synchronizace fotografií naleznete [v části informace o synchronizaci obrázků profilů v sadě Office 365](https://go.microsoft.com/fwlink/?linkid=2022634)</span><span class="sxs-lookup"><span data-stu-id="02387-106">For more information about the photo synchronization process, see [Information about profile picture synchronization in Office 365](https://go.microsoft.com/fwlink/?linkid=2022634)</span></span>
  
- <span data-ttu-id="02387-107">**Synchronizace profilů** -doba potřebná k dokončení synchronizace profilu závisí na počtu změn (práce), které musí úloha importu služby AD zpracovat.</span><span class="sxs-lookup"><span data-stu-id="02387-107">**Profile Synchronization** - The time that's required to complete a profile synchronization depends on the number of changes (work) the AD Import Job has to process.</span></span> <span data-ttu-id="02387-108">Pokud existuje mnoho změn, úloha časovače má mnoho práce a bude trvat déle, než se změny projeví v aplikaci profilů uživatelů.</span><span class="sxs-lookup"><span data-stu-id="02387-108">If there are many changes, the timer job has a lot of work to do, and it will take longer for the changes to be reflected in the User Profile Application.</span></span> <span data-ttu-id="02387-109">Pokud má úloha časovače menší objem práce, projeví se změny v aplikaci profilů uživatelů mnohem rychleji.</span><span class="sxs-lookup"><span data-stu-id="02387-109">If the timer job has a small volume of work to do, the changes will be reflected in the User Profile Application much faster.</span></span> 
  
<span data-ttu-id="02387-110">Další informace o procesu synchronizace profilů naleznete [v tématu informace o synchronizaci profilů uživatelů ve službě SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2022639) .</span><span class="sxs-lookup"><span data-stu-id="02387-110">For more information about the profile synchronization process, see [Information about user profile synchronization in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2022639)</span></span>
    
- <span data-ttu-id="02387-111">**Aktualizovat profil v sadě Office Delve** -Delve uživatelé mohou spravovat svůj profil sady Office 365.</span><span class="sxs-lookup"><span data-stu-id="02387-111">**Update Profile in Office Delve** - Delve users can manage their Office 365 Profile.</span></span> <span data-ttu-id="02387-112">Další informace naleznete v tématu [zobrazení a aktualizace vašeho profilu v sadě Office Delve](https://support.office.com/article/View-and-update-your-profile-in-Office-Delve-4e84343b-eedf-45a1-aeb9-8627ccca14ba).</span><span class="sxs-lookup"><span data-stu-id="02387-112">For more information, see [View and Update your profile in Office Delve](https://support.office.com/article/View-and-update-your-profile-in-Office-Delve-4e84343b-eedf-45a1-aeb9-8627ccca14ba).</span></span>
    

