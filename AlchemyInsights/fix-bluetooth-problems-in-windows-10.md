---
title: Oprava problémů s Bluetooth ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001475"
- "3506"
ms.openlocfilehash: 94dda7a42632f57ce3aef5f467b87df1033b8d49
ms.sourcegitcommit: 9a35768444824cde9e192f1d9daafc9157437244
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/25/2020
ms.locfileid: "42268591"
---
# <a name="fix-bluetooth-problems-in-windows-10"></a><span data-ttu-id="d737f-102">Oprava problémů s Bluetooth ve Windows 10</span><span class="sxs-lookup"><span data-stu-id="d737f-102">Fix Bluetooth problems in Windows 10</span></span>

<span data-ttu-id="d737f-103">Pokud ikona Bluetooth chybí nebo bluetooth nelze zapnout nebo vypnout, můžete spustit poradce při potížích s Technologií Bluetooth.</span><span class="sxs-lookup"><span data-stu-id="d737f-103">If the Bluetooth icon is missing or Bluetooth can't be turned on or off, you may want to run the Bluetooth troubleshooter.</span></span> <span data-ttu-id="d737f-104">[Otevřete nastavení poradce při potížích](ms-settings:troubleshoot), klepněte na **tlačítko Bluetooth** v části **Najít a opravit další problémy**, klepněte na **tlačítko Spustit poradce při potížích**.</span><span class="sxs-lookup"><span data-stu-id="d737f-104">[Open the Troubleshoot settings](ms-settings:troubleshoot), click **Bluetooth** under **Find and fix other problems**, click **Run the troubleshooter**.</span></span>

<span data-ttu-id="d737f-105">Pokud ikonu Bluetooth nevidíte, ale Bluetooth se zobrazí ve Správci zařízení:</span><span class="sxs-lookup"><span data-stu-id="d737f-105">If you don't see the Bluetooth icon, but Bluetooth does appear in Device Manager:</span></span>

1. <span data-ttu-id="d737f-106">Ve Správci zařízení klikněte na **Bluetooth**.</span><span class="sxs-lookup"><span data-stu-id="d737f-106">In Device Manager, click **Bluetooth**.</span></span> <span data-ttu-id="d737f-107">Stiskněte a podržte (nebo klepněte pravým tlačítkem myši) název adaptéru Bluetooth a klepněte na tlačítko **Odinstalovat zařízení**.</span><span class="sxs-lookup"><span data-stu-id="d737f-107">Press and hold (or right-click) the Bluetooth adapter name and click **Uninstall device**.</span></span>

2. <span data-ttu-id="d737f-108">Vypněte zařízení se systémem Windows, počkejte několik sekund a pak ho znovu zapněte.</span><span class="sxs-lookup"><span data-stu-id="d737f-108">Shut down your Windows device, wait a few seconds, and then turn it back on.</span></span> <span data-ttu-id="d737f-109">Systém Windows se pokusí ovladač přeinstalovat.</span><span class="sxs-lookup"><span data-stu-id="d737f-109">Windows will try to reinstall the driver.</span></span>

<span data-ttu-id="d737f-110">Pokud jste nedávno nainstalovali aktualizace Windows 10 nebo upgradovali na Windows 10, možná budete chtít zkontrolovat aktualizace ovladačů:</span><span class="sxs-lookup"><span data-stu-id="d737f-110">If you recently installed Windows 10 updates or upgraded to Windows 10, you may want to check for driver updates:</span></span>

1. <span data-ttu-id="d737f-111">Ve Správci zařízení klikněte na **Bluetooth**a potom klikněte na název adaptéru Bluetooth (který může obsahovat slovo "rádio").</span><span class="sxs-lookup"><span data-stu-id="d737f-111">In Device Manager, click **Bluetooth**, and then click the Bluetooth adapter name (which may include the word "radio").</span></span>

2. <span data-ttu-id="d737f-112">Stiskněte a podržte (nebo klepněte pravým tlačítkem myši) adaptér Bluetooth a potom klepněte na tlačítko Aktualizovat automatické vyhledávání **ovladačů** > **pro aktualizovaný software ovladače**.</span><span class="sxs-lookup"><span data-stu-id="d737f-112">Press and hold (or right-click) the Bluetooth adapter, and then click **Update driver** > **Search automatically for updated driver software**.</span></span> <span data-ttu-id="d737f-113">Postupujte podle pokynů a potom klepněte na tlačítko **Zavřít**.</span><span class="sxs-lookup"><span data-stu-id="d737f-113">Follow the steps, then click **Close**.</span></span>

      - <span data-ttu-id="d737f-114">Pokud systém Windows nemůže najít nový ovladač Bluetooth, navštivte web výrobce počítače a stáhněte si odtud nejnovější ovladač Bluetooth.</span><span class="sxs-lookup"><span data-stu-id="d737f-114">If Windows can't find a new Bluetooth driver, visit the PC manufacturer's website and download the latest Bluetooth driver from there.</span></span>

    - <span data-ttu-id="d737f-115">Po stažení klepněte na tlačítko **Aktualizovat ovladač** > **Procházet můj počítač pro software** > ovladače**Vyhledejte** umístění, kde jsou uloženy soubory ovladače > **OK** > **Next**, a podle pokynů k instalaci.</span><span class="sxs-lookup"><span data-stu-id="d737f-115">After you download it, click **Update driver** > **Browse my computer for driver software** > **Browse** for the location where the driver files are stored > **OK** > **Next**, and follow the steps to install.</span></span>

3. <span data-ttu-id="d737f-116">Po instalaci aktualizovaného ovladače restartujte počítač a zkontrolujte, zda se jedná o problém s připojením.</span><span class="sxs-lookup"><span data-stu-id="d737f-116">After installing the updated driver, restart the machine, and then check whether that fixes the connection issue.</span></span>

<span data-ttu-id="d737f-117">Další podrobnosti o řešení problémů s Bluetooth naleznete v celém článku [Oprava problémů s Bluetooth v systému Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span><span class="sxs-lookup"><span data-stu-id="d737f-117">For more details of how to troubleshoot Bluetooth problems, please see the full article, [Fix Bluetooth problems in Windows 10](https://support.microsoft.com/help/14169/windows-10-fix-bluetooth-problems).</span></span>
