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
ms.openlocfilehash: d436184bdc0e283db217ea734fb2c8e05f85b4e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36525052"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="6539b-102">Opravte chyby 0x8004de40 v OneDrive</span><span class="sxs-lookup"><span data-stu-id="6539b-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="6539b-103">Pokud se zobrazí chybová 0x8004de40 s OneDrive:</span><span class="sxs-lookup"><span data-stu-id="6539b-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="6539b-104">Restartujte ohrožený počítač během připojení k vaší doméně adresáře aktivovat.</span><span class="sxs-lookup"><span data-stu-id="6539b-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="6539b-105">Pokud restartování počítače neodstraní problém, odebrat a znovu připojit zařízení z Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6539b-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="6539b-106">**Poznámka**: při provádění těchto kroků byste měli být v podnikové síti.</span><span class="sxs-lookup"><span data-stu-id="6539b-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="6539b-107">Není provedení těchto kroků, pokud nejste schopni se připojit k vaší podnikové infrastruktury (např. při cestování).</span><span class="sxs-lookup"><span data-stu-id="6539b-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="6539b-108">Otevřete příkazový řádek se zvýšenými oprávněními.</span><span class="sxs-lookup"><span data-stu-id="6539b-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="6539b-109">Chcete-li otevřít okno příkazového řádku se zvýšenými oprávněními, klepněte na tlačítko - **Start**, klepněte pravým tlačítkem myši **Příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.</span><span class="sxs-lookup"><span data-stu-id="6539b-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="6539b-110">Zadejte *dsregcmd /leave* a stiskněte klávesu **Enter**.</span><span class="sxs-lookup"><span data-stu-id="6539b-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="6539b-111">Po dokončení zadejte *dsregcmd /join* a stiskněte klávesu **Enter**.</span><span class="sxs-lookup"><span data-stu-id="6539b-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="6539b-112">Po dokončení zavřete okno příkazového řádku.</span><span class="sxs-lookup"><span data-stu-id="6539b-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="6539b-113">Restartujte počítač a přihlásit do OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6539b-113">Reboot the computer, and log into OneDrive.</span></span>