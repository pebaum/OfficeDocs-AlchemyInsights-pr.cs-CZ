---
title: Fix 0x8004de40 chyba v OneDrive
ms.author: pebaum
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: aa0e0a63ac1e365a7cdce018626740446040a664
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36755841"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="546aa-102">Fix 0x8004de40 chyba v OneDrive</span><span class="sxs-lookup"><span data-stu-id="546aa-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="546aa-103">Obdržíte-li chybu 0x8004de40 u funkce OneDrive:</span><span class="sxs-lookup"><span data-stu-id="546aa-103">If you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="546aa-104">Restartujte ohrožený počítač, který je připojen k doméně adresáře Acitve.</span><span class="sxs-lookup"><span data-stu-id="546aa-104">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="546aa-105">Pokud počítač nebude problém napravovat, připojte se a znovu připojte k zařízení Azure AD.</span><span class="sxs-lookup"><span data-stu-id="546aa-105">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="546aa-106">**Poznámka**: při provádění těchto kroků byste měli být v podnikové síti.</span><span class="sxs-lookup"><span data-stu-id="546aa-106">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="546aa-107">Neprovádějte tyto kroky, pokud se nemůžete připojit k podnikové infrastruktuře (například při cestování).</span><span class="sxs-lookup"><span data-stu-id="546aa-107">Don't perform these steps when you aren't able to connect to your corporate infrastructure (for example, while traveling).</span></span> 

- <span data-ttu-id="546aa-108">Otevřete příkazový řádek se zvýšenými oprávněními.</span><span class="sxs-lookup"><span data-stu-id="546aa-108">Open an elevated command prompt.</span></span> 
- <span data-ttu-id="546aa-109">Chcete-li otevřít příkazový řádek se zvýšenými oprávněními, klepněte na tlačítko **Start**, klepněte pravým tlačítkem myši na položku **příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.</span><span class="sxs-lookup"><span data-stu-id="546aa-109">To open an elevated command prompt, click - **Start**, right-click **Command Prompt**, and then click **Run as administrator**.</span></span>
- <span data-ttu-id="546aa-110">Zadejte příkaz *dsregcmd/odejdi* a stiskněte klávesu **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="546aa-110">Type *dsregcmd /leave* and press **Enter**.</span></span>
- <span data-ttu-id="546aa-111">Po dokončení zadejte příkaz *dsregcmd/JOIN* a stiskněte klávesu **ENTER**.</span><span class="sxs-lookup"><span data-stu-id="546aa-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>
- <span data-ttu-id="546aa-112">Po dokončení ukončete příkazový řádek.</span><span class="sxs-lookup"><span data-stu-id="546aa-112">When complete, close the command prompt.</span></span>
- <span data-ttu-id="546aa-113">Restartujte počítač a přihlaste se k OneDrive.</span><span class="sxs-lookup"><span data-stu-id="546aa-113">Reboot the computer, and log into OneDrive.</span></span>