---
title: Spuštění diagnostiky paměti Windows ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002959"
- "5661"
ms.openlocfilehash: 3fedc52d02f1f70743429d0313eda0361306c3f3
ms.sourcegitcommit: 18b080c2a5d741af01ec589158effc35ea7cf449
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/19/2020
ms.locfileid: "44357379"
---
# <a name="run-windows-memory-diagnostics-in-windows-10"></a><span data-ttu-id="6a2ec-102">Spuštění diagnostiky paměti Windows ve Windows 10</span><span class="sxs-lookup"><span data-stu-id="6a2ec-102">Run Windows Memory Diagnostics in Windows 10</span></span>

<span data-ttu-id="6a2ec-103">Pokud systém Windows a aplikace v počítači havaruje, zamrzá nebo jedná nestabilním způsobem, můžete mít potíže s pamětí počítače (RAM).</span><span class="sxs-lookup"><span data-stu-id="6a2ec-103">If Windows and apps on your PC are crashing, freezing, or acting in an unstable manner, you may have a problem with the PC’s memory (RAM).</span></span> <span data-ttu-id="6a2ec-104">Můžete spustit Diagnostika paměti systému Windows a zkontrolovat problémy s pamětí RAM počítače.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-104">You can run the Windows Memory Diagnostic to check for problems with the PC’s RAM.</span></span>

<span data-ttu-id="6a2ec-105">Do vyhledávacího pole na hlavním panelu zadejte **diagnostiku paměti**a vyberte **nástroj Diagnostika paměti systému Windows**.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-105">In the search box on your taskbar, type **memory diagnostic**, and then select **Windows Memory Diagnostic**.</span></span> 

<span data-ttu-id="6a2ec-106">Chcete-li spustit diagnostiku, počítač musí restartovat.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-106">To run the diagnostic, the PC needs to restart.</span></span> <span data-ttu-id="6a2ec-107">Máte možnost restartovat okamžitě (prosím, uložte svou práci a zavřete otevřené dokumenty a e-maily první), nebo naplánovat diagnostiku spustit automaticky při příštím restartování počítače:</span><span class="sxs-lookup"><span data-stu-id="6a2ec-107">You have the option to restart immediately (please save your work and close open documents and e-mails first), or schedule the diagnostic to run automatically the next time the PC restarts:</span></span>

![Diagnostika paměti systému Windows](media/windows-memory-diagnostic.png)

<span data-ttu-id="6a2ec-109">Po restartování počítače se **nástroj Diagnostika paměti systému Windows** spustí automaticky.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-109">When the PC restarts, the **Windows Memory Diagnostics Tool** will run automatically.</span></span> <span data-ttu-id="6a2ec-110">Stav a průběh se zobrazí při spuštění diagnostiky a máte možnost zrušit diagnostiku stisknutím klávesy **ESC** na klávesnici.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-110">Status and progress will be displayed as the diagnostics run, and you have the option of cancelling the diagnostics by hitting the **ESC** key on your keyboard.</span></span>

<span data-ttu-id="6a2ec-111">Po dokončení diagnostiky se systém Windows spustí normálně.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-111">When the diagnostics are complete, Windows will start normally.</span></span>
<span data-ttu-id="6a2ec-112">Ihned po restartování, když se zobrazí plocha, se zobrazí oznámení (vedle ikony **Centra akcí** na hlavním panelu), které označuje, zda byly nalezeny nějaké chyby paměti.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-112">Immediately after restart, when the Desktop appears, a notification will appear (next to the **Action Center** icon on the taskbar), to indicate whether any memory errors were found.</span></span> <span data-ttu-id="6a2ec-113">Příklad:</span><span class="sxs-lookup"><span data-stu-id="6a2ec-113">For example:</span></span>

<span data-ttu-id="6a2ec-114">Tady je ikona Centra akcí:</span><span class="sxs-lookup"><span data-stu-id="6a2ec-114">Here's the Action Center icon:</span></span> ![Ikona Centra akcí](media/action-center-icon.png) 

<span data-ttu-id="6a2ec-116">A ukázkové oznámení:</span><span class="sxs-lookup"><span data-stu-id="6a2ec-116">And a sample notification:</span></span> ![Žádné chyby paměti](media/no-memory-errors.png)

<span data-ttu-id="6a2ec-118">Pokud jste oznámení zmeškali, můžete vybrat ikonu **Centrum akcí** na hlavním panelu, chcete-li zobrazit **Centrum akcí** a zobrazit posuvný seznam oznámení.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-118">If you missed the notification, you can select the **Action Center** icon  on the taskbar to display the **Action Center** and see a scrollable list of notifications.</span></span>

<span data-ttu-id="6a2ec-119">Chcete-li zkontrolovat podrobné informace, zadejte **událost** do vyhledávacího pole na hlavním panelu a vyberte **Prohlížeč událostí**.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-119">To review detailed information, type **event** into the search box on your taskbar, and then select **Event Viewer**.</span></span> <span data-ttu-id="6a2ec-120">V levém podokně **prohlížeče událostí**přejděte do > **systému Windows Logs**.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-120">In the **Event Viewer**’s left-hand pane, navigate to **Windows Logs > System**.</span></span> <span data-ttu-id="6a2ec-121">V pravém podokně naskenujete seznam při pohledu na sloupec **Zdroj,** dokud neuvidíte události se zdrojovou hodnotou **MemoryDiagnostics-Results**.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-121">In the right-hand pane, scan down the list while looking at the **Source** column, until you see events with Source value **MemoryDiagnostics-Results**.</span></span> <span data-ttu-id="6a2ec-122">Zvýrazněte každou takovou událost a podívejte se na informace o výsledku v poli pod kartou **Obecné** pod seznamem.</span><span class="sxs-lookup"><span data-stu-id="6a2ec-122">Highlight each such event and see the result information in the box under the **General** tab below the list.</span></span>
