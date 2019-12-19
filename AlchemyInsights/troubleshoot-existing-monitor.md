---
title: Poradce při potížích s existujícím monitorem
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3454"
- "9001450"
ms.openlocfilehash: d90baddd01bdf8508bd6289509c8399b8241887a
ms.sourcegitcommit: 42463e8d8869f36225a27388d83d37629c6b149e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/18/2019
ms.locfileid: "40738562"
---
# <a name="troubleshoot-an-existing-monitor"></a><span data-ttu-id="4d675-102">Odstraňování problémů s existujícím monitorem</span><span class="sxs-lookup"><span data-stu-id="4d675-102">Troubleshoot an existing monitor</span></span>

<span data-ttu-id="4d675-103">Vyzkoušejte tato řešení při řešení potíží s monitorem.</span><span class="sxs-lookup"><span data-stu-id="4d675-103">Try these solutions to troubleshoot a monitor.</span></span> 

<span data-ttu-id="4d675-104">**Aktualizujte displej monitoru:**</span><span class="sxs-lookup"><span data-stu-id="4d675-104">**Refresh your monitor's display:**</span></span>

<span data-ttu-id="4d675-105">Současně stiskněte následující klávesy: Klávesa Windows + CTRL + SHIFT + B. Tímto se bude aktualizovat komunikace s grafickým ovladačem.</span><span class="sxs-lookup"><span data-stu-id="4d675-105">Press the following keys at the same time: Windows Key  + Ctrl + Shift + B. This will refresh communication with your graphics driver.</span></span> <span data-ttu-id="4d675-106">Monitory na chvíli zabliká a po několika sekundách se vrátí.</span><span class="sxs-lookup"><span data-stu-id="4d675-106">Your monitors will blink momentarily and come back after a few seconds.</span></span>

<span data-ttu-id="4d675-107">**Odstraňování problémů s hardwarem monitoru:**</span><span class="sxs-lookup"><span data-stu-id="4d675-107">**Troubleshoot monitor hardware:**</span></span>

1. <span data-ttu-id="4d675-108">Odpojte kabel spojující počítač s monitorem a zapojte jej zpět.</span><span class="sxs-lookup"><span data-stu-id="4d675-108">Unplug the cable connecting your PC to your monitor, and plug it back in.</span></span>
2. <span data-ttu-id="4d675-109">Odpojte od počítače všechna nepodstatná zařízení (například adaptéry nebo doky).</span><span class="sxs-lookup"><span data-stu-id="4d675-109">Disconnect any non-essential devices from your PC (such as adapters or docks).</span></span>

<span data-ttu-id="4d675-110">**Pokud jste nedávno nainstalovali aktualizaci do počítače, můžete vrátit zpět ovladač obrazovky:**</span><span class="sxs-lookup"><span data-stu-id="4d675-110">**If you recently installed an update on your PC, you can roll back your display driver:**</span></span>

1. <span data-ttu-id="4d675-111">Klepněte na položku **Start**, zadejte příkaz **Správce zařízení**a z výsledků vyberte položku **Správce zařízení** .</span><span class="sxs-lookup"><span data-stu-id="4d675-111">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="4d675-112">Rozbalte část **grafické adaptéry** , klepněte pravým tlačítkem myši na grafický adaptér a vyberte příkaz **vlastnosti**.</span><span class="sxs-lookup"><span data-stu-id="4d675-112">Expand the **Display adapters** section, right-click your display adapter, ands select **Properties**.</span></span>
3. <span data-ttu-id="4d675-113">Přejděte na kartu **ovladač** a vyberte možnost **vrátit zpět ovladač**.</span><span class="sxs-lookup"><span data-stu-id="4d675-113">Navigate to the **Driver** tab and select **Roll Back Driver**.</span></span> <br>
<span data-ttu-id="4d675-114">Poznámka: Pokud tato možnost není k dispozici nebo je šedá, přejděte na další krok výběrem možnosti **ne** z následujícího seznamu.</span><span class="sxs-lookup"><span data-stu-id="4d675-114">Note: If this isn't available or is grayed out, select **No** from the options below to move to the next step.</span></span>
4. <span data-ttu-id="4d675-115">Aby se změny projevily, bude pravděpodobně nutné restartovat počítač.</span><span class="sxs-lookup"><span data-stu-id="4d675-115">You may need to restart your PC before these changes take effect.</span></span>

<span data-ttu-id="4d675-116">**Odinstalujte a přeinstalujte ovladač zobrazení:**</span><span class="sxs-lookup"><span data-stu-id="4d675-116">**Uninstall and reinstall your display driver:**</span></span>

1. <span data-ttu-id="4d675-117">Klepněte na položku **Start**, zadejte příkaz **Správce zařízení**a z výsledků vyberte položku **Správce zařízení** .</span><span class="sxs-lookup"><span data-stu-id="4d675-117">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="4d675-118">Rozbalte sekci **grafické adaptéry** , klepněte pravým tlačítkem myši na grafický adaptér, Andy vyberte **odinstalační zařízení**.</span><span class="sxs-lookup"><span data-stu-id="4d675-118">Expand the **Display adapters** section, right-click your display adapter, ands select **Uninstall device**.</span></span> 
3. <span data-ttu-id="4d675-119">Zaškrtněte políčko vedle možnosti **Odstranit software ovladače pro toto zařízení** a vyberte možnost **odinstalovat**.</span><span class="sxs-lookup"><span data-stu-id="4d675-119">Select the box next to **Delete the driver software for this device** and select **Uninstall**.</span></span><br>
<span data-ttu-id="4d675-120">Poznámka: v této fázi budete pravděpodobně požádáni o restartování počítače.</span><span class="sxs-lookup"><span data-stu-id="4d675-120">Note: You may be asked to restart your computer at this stage.</span></span> <span data-ttu-id="4d675-121">Před restartováním si poznamenejte zbývající instrukce.</span><span class="sxs-lookup"><span data-stu-id="4d675-121">Make sure to write down the remaining instructions before you restart.</span></span>
4. <span data-ttu-id="4d675-122">Spusťte Správce zařízení znovu.</span><span class="sxs-lookup"><span data-stu-id="4d675-122">Open Device Manager again.</span></span>
5. <span data-ttu-id="4d675-123">Rozbalte část **grafické adaptéry** , klepněte pravým tlačítkem myši na grafický adaptér a vyberte příkaz **Aktualizovat ovladač**.</span><span class="sxs-lookup"><span data-stu-id="4d675-123">Expand the **Display adapters** section, right-click on your display adapter, and select **Update Driver**.</span></span>
6. <span data-ttu-id="4d675-124">Vyberte **automatické vyhledávání pro aktualizaci softwaru ovladače** a postupujte podle pokynů k instalaci.</span><span class="sxs-lookup"><span data-stu-id="4d675-124">Select **Search automatically for update driver software** and follow the installation instructions.</span></span>