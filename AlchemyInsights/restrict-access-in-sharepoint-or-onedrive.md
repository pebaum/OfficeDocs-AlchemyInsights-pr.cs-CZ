---
title: Omezení přístupu v serveru SharePoint nebo OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e0fbec6eb269a173664e2b9a1efe6eefb527b96f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32383864"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="c4a8f-102">Omezení přístupu v serveru SharePoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="c4a8f-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="c4a8f-103">V SharePoint a OneDrive můžete omezit přístup k položky, jako jsou soubory, složky a seznamy udělením přístupu pouze pro skupiny nebo jednotlivce, který má přístup.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-103">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access.</span></span> <span data-ttu-id="c4a8f-104">Ve výchozím nastavení oprávnění ve službě SharePoint zděděna z výše v hierarchii.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-104">By default, permissions in SharePoint are inherited from higher up in the hierarchy.</span></span> <span data-ttu-id="c4a8f-105">Tak soubor dědí oprávnění ze složky, které dědí oprávnění z knihovny, který dědí oprávnění z webu.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-105">So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="c4a8f-106">Můžete sdílet na vyšší úrovni (například pomocí sdílení celého webu) a potom přerušit vztah dědičnosti, pokud chcete sdílet všechny položky na webu.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-106">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site.</span></span> <span data-ttu-id="c4a8f-107">Avšak nedoporučujeme to proto zachování oprávnění více složité a matoucí v budoucnosti.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-107">However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future.</span></span> <span data-ttu-id="c4a8f-108">Zde je to, co byste mohli dělat místo toho:</span><span class="sxs-lookup"><span data-stu-id="c4a8f-108">Here's what you could do instead:</span></span>
  
- <span data-ttu-id="c4a8f-109">Pokud například chcete sdílet obsah složek s výjimkou jednoho souboru, tento soubor přesunete do nového umístění, který není sdílen.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="c4a8f-110">Pokud máte dvě podsložky ve složce a chcete sdílet jednu podsložku s skupiny A a B povolit pouze skupiny A přístup k podsložce druhé, skupině A sdílet složku a přidat skupiny B první podsložky.</span><span class="sxs-lookup"><span data-stu-id="c4a8f-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="c4a8f-111">Zastavení sdílení souboru nebo složky</span><span class="sxs-lookup"><span data-stu-id="c4a8f-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

