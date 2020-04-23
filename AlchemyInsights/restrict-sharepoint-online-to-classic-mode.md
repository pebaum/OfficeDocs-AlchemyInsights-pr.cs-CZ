---
title: Omezení SharePointu Online na klasický režim
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: c5ea5d264b62e4c349623bd431776207b38da470
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742462"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="284b1-102">Omezení SharePointu Online na klasický režim</span><span class="sxs-lookup"><span data-stu-id="284b1-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="284b1-103">Některé organizace stále vyžadují klasické prostředí.</span><span class="sxs-lookup"><span data-stu-id="284b1-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="284b1-104">I když neexistují žádné plány na odebrání klasického režimu na podrobné úrovni, již není možné omezit celou organizaci (tenanta) na klasický režim pro seznamy a knihovny.</span><span class="sxs-lookup"><span data-stu-id="284b1-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="284b1-105">Správce bude mít následující možnosti pro správu jednotlivých seznamů a knihoven v klasickém režimu pomocí podrobných přepínačů pro odhlášení, které poskytujeme na následujících úrovních:</span><span class="sxs-lookup"><span data-stu-id="284b1-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="284b1-106">kolekce webů</span><span class="sxs-lookup"><span data-stu-id="284b1-106">site collection</span></span>
- <span data-ttu-id="284b1-107">Stránky</span><span class="sxs-lookup"><span data-stu-id="284b1-107">site</span></span>
- <span data-ttu-id="284b1-108">Seznamu</span><span class="sxs-lookup"><span data-stu-id="284b1-108">list</span></span>
- <span data-ttu-id="284b1-109">Knihovny</span><span class="sxs-lookup"><span data-stu-id="284b1-109">library</span></span>

<span data-ttu-id="284b1-110">Kromě toho seznamy, které používají určité funkce a vlastní nastavení, které nejsou podporovány moderní bude stále automaticky přepnut do klasického režimu.</span><span class="sxs-lookup"><span data-stu-id="284b1-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="284b1-111">dubna 2019 se proces zakázání úrovně klienta odhlásí z moderního seznamu a knihoven spustí a bude pokračovat až do 31.</span><span class="sxs-lookup"><span data-stu-id="284b1-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="284b1-112">Seznamy a knihovny, které jsou v klasickém režimu v důsledku odhlášení klienta, budou automaticky přesunuty do moderní.</span><span class="sxs-lookup"><span data-stu-id="284b1-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="284b1-113">Pokud požadujete klasický režim, podívejte se na více informací [zde](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) a PnP Powershell instrukce [zde,](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) který popisuje možnosti a nástroje, které můžete použít dnes používat klasický režim zkušenosti.</span><span class="sxs-lookup"><span data-stu-id="284b1-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
