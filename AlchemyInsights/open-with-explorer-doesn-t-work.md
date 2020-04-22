---
title: Otevřít v Průzkumníkovi nefunguje
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
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: dc939a3451ff4fe95e4aa5a999839a2c532b398c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713027"
---
# <a name="open-with-explorer-isnt-working"></a><span data-ttu-id="0c09b-102">Otevřít v Průzkumníkovi nefunguje</span><span class="sxs-lookup"><span data-stu-id="0c09b-102">Open with Explorer isn't working</span></span>

<span data-ttu-id="0c09b-103">Pokud **open s Průzkumníkem** nebo **zobrazení v Průzkumníku souborů** nefunguje, ujistěte se, že služba WebClient je nastavena na **spuštěno** podle následujících kroků.</span><span class="sxs-lookup"><span data-stu-id="0c09b-103">If **Open with Explorer** or **View in File Explorer** doesn't work make sure the WebClient service is set to **Running** by following the steps below.</span></span> <span data-ttu-id="0c09b-104">Otevření knihovny SharePointu nebo OneDrivu může například trvat dlouho, když služba není spuštěná.</span><span class="sxs-lookup"><span data-stu-id="0c09b-104">For example, it might take a long time to open a SharePoint or OneDrive library when the service is not running.</span></span> 
  
1. <span data-ttu-id="0c09b-105">Do vyhledávacího pole windows zadejte spustit, vyberte spustit aplikaci klasické pracovní plochy, zadejte services.msc a pak vyberte **Enter**.</span><span class="sxs-lookup"><span data-stu-id="0c09b-105">In the Windows search box, type run, select the Run desktop app, type services.msc, and then select **Enter**.</span></span>
    
2. <span data-ttu-id="0c09b-106">Přejděte dolů na službu WebClient a zkontrolujte sloupec **Stav.**</span><span class="sxs-lookup"><span data-stu-id="0c09b-106">Scroll down to the WebClient service and check the **Status** column.</span></span> <span data-ttu-id="0c09b-107">Pokud stav služby WebClient není **spuštěn**, poklepejte na službu, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="0c09b-107">If the WebClient service status is not **Running**, double-click the service, click **Start**, and then click **OK**.</span></span> <span data-ttu-id="0c09b-108">V případě potřeby povolte službu zaškrtnutím políčka **Ručně** nebo **Automaticky** v poli **Typ spuštění.**</span><span class="sxs-lookup"><span data-stu-id="0c09b-108">Enable the service, if needed, by selecting either **Manual** or **Automatic** in the **Startup type** box.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="0c09b-109">Informace o řešení problémů s otevřením v Průzkumníkovi souborů naleznete [v tématu Otevření v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665).</span><span class="sxs-lookup"><span data-stu-id="0c09b-109">To troubleshoot issues opening in File Explorer, see [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665).</span></span> <span data-ttu-id="0c09b-110">Prozkoumejte synchronizaci jako lepší alternativu: [Synchronizujte sharepointové soubory s novým klientem synchronizace OneDrivu](https://go.microsoft.com/fwlink/?linkid=871666).</span><span class="sxs-lookup"><span data-stu-id="0c09b-110">Explore sync as a better alternative: [Sync SharePoint files with the new OneDrive sync client](https://go.microsoft.com/fwlink/?linkid=871666).</span></span> 
  

