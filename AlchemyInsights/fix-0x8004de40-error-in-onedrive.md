---
title: Oprava chyby 0x8004de40 na OneDrivu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 5da4271f242597b195ef61d553fd4a2ffb313025
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716021"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="e25b5-102">Oprava chyby 0x8004de40 na OneDrivu</span><span class="sxs-lookup"><span data-stu-id="e25b5-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="e25b5-103">Pokud se na OneDrivu zobrazí chyba 0x8004de40:</span><span class="sxs-lookup"><span data-stu-id="e25b5-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="e25b5-104">Restartujte postižený počítač při připojení k doméně Acitve Directory.</span><span class="sxs-lookup"><span data-stu-id="e25b5-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="e25b5-105">Pokud restartování problém nevyřeší, odpojte se a znovu se připojte k zařízení z Azure AD.</span><span class="sxs-lookup"><span data-stu-id="e25b5-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="e25b5-106">**Poznámka:** Při provádění těchto kroků byste měli být v podnikové síti.</span><span class="sxs-lookup"><span data-stu-id="e25b5-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="e25b5-107">Tyto kroky neprovádějte, pokud se nemůžete připojit k podnikové infrastruktuře (například na cestách).</span><span class="sxs-lookup"><span data-stu-id="e25b5-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="e25b5-108">Otevřete příkazový řádek se zvýšenými oprávněními.</span><span class="sxs-lookup"><span data-stu-id="e25b5-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="e25b5-109">Chcete-li otevřít příkazový řádek se zvýšenými oprávněními, klepněte na tlačítko - **Spustit**, klepněte pravým tlačítkem myši na **příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.</span><span class="sxs-lookup"><span data-stu-id="e25b5-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="e25b5-110">Zadejte *dsregcmd /leave* a stiskněte **enter**.</span><span class="sxs-lookup"><span data-stu-id="e25b5-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="e25b5-111">Po dokončení zadejte *dsregcmd /join* a stiskněte **Enter**.</span><span class="sxs-lookup"><span data-stu-id="e25b5-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="e25b5-112">Po dokončení zavřete příkazový řádek.</span><span class="sxs-lookup"><span data-stu-id="e25b5-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="e25b5-113">Restartujte počítač a přihlaste se k OneDrivu.</span><span class="sxs-lookup"><span data-stu-id="e25b5-113">Reboot the computer, and log into OneDrive.</span></span>