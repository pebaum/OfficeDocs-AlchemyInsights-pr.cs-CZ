---
title: Omezení služby SharePoint Online do klasického režimu
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: c51e48fe5694f964aef74c2973f774b44415ebb8
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32422168"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="b9c43-102">Omezení služby SharePoint Online do klasického režimu</span><span class="sxs-lookup"><span data-stu-id="b9c43-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="b9c43-103">Některé organizace vyžadují stále klasický režim zkušenosti.</span><span class="sxs-lookup"><span data-stu-id="b9c43-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="b9c43-104">Pokud nejsou žádné plány k odebrání klasického režimu na nejnižší úrovni, počínaje dne 1,2019, již bude možné omezit celou organizaci (nájemce) do klasického režimu pro seznamy a knihovny.</span><span class="sxs-lookup"><span data-stu-id="b9c43-104">While there are no plans to remove classic mode at a granular level, starting April 1,2019, it will no longer be possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="b9c43-105">Správce bude mít následující možnosti spravovat jednotlivé seznamy a knihovny v klasickém režimu granulovaných přepínače opt-out, které poskytujeme na následujících úrovních:</span><span class="sxs-lookup"><span data-stu-id="b9c43-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="b9c43-106">kolekce webů</span><span class="sxs-lookup"><span data-stu-id="b9c43-106">site collection</span></span>
- <span data-ttu-id="b9c43-107">webu</span><span class="sxs-lookup"><span data-stu-id="b9c43-107">site</span></span>
- <span data-ttu-id="b9c43-108">seznam</span><span class="sxs-lookup"><span data-stu-id="b9c43-108">list</span></span>
- <span data-ttu-id="b9c43-109">Knihovna</span><span class="sxs-lookup"><span data-stu-id="b9c43-109">library</span></span>

<span data-ttu-id="b9c43-110">Dále se seznamy, které používají určité funkce a vlastní nastavení, které nejsou podporovány moderní se stále automaticky přepne do klasického režimu.</span><span class="sxs-lookup"><span data-stu-id="b9c43-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="b9c43-111">Po 1. duben seznamy a knihovny, které jsou v klasickém režimu v důsledku odhlášení klienta budou automaticky spravovány na úrovni webu a na úroveň seznamu.</span><span class="sxs-lookup"><span data-stu-id="b9c43-111">After April 1, lists and libraries that are in classic mode as a result of tenant opt-out will automatically be managed at the site level and list level.</span></span>

<span data-ttu-id="b9c43-112">Pokud požadujete klasického režimu naleznete zde další informace a PnP Powershell instrukce zde popisuje nástroje a možnosti můžete použít dnes Příprava odebrání nájemce úrovně odhlásit dne 1.</span><span class="sxs-lookup"><span data-stu-id="b9c43-112">If you require classic mode please see more information here and PnP Powershell instruction here that describes options and tools you can use today to prepare for the removal of the tenant level opt-out on April 1.</span></span>
