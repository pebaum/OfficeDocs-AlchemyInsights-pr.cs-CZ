---
title: Opravte chyby 0x8004de40 v OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 2256fb66cb7a4e2adcff9fda16a80c87e2997f0c
ms.sourcegitcommit: 8f6a1be929b275faa295ba8aeeae17898a47c3b0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/21/2019
ms.locfileid: "35133970"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="a45cb-102">Opravte chyby 0x8004de40 v OneDrive</span><span class="sxs-lookup"><span data-stu-id="a45cb-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="a45cb-103">Pokud se zobrazí chybová 0x8004de40 s OneDrive:</span><span class="sxs-lookup"><span data-stu-id="a45cb-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="a45cb-104">Restartujte ohrožený počítač během připojení k vaší doméně adresáře aktivovat.</span><span class="sxs-lookup"><span data-stu-id="a45cb-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="a45cb-105">Pokud restartování počítače neodstraní problém, odebrat a znovu připojit zařízení z Azure AD.</span><span class="sxs-lookup"><span data-stu-id="a45cb-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="a45cb-106">**Poznámka**: při provádění těchto kroků byste měli být v podnikové síti.</span><span class="sxs-lookup"><span data-stu-id="a45cb-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="a45cb-107">Není provedení těchto kroků, pokud nejste schopni se připojit k vaší podnikové infrastruktury (např. při cestování).</span><span class="sxs-lookup"><span data-stu-id="a45cb-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="a45cb-108">Otevřete příkazový řádek se zvýšenými oprávněními.</span><span class="sxs-lookup"><span data-stu-id="a45cb-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="a45cb-109">Chcete-li otevřít okno příkazového řádku se zvýšenými oprávněními, klepněte na tlačítko - **Start**, klepněte pravým tlačítkem myši **Příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.</span><span class="sxs-lookup"><span data-stu-id="a45cb-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="a45cb-110">Zadejte *dsregcmd /leave* a stiskněte klávesu **Enter**.</span><span class="sxs-lookup"><span data-stu-id="a45cb-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="a45cb-111">Po dokončení zadejte *dsregcmd /join* a stiskněte klávesu **Enter**.</span><span class="sxs-lookup"><span data-stu-id="a45cb-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="a45cb-112">Po dokončení zavřete okno příkazového řádku.</span><span class="sxs-lookup"><span data-stu-id="a45cb-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="a45cb-113">Restartujte počítač a přihlásit do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a45cb-113">Reboot the computer, and log into OneDrive.</span></span>