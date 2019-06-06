---
title: Správa vyhledávání slovníků v Online služby SharePoint
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c2960093bb1cfb649c26528c9f671e6d720ff237
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/05/2019
ms.locfileid: "34736046"
---
# <a name="search-in-sharepoint-online"></a><span data-ttu-id="2f261-102">Vyhledávání ve službě SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="2f261-102">Search in SharePoint Online</span></span>

<span data-ttu-id="2f261-103">Obsah musí být procházeny a přidán do indexu hledání uživatelům najít, co se při hledání v SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2f261-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="2f261-104">Automatické procházení obsahu na základě plánu předem definované procházení (plán procházení nelze změnit).</span><span class="sxs-lookup"><span data-stu-id="2f261-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="2f261-105">Prohledávací modul zvedne obsah, který se změnil od posledního procházení a aktualizuje index.</span><span class="sxs-lookup"><span data-stu-id="2f261-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="2f261-106">K zajištění procházení obsahu a aktualizace indexu, postupujte následujícím způsobem.</span><span class="sxs-lookup"><span data-stu-id="2f261-106">To ensure content is crawled and the index is updated, follow the steps below.</span></span>

<span data-ttu-id="2f261-107">Zkontrolujte, zda obsah lze nalézt tím, že lze prohledávat obsah webu.</span><span class="sxs-lookup"><span data-stu-id="2f261-107">Make sure content can be found by making site content searchable.</span></span> <span data-ttu-id="2f261-108">Další informace naleznete v tématu [Povolení obsahu na webu, abyste je mohli prohledávat](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="2f261-108">For more info, see [Enable content on a site to be searchable](https://docs.microsoft.com/en-us/sharepoint/make-site-content-searchable).</span></span>

<span data-ttu-id="2f261-109">Při změně spravovanou vlastnost, nebo při změně mapování procházených a spravovány dříve, než se změny projeví ve vyhledávacím indexu musí být znovu procházené vlastnosti webu.</span><span class="sxs-lookup"><span data-stu-id="2f261-109">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

<span data-ttu-id="2f261-110">Protože jsou změny provedeny ve schématu hledání a ne na skutečný web, bude prohledávací modul automaticky Reindexace webu.</span><span class="sxs-lookup"><span data-stu-id="2f261-110">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

<span data-ttu-id="2f261-111">Další informace naleznete v tématu [ručně vyžádání prohledávání a indexování znovu serveru, knihovny nebo seznamu](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="2f261-111">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/en-us/sharepoint/crawl-site-conten).</span></span>

 <span data-ttu-id="2f261-112">Počkejte alespoň 24 hodin po ručně procházení a úplné Přeindexovat zobrazíte, pokud přetrvávají problém.</span><span class="sxs-lookup"><span data-stu-id="2f261-112">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

<span data-ttu-id="2f261-113">Pokud více než 24 hodin uplynulo od zahájeno procházení a úplné Přeindexovat, prosím přihlásit případ podpory.</span><span class="sxs-lookup"><span data-stu-id="2f261-113">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="2f261-114">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="2f261-114">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="2f261-115">Uveďte, prosím, nás alespoň 24 hodin, řešení.</span><span class="sxs-lookup"><span data-stu-id="2f261-115">Please give us at least 24 hours to complete a solution.</span></span>

<span data-ttu-id="2f261-116">**Důležité**: Pokud webu, dokument (knihovna) nebo seznamu byla odstraněna a stále zobrazuje ve výsledcích vyhledávání, by měla uživatelům zobrazí chybě 404 Soubor nebyl nalezen při pokusu o přístup.</span><span class="sxs-lookup"><span data-stu-id="2f261-116">**Important**: If a site, document (library), or a list was deleted and still shows in the search results, users should receive an Error 404 File Not Found when trying to access.</span></span> <span data-ttu-id="2f261-117">Tento problém je zaznamenán jako případ podpory pro další výzkum.</span><span class="sxs-lookup"><span data-stu-id="2f261-117">This issue should be logged as a support case for further investigation.</span></span> 



