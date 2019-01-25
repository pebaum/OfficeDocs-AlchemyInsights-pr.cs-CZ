---
title: Není možné otevřít v programu Průzkumník
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
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: b55fc7bd5670e655334ef7be368b245c8899633a
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29462467"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="98a44-102">Otevřít v programu Průzkumník není funkční.</span><span class="sxs-lookup"><span data-stu-id="98a44-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="98a44-p101">Pokud není možné **Otevřít pomocí Průzkumníka** nebo **zobrazení v Průzkumníku souborů** zkontrolujte, zda že služba Webový klient je nastavena ke **spuštění** pomocí následujících kroků. Například může trvat dlouhou dobu otevření knihovny služby SharePoint nebo OneDrive, pokud služba není spuštěna.</span><span class="sxs-lookup"><span data-stu-id="98a44-p101">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below. For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="98a44-105">Do pole hledání systému Windows spustit, typ vyberte desktop app spustit, zadejte services.msc a potom vyberte možnost **Enter**.</span><span class="sxs-lookup"><span data-stu-id="98a44-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="98a44-p102">Vyhledejte položku Služba Webový klient a zaškrtněte políčko ve sloupci **Stav** . Pokud stav služby Webový klient není **spuštěna**, poklepejte na položku služby, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**. Povolte službu, v případě potřeby v rozevíracím seznamu **Typ spouštění** vyberte **Ruční** nebo **Automatické** .</span><span class="sxs-lookup"><span data-stu-id="98a44-p102">Scroll down to the WebClient service and check the **Status** column. If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**. Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="98a44-p103">Problémů s otevřením v File Explorer, viz [Otevřít v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Zkoumání synchronizovat jako lepší alternativa: [SharePoint synchronizace souborů pomocí nového klienta synchronizace OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="98a44-p103">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

