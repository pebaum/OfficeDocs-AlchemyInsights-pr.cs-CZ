---
title: Poradce při potížích s používáním programu Open v Průzkumníkovi
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: a9ab7dd27e4dc1bd76c93cc81260616063e638ed
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36742726"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="88ad3-102">Řešení potíží s otevřením v Průzkumníkovi</span><span class="sxs-lookup"><span data-stu-id="88ad3-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="88ad3-103">Řešení běžných potíží s otevřením knihovny dokumentů ve službě SharePoint nebo OneDrive pomocí příkazu **otevřít v programu Průzkumník** :</span><span class="sxs-lookup"><span data-stu-id="88ad3-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="88ad3-104">Použijte aplikaci Internet Explorer 10 nebo Internet Explorer 11.</span><span class="sxs-lookup"><span data-stu-id="88ad3-104">Use Internet Explorer 10 or Internet Explorer 11.</span></span> <span data-ttu-id="88ad3-105">**Otevřít v aplikaci Explorer** není kompatibilní s aplikací Microsoft Edge, Google Chrome, Firefox a dalšími.</span><span class="sxs-lookup"><span data-stu-id="88ad3-105">**Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="88ad3-106">**Otevřít v aplikaci Explorer** je zakázáno ve všech prohlížečích kromě aplikace Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="88ad3-106">**Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="88ad3-107">**Otevření v aplikaci Explorer** není k dispozici v moderních zkušenostech s knihovnami služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="88ad3-107">**Open with Explorer** is not available in the modern experience for SharePoint libraries.</span></span> <span data-ttu-id="88ad3-108">Místo toho použijte **zobrazení v Průzkumníku souborů** .</span><span class="sxs-lookup"><span data-stu-id="88ad3-108">Use **View in File Explorer** instead.</span></span> <span data-ttu-id="88ad3-109">\> **V Průzkumníku souborů**vyberte možnost **Zobrazit možnosti zobrazení** .</span><span class="sxs-lookup"><span data-stu-id="88ad3-109">Select **View options** \> **View in File Explorer**.</span></span> <span data-ttu-id="88ad3-110">Zobrazení v Průzkumníku souborů není kompatibilní s aplikací Microsoft Edge, Google Chrome, Firefox a dalšími.</span><span class="sxs-lookup"><span data-stu-id="88ad3-110">View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="88ad3-111">**Zobrazit v Průzkumníku souborů** , který je k dispozici pouze v aplikaci Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="88ad3-111">**View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="88ad3-112">Přesvědčte se, zda je spuštěna služba Webový klient.</span><span class="sxs-lookup"><span data-stu-id="88ad3-112">Make sure the WebClient service is running.</span></span> <span data-ttu-id="88ad3-113">V poli Hledat systému Windows zadejte příkaz Spustit, vyberte položku Spustit pracovní plochu, zadejte Services. msc a stiskněte klávesu ENTER.</span><span class="sxs-lookup"><span data-stu-id="88ad3-113">In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter.</span></span> <span data-ttu-id="88ad3-114">Přejděte dolů ke službě Webový klient a ujistěte se, že ve sloupci **stav** je zobrazeno "spuštěno".</span><span class="sxs-lookup"><span data-stu-id="88ad3-114">Scroll down to the WebClient service and make sure the **Status** column displays "Running."</span></span> <span data-ttu-id="88ad3-115">Pokud tomu tak není, poklepejte na službu, klepněte na tlačítko **Start**a potom na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="88ad3-115">If it doesn't, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="88ad3-116">(Službu bude pravděpodobně nutné nejprve povolit výběrem možnosti **ručně** nebo **automaticky** v poli **Typ spouštění** .)</span><span class="sxs-lookup"><span data-stu-id="88ad3-116">(You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="88ad3-117">Otevření knihovny v Průzkumníku souborů je užitečné v případě, že potřebujete zkopírovat nebo přesunout více souborů a složek, ale pokud chcete v knihovně pravidelně pracovat, doporučujeme jej synchronizovat.</span><span class="sxs-lookup"><span data-stu-id="88ad3-117">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it.</span></span> <span data-ttu-id="88ad3-118">Informace o řešení potíží s otevřením v Průzkumníku souborů naleznete [v tématu Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="88ad3-118">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="88ad3-119">Informace o nastavení synchronizace naleznete v tématu [synchronizujte soubory služby SharePoint s novým synchronním klientem OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="88ad3-119">For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="88ad3-120">Další informace naleznete v článku [použití příkazu otevřít v Průzkumníkovi k řešení potíží ve službě SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer) .</span><span class="sxs-lookup"><span data-stu-id="88ad3-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer) for more information.</span></span> 
  

