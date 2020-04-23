---
title: Poradce při potížích s aplikací Otevřít v Průzkumníkovi
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: cb26876d93a110b3b0addd7821206215c783f959
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759685"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="12aa2-102">Řešení problémů s aplikací Otevřít v Průzkumníkovi</span><span class="sxs-lookup"><span data-stu-id="12aa2-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="12aa2-103">Řešení běžných problémů s otevřením knihovny dokumentů na SharePointu nebo OneDrivu pomocí příkazu **Otevřít v Průzkumníkovi:**</span><span class="sxs-lookup"><span data-stu-id="12aa2-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="12aa2-104">Použijte internet explorer 10 nebo internet explorer 11.</span><span class="sxs-lookup"><span data-stu-id="12aa2-104">Use Internet Explorer 10 or Internet Explorer 11.</span></span> <span data-ttu-id="12aa2-105">**Otevřít s Průzkumníkem** není kompatibilní s Microsoft Edge, Google Chrome, Firefox a další.</span><span class="sxs-lookup"><span data-stu-id="12aa2-105">**Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="12aa2-106">**Otevřít v aplikaci Explorer** je zakázáno ve všech prohlížečích kromě aplikace Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="12aa2-106">**Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="12aa2-107">**Open with Explorer** není k dispozici v moderním prostředí pro sharepointové knihovny.</span><span class="sxs-lookup"><span data-stu-id="12aa2-107">**Open with Explorer** is not available in the modern experience for SharePoint libraries.</span></span> <span data-ttu-id="12aa2-108">Místo toho **použijte zobrazení v Průzkumníkovi** souborů.</span><span class="sxs-lookup"><span data-stu-id="12aa2-108">Use **View in File Explorer** instead.</span></span> <span data-ttu-id="12aa2-109">V **Průzkumníkovi** \> **souborů vyberte Zobrazit volby Zobrazení**.</span><span class="sxs-lookup"><span data-stu-id="12aa2-109">Select **View options** \> **View in File Explorer**.</span></span> <span data-ttu-id="12aa2-110">Zobrazení v Průzkumníkovi souborů není kompatibilní s Microsoft Edge, Google Chrome, Firefox a další.</span><span class="sxs-lookup"><span data-stu-id="12aa2-110">View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="12aa2-111">**Zobrazení v Průzkumníkovi souborů** je k dispozici pouze v aplikaci Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="12aa2-111">**View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="12aa2-112">Zkontrolujte, zda je spuštěna služba WebClient.</span><span class="sxs-lookup"><span data-stu-id="12aa2-112">Make sure the WebClient service is running.</span></span> <span data-ttu-id="12aa2-113">Do vyhledávacího pole windows zadejte spustit, vyberte spustit aplikaci klasické pracovní plochy, zadejte services.msc a stiskněte Enter.</span><span class="sxs-lookup"><span data-stu-id="12aa2-113">In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter.</span></span> <span data-ttu-id="12aa2-114">Přejděte dolů na službu WebClient a ujistěte se, že ve sloupci **Stav** se zobrazí zpráva Spuštěno.</span><span class="sxs-lookup"><span data-stu-id="12aa2-114">Scroll down to the WebClient service and make sure the **Status** column displays "Running."</span></span> <span data-ttu-id="12aa2-115">Pokud tomu tak není, poklepejte na službu, klikněte na **tlačítko Start**a potom klikněte na **tlačítko OK**.</span><span class="sxs-lookup"><span data-stu-id="12aa2-115">If it doesn't, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="12aa2-116">(Službu může být nutné nejprve povolit zaškrtnutím políčka **Ručně** nebo **Automaticky** v poli **Typ spuštění.)**</span><span class="sxs-lookup"><span data-stu-id="12aa2-116">(You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="12aa2-117">Otevření knihovny v Průzkumníkovi souborů je užitečné, pokud potřebujete jednou zkopírovat nebo přesunout více souborů a složek, ale pokud chcete v knihovně pravidelně pracovat, doporučujeme ji synchronizovat.</span><span class="sxs-lookup"><span data-stu-id="12aa2-117">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it.</span></span> <span data-ttu-id="12aa2-118">Informace o řešení problémů s otevřením v Průzkumníkovi souborů naleznete [v tématu Otevření v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="12aa2-118">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="12aa2-119">Informace o nastavení synchronizace najdete v [tématu Synchronizace sharepointových souborů s novým klientem synchronizace OneDrivu](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="12aa2-119">For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="12aa2-120">Další informace najdete v článku [Použití příkazu Otevřít v průzkumníkovi k řešení problémů v SharePointu Online.](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer)</span><span class="sxs-lookup"><span data-stu-id="12aa2-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer) for more information.</span></span> 
  

