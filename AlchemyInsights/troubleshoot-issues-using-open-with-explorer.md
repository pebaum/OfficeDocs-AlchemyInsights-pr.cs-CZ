---
title: Řešení potíží pomocí otevřít pomocí Průzkumníka
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
ms.openlocfilehash: 6e67c2916e0c5739f6126064d45e175a7fd6f8d4
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36500208"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="8e169-102">Řešení potíží se službou otevřít v programu Průzkumník</span><span class="sxs-lookup"><span data-stu-id="8e169-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="8e169-103">Řešení běžných potíží s otevřením knihovny dokumentů služby SharePoint nebo OneDrive pomocí příkazu **Otevřít v Průzkumníkovi** :</span><span class="sxs-lookup"><span data-stu-id="8e169-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="8e169-104">Pomocí Internet Explorer 10 nebo Internet Explorer 11.</span><span class="sxs-lookup"><span data-stu-id="8e169-104">Use Internet Explorer 10 or Internet Explorer 11.</span></span> <span data-ttu-id="8e169-105">**Otevřít v aplikaci Explorer** není kompatibilní s Edge Microsoft, Google Chrome, Firefox a další.</span><span class="sxs-lookup"><span data-stu-id="8e169-105">**Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="8e169-106">**Otevřít pomocí Průzkumníka** je zakázáno ve všech prohlížečích s výjimkou Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="8e169-106">**Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="8e169-107">**Otevřít v Průzkumníkovi** není k dispozici v moderních zkušenosti pro knihovny služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8e169-107">**Open with Explorer** is not available in the modern experience for SharePoint libraries.</span></span> <span data-ttu-id="8e169-108">Místo toho použijte **zobrazení v Průzkumníku souborů** .</span><span class="sxs-lookup"><span data-stu-id="8e169-108">Use **View in File Explorer** instead.</span></span> <span data-ttu-id="8e169-109">Vyberte **Možnosti zobrazení** \> **zobrazení v Průzkumníku souborů**.</span><span class="sxs-lookup"><span data-stu-id="8e169-109">Select **View options** \> **View in File Explorer**.</span></span> <span data-ttu-id="8e169-110">Zobrazení v Průzkumníku souboru není kompatibilní s Edge Microsoft, Google Chrome, Firefox a další.</span><span class="sxs-lookup"><span data-stu-id="8e169-110">View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others.</span></span> <span data-ttu-id="8e169-111">**Zobrazení v Průzkumníku souboru** k dispozici pouze v aplikaci Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="8e169-111">**View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="8e169-112">Zkontrolujte, zda že je spuštěna služba Webový klient.</span><span class="sxs-lookup"><span data-stu-id="8e169-112">Make sure the WebClient service is running.</span></span> <span data-ttu-id="8e169-113">Do pole hledání systému Windows spustit, typ vyberte desktop app spustit, zadejte příkaz services.msc a stiskněte klávesu Enter.</span><span class="sxs-lookup"><span data-stu-id="8e169-113">In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter.</span></span> <span data-ttu-id="8e169-114">Přejděte na položku Služba Webový klient a ujistěte se, že ve sloupci **Stav** zobrazí "Spuštění."</span><span class="sxs-lookup"><span data-stu-id="8e169-114">Scroll down to the WebClient service and make sure the **Status** column displays "Running."</span></span> <span data-ttu-id="8e169-115">Pokud tomu tak není, poklepejte na položku služby, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="8e169-115">If it doesn't, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="8e169-116">(Pravděpodobně nutné nejprve povolit výběrem **Ruční** nebo **Automatické** v rozevíracím seznamu **Typ spouštění** .)</span><span class="sxs-lookup"><span data-stu-id="8e169-116">(You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="8e169-117">Otevření knihovny v Průzkumníku souborů je užitečné, pokud chcete kopírovat nebo přesouvat více souborů a složek po, ale pokud chcete pravidelně pracovat v knihovně, doporučujeme jeho synchronizací.</span><span class="sxs-lookup"><span data-stu-id="8e169-117">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it.</span></span> <span data-ttu-id="8e169-118">Problémů s otevřením v File Explorer, viz [Otevřít v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="8e169-118">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="8e169-119">Informace o nastavení synchronizace naleznete v tématu [SharePoint synchronizace souborů pomocí nového klienta synchronizace OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="8e169-119">For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="8e169-120">Naleznete další informace v článku [použití příkazu "otevřít pomocí Průzkumníka" problémů v Online služby SharePoint](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) .</span><span class="sxs-lookup"><span data-stu-id="8e169-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) for more information.</span></span> 
  

