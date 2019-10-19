---
title: Omezení služby SharePoint Online na klasický režim
ms.author: pebaum
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: 18d263593d99f24c3020336ae601df14dbbf5411
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36752061"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="9a82f-102">Omezení služby SharePoint Online na klasický režim</span><span class="sxs-lookup"><span data-stu-id="9a82f-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="9a82f-103">Některé organizace stále vyžadují klasický režim.</span><span class="sxs-lookup"><span data-stu-id="9a82f-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="9a82f-104">Přestože není plánováno odstranění klasického režimu na úrovni zrnité úrovně, není již možné omezit celou organizaci (nájemce) na klasický režim pro seznamy a knihovny.</span><span class="sxs-lookup"><span data-stu-id="9a82f-104">While there are no plans to remove classic mode at a granular level, it is no longer possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="9a82f-105">Správce bude mít následující možnosti správy jednotlivých seznamů a knihoven v klasickém režimu pomocí granulovaných přepínačů opt-out, které poskytujeme na následujících úrovních:</span><span class="sxs-lookup"><span data-stu-id="9a82f-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="9a82f-106">kolekce webů</span><span class="sxs-lookup"><span data-stu-id="9a82f-106">site collection</span></span>
- <span data-ttu-id="9a82f-107">Stránky</span><span class="sxs-lookup"><span data-stu-id="9a82f-107">site</span></span>
- <span data-ttu-id="9a82f-108">Seznamu</span><span class="sxs-lookup"><span data-stu-id="9a82f-108">list</span></span>
- <span data-ttu-id="9a82f-109">Knihovny</span><span class="sxs-lookup"><span data-stu-id="9a82f-109">library</span></span>

<span data-ttu-id="9a82f-110">Kromě toho seznamy, které používají určité funkce a vlastní nastavení, které nejsou podporovány moderními, budou stále automaticky přepnány do klasického režimu.</span><span class="sxs-lookup"><span data-stu-id="9a82f-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="9a82f-111">Počínaje 1. dubna 2019 se proces, který zakáže nájemci, nevolí z moderního seznamu a knihovny začnou a pokračují do 31. května 2019.</span><span class="sxs-lookup"><span data-stu-id="9a82f-111">Beginning April 1, 2019, the process to disable the tenant level opt out of modern list and libraries will start and continue through May 31, 2019.</span></span>  <span data-ttu-id="9a82f-112">Seznamy a knihovny, které jsou v klasickém režimu v důsledku opt-out klienta, budou automaticky přesunuty na moderní.</span><span class="sxs-lookup"><span data-stu-id="9a82f-112">The lists and libraries that are in classic mode as a result of tenant opt-out will automatically be shifted to modern.</span></span>

<span data-ttu-id="9a82f-113">Pokud požadujete klasický režim, Prohlédněte si [zde](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) Další informace a instrukce PNP PowerShell, které popisují možnosti a nástroje [, které můžete](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) použít dnes k použití klasického režimu.</span><span class="sxs-lookup"><span data-stu-id="9a82f-113">If you require classic mode please see more information [here](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) and PnP Powershell instruction [here](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) that describes options and tools you can use today to use the classic mode experience.</span></span>
