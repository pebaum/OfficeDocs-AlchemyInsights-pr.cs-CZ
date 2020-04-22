---
title: Omezení přístupu na SharePointu nebo OneDrivu
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: ed8e97b20c96a7b46995c969074cc4cef3a787d9
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43715877"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="51b75-102">Omezení přístupu na SharePointu nebo OneDrivu</span><span class="sxs-lookup"><span data-stu-id="51b75-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="51b75-103">V SharePointu a OneDrivu můžete omezit přístup k položkám, jako jsou soubory, složky a seznamy, tím, že udělíte přístup jenom skupinám nebo jednotlivcům, ke kterým chcete mít přístup.</span><span class="sxs-lookup"><span data-stu-id="51b75-103">In SharePoint and OneDrive, you restrict access to items like files, folders, and lists by granting access only to groups or individuals you want to have access.</span></span> <span data-ttu-id="51b75-104">Ve výchozím nastavení se oprávnění v SharePointu dědí z vyšších míst v hierarchii.</span><span class="sxs-lookup"><span data-stu-id="51b75-104">By default, permissions in SharePoint are inherited from higher up in the hierarchy.</span></span> <span data-ttu-id="51b75-105">Soubor tedy dědí svá oprávnění ze složky, která dědí svá oprávnění z knihovny, která zdědí svá oprávnění z webu.</span><span class="sxs-lookup"><span data-stu-id="51b75-105">So a file inherits its permissions from the folder, which inherits its permissions from the library, which inherits its permissions from the site.</span></span>
  
<span data-ttu-id="51b75-106">Pokud nechcete sdílet všechny položky na webu, můžete je sdílet na vyšší úrovni (například sdílením celého webu) a pak přerušit dědičnost.</span><span class="sxs-lookup"><span data-stu-id="51b75-106">You can share at a higher level (such as by sharing an entire site) and then break inheritance if you don't want to share all the items on the site.</span></span> <span data-ttu-id="51b75-107">Nedoporučujeme to však, protože to v budoucnu zkomplikuje a zmatečně zkomplikuje a zmateční.</span><span class="sxs-lookup"><span data-stu-id="51b75-107">However, we don't recommend this because it makes maintaining the permissions more complex and confusing in the future.</span></span> <span data-ttu-id="51b75-108">Zde je to, co byste mohli udělat místo:</span><span class="sxs-lookup"><span data-stu-id="51b75-108">Here's what you could do instead:</span></span>
  
- <span data-ttu-id="51b75-109">Pokud například chcete sdílet veškerý obsah složky s výjimkou jednoho souboru v ní, přesuňte tento soubor do nového umístění, které není sdíleno.</span><span class="sxs-lookup"><span data-stu-id="51b75-109">If, for example, you want to share all the contents of a folder except for one file in it, move that file to a new location that isn't shared.</span></span>
    
- <span data-ttu-id="51b75-110">Pokud máte ve složce dvě podsložky a chcete sdílet jednu podsložku se skupinami A a B a povolit pouze skupinu A přístup k druhé podsložce, sdílejte nadřazenou složku se skupinou A a přidejte skupinu B do první podsložky.</span><span class="sxs-lookup"><span data-stu-id="51b75-110">If you have two subfolders in a folder, and you want to share one subfolder with groups A and B and allow only group A access to the second subfolder, share the parent folder with group A and add group B to the first subfolder.</span></span>
    
[<span data-ttu-id="51b75-111">Ukončení sdílení souboru nebo složky</span><span class="sxs-lookup"><span data-stu-id="51b75-111">Stop sharing a file or folder </span></span>](https://go.microsoft.com/fwlink/?linkid=2008861)
  

