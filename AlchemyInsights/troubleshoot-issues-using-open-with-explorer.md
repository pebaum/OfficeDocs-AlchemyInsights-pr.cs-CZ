---
title: Řešení potíží pomocí otevřít pomocí Průzkumníka
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: 5be8a8f9f67939c7e2671855da259818269d9299
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281740"
---
# <a name="fix-problems-with-open-with-explorer"></a><span data-ttu-id="694fe-102">Řešení potíží se službou otevřít v programu Průzkumník</span><span class="sxs-lookup"><span data-stu-id="694fe-102">Fix problems with Open with Explorer</span></span>

<span data-ttu-id="694fe-103">Řešení běžných potíží s otevřením knihovny dokumentů služby SharePoint nebo OneDrive pomocí příkazu **Otevřít v Průzkumníkovi** :</span><span class="sxs-lookup"><span data-stu-id="694fe-103">Fix common problems with opening a document library in SharePoint or OneDrive using the **Open with Explorer** command:</span></span> 
  
- <span data-ttu-id="694fe-p101">Pomocí Internet Explorer 10 nebo Internet Explorer 11. **Otevřít v aplikaci Explorer** není kompatibilní s Edge Microsoft, Google Chrome, Firefox a další. **Otevřít pomocí Průzkumníka** je zakázáno ve všech prohlížečích s výjimkou Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="694fe-p101">Use Internet Explorer 10 or Internet Explorer 11. **Open with Explorer** isn't compatible with Microsoft Edge, Google Chrome, Firefox and others. **Open with Explorer** is disabled in all browsers except Internet Explorer.</span></span> 
    
- <span data-ttu-id="694fe-p102">**Otevřít v Průzkumníkovi** není k dispozici v moderních zkušenosti pro knihovny služby SharePoint. Místo toho použijte **zobrazení v Průzkumníku souborů** . Vyberte **Možnosti zobrazení** \> **zobrazení v Průzkumníku souborů**. Zobrazení v Průzkumníku souboru není kompatibilní s Edge Microsoft, Google Chrome, Firefox a další. **Zobrazení v Průzkumníku souboru** k dispozici pouze v aplikaci Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="694fe-p102">**Open with Explorer** is not available in the modern experience for SharePoint libraries. Use **View in File Explorer** instead. Select **View options** \> **View in File Explorer**. View in File Explorer is not compatible with Microsoft Edge, Google Chrome, Firefox and others. **View in File Explorer** in available only in Internet Explorer.</span></span> 
    
- <span data-ttu-id="694fe-p103">Zkontrolujte, zda že je spuštěna služba Webový klient. Do pole hledání systému Windows spustit, typ vyberte desktop app spustit, zadejte příkaz services.msc a stiskněte klávesu Enter. Přejděte na položku Služba Webový klient a ujistěte se, že ve sloupci **Stav** zobrazí "Spuštění." Pokud tomu tak není, poklepejte na položku služby, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**. (Pravděpodobně nutné nejprve povolit výběrem **Ruční** nebo **Automatické** v rozevíracím seznamu **Typ spouštění** .)</span><span class="sxs-lookup"><span data-stu-id="694fe-p103">Make sure the WebClient service is running. In the Windows search box, type run, select the Run desktop app, type services.msc, and then press Enter. Scroll down to the WebClient service and make sure the **Status** column displays "Running." If it doesn't, double-click the service, click **Start**, and then click **OK**. (You might need to first enable the service by selecting either **Manual** or **Automatic** in the **Startup type** box.)</span></span> 
    
> [!NOTE]
> <span data-ttu-id="694fe-p104">Otevření knihovny v Průzkumníku souborů je užitečné, pokud chcete kopírovat nebo přesouvat více souborů a složek po, ale pokud chcete pravidelně pracovat v knihovně, doporučujeme jeho synchronizací. Problémů s otevřením v File Explorer, viz [Otevřít v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Informace o nastavení synchronizace naleznete v tématu [SharePoint synchronizace souborů pomocí nového klienta synchronizace OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="694fe-p104">Opening a library in File Explorer is handy if you need to copy or move multiple files and folders once, but if you want to regularly work in the library, we recommend syncing it. To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). For info about setting up sync, see [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span>
  
<span data-ttu-id="694fe-120">Naleznete další informace v článku [použití příkazu "otevřít pomocí Průzkumníka" problémů v Online služby SharePoint](https://support.office.com/en-us/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) .</span><span class="sxs-lookup"><span data-stu-id="694fe-120">Please see the article [How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online](https://support.office.com/en-us/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) for more information.</span></span> 
  

