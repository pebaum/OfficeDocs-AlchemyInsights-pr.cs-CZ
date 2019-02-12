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
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29905141"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="e421e-102">Omezení přístupu v serveru SharePoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="e421e-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="e421e-p101">V SharePoint a OneDrive můžete omezit přístup k položky, jako jsou soubory, složky a seznamy udělením přístupu pouze pro skupiny nebo jednotlivce, který má přístup. Ve výchozím nastavení oprávnění ve službě SharePoint zděděna z výše v hierarchii. Tak soubor dědí oprávnění ze složky, které dědí oprávnění z knihovny, který dědí oprávnění z webu.</span><span class="sxs-lookup"><span data-stu-id="e421e-p101">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access. By default, permissions in SharePoint are inherited from higher up in the hierarchy. So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="e421e-p102">Můžete sdílet na vyšší úrovni (například pomocí sdílení celého webu) a potom přerušit vztah dědičnosti, pokud chcete sdílet všechny položky na webu. Avšak nedoporučujeme to proto zachování oprávnění více složité a matoucí v budoucnosti. Zde je to, co byste mohli dělat místo toho:</span><span class="sxs-lookup"><span data-stu-id="e421e-p102">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site. However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future. Here's what you could do instead:</span></span>
  
- <span data-ttu-id="e421e-109">Pokud například chcete sdílet obsah složek s výjimkou jednoho souboru, tento soubor přesunete do nového umístění, který není sdílen.</span><span class="sxs-lookup"><span data-stu-id="e421e-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="e421e-110">Pokud máte dvě podsložky ve složce a chcete sdílet jednu podsložku s skupiny A a B povolit pouze skupiny A přístup k podsložce druhé, skupině A sdílet složku a přidat skupiny B první podsložky.</span><span class="sxs-lookup"><span data-stu-id="e421e-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="e421e-111">Zastavení sdílení souboru nebo složky</span><span class="sxs-lookup"><span data-stu-id="e421e-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

