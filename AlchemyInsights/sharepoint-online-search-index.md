---
title: Vyhledávání ve službě SharePoint Online
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: fc49978fbd2c07381dae83061b1a1868cd1df0d0
ms.sourcegitcommit: 327a2c77afc2ff3d67d3aaaea1a92068a3c4bb1f
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/06/2019
ms.locfileid: "36059245"
---
# <a name="search-in-sharepoint-online"></a><span data-ttu-id="bbdc6-102">Vyhledávání ve službě SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="bbdc6-102">Search in SharePoint Online</span></span>

<span data-ttu-id="bbdc6-103">Obsah musí být procházeny a přidán do indexu hledání uživatelům najít, co se při hledání v SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="bbdc6-104">Automatické procházení obsahu na základě plánu předem definované procházení (plán procházení nelze změnit).</span><span class="sxs-lookup"><span data-stu-id="bbdc6-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="bbdc6-105">Prohledávací modul zvedne obsah, který se změnil od posledního procházení a aktualizuje index.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="bbdc6-106">K zajištění procházení obsahu a aktualizace indexu, pamatujte si následující:</span><span class="sxs-lookup"><span data-stu-id="bbdc6-106">To ensure content is crawled and the index is updated, note the following:</span></span>

- <span data-ttu-id="bbdc6-107">Zkontrolujte, zda obsah lze nalézt tím, [že lze prohledávat obsah webu](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="bbdc6-107">Make sure content can be found by [making site content searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span>

- <span data-ttu-id="bbdc6-108">Při změně spravovanou vlastnost, nebo při změně mapování procházených a spravovány dříve, než se změny projeví ve vyhledávacím indexu musí být znovu procházené vlastnosti webu.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-108">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

    <span data-ttu-id="bbdc6-109">Protože jsou změny provedeny ve schématu hledání a ne na skutečný web, bude prohledávací modul automaticky Reindexace webu.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-109">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

    <span data-ttu-id="bbdc6-110">Další informace naleznete v tématu [ručně vyžádání prohledávání a indexování znovu serveru, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="bbdc6-110">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span></span>

- <span data-ttu-id="bbdc6-111">Počkejte alespoň 24 hodin po ručně procházení a úplné Přeindexovat zobrazíte, pokud přetrvávají problém.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-111">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

    <span data-ttu-id="bbdc6-112">Pokud více než 24 hodin uplynulo od zahájeno procházení a úplné Přeindexovat, prosím přihlásit případ podpory.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-112">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="bbdc6-113">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-113">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="bbdc6-114">Uveďte, prosím, nás alespoň 24 hodin, řešení.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-114">Please give us at least 24 hours to complete a solution.</span></span>

>[! Důležité!]<span data-ttu-id="bbdc6-115">: Pokud webu, dokument (knihovna) nebo seznamu byla odstraněna a stále zobrazuje ve výsledcích vyhledávání, by měly uživatelům zobrazí **Chyba 404 Soubor nebyl nalezen** při pokusu o přístup.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-115">: If a site, document (library), or a list was deleted and still shows in the search results, users should receive an **Error 404 File Not Found** when trying to access it.</span></span> <span data-ttu-id="bbdc6-116">Tento problém je zaznamenán jako případ podpory pro další výzkum.</span><span class="sxs-lookup"><span data-stu-id="bbdc6-116">This issue should be logged as a support case for further investigation.</span></span> 



