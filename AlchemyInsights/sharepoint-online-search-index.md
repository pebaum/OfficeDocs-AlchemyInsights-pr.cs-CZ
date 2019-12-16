---
title: Hledat ve službě SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c4ff98f0cf928834c803542340b32da15a40d583
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40044036"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a><span data-ttu-id="fc3dc-102">Procházení a indexování obsahu ve službě SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="fc3dc-102">Content crawling and indexing in SharePoint Online</span></span>

<span data-ttu-id="fc3dc-103">Obsah musí být procházen a přidán do vyhledávacího indexu, aby uživatelé našli hledané informace ve službě SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-103">Content must be crawled and added to the search index for users to find what they're searching for in SharePoint Online.</span></span> <span data-ttu-id="fc3dc-104">Obsah je automaticky procházen na základě předem definovaného plánu procházení (plán procházení nelze změnit).</span><span class="sxs-lookup"><span data-stu-id="fc3dc-104">Content is automatically crawled based on a pre-defined crawl schedule (the crawl schedule cannot be changed).</span></span> <span data-ttu-id="fc3dc-105">Prohledávací modul zachytí obsah, který se od posledního procházení změnil, a aktualizuje rejstřík.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-105">The crawler picks up content that has changed since the last crawl and updates the index.</span></span> <span data-ttu-id="fc3dc-106">Chcete-li zajistit procházení obsahu a aktualizaci indexu, uvědomte si následující skutečnosti:</span><span class="sxs-lookup"><span data-stu-id="fc3dc-106">To ensure content is crawled and the index is updated, note the following:</span></span>

- <span data-ttu-id="fc3dc-107">Ujistěte se, že obsah webu lze [vyhledat pomocí webového obsahu](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="fc3dc-107">Make sure content can be found by [making site content searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span>

- <span data-ttu-id="fc3dc-108">Pokud jste změnili spravovanou vlastnost nebo jste změnili mapování procházených a spravovaných vlastností, musí být web znovu procházen dříve, než se změny projeví ve vyhledávacím indexu.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-108">When you have changed a managed property, or when you have changed the mapping of crawled and managed properties, the site must be re-crawled before your changes will be reflected in the search index.</span></span> 

    <span data-ttu-id="fc3dc-109">Vzhledem k tomu, že změny jsou provedeny ve schématu hledání a nikoli na skutečném webu, prohledávací modul automaticky znovu Indexujte Web.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-109">Because your changes are made in the search schema, and not to the actual site, the crawler will not automatically re-index the site.</span></span> 

    <span data-ttu-id="fc3dc-110">Další informace naleznete v tématu [Ruční procházení a přeindexování webu, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span><span class="sxs-lookup"><span data-stu-id="fc3dc-110">For more info, see [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-conten).</span></span>

- <span data-ttu-id="fc3dc-111">Vyčkejte nejméně 24 hodin po ručním vyžádání procházení a úplného obnovení indexu a zjistěte, zda stále dochází k potížím.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-111">Wait at least 24 hours after manually requesting a crawl and full re-index to see if you're still experiencing an issue.</span></span> 

    <span data-ttu-id="fc3dc-112">Pokud uplynulo více než 24 hodin od zahájení procházení a úplného obnovení indexu, zadejte do protokolu případ podpory.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-112">If more than 24 hours have passed since you initiated the crawl and full re-index, please log a support case.</span></span> <span data-ttu-id="fc3dc-113">V mnoha případech už pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-113">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="fc3dc-114">K dokončení řešení nám prosím dejte alespoň 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-114">Please give us at least 24 hours to complete a solution.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="fc3dc-115">Pokud byl web, dokument (knihovna) nebo seznam odstraněn a ve výsledcích hledání je stále zobrazen, měli by uživatelé při pokusu o přístup obdržet **chybu 404 soubor nebyl nalezen** .</span><span class="sxs-lookup"><span data-stu-id="fc3dc-115">If a site, document (library), or a list was deleted and still shows in the search results, users should receive an **Error 404 File Not Found** when trying to access it.</span></span> <span data-ttu-id="fc3dc-116">Tento problém by měl být zaznamenán jako případ podpory pro další zkoumání.</span><span class="sxs-lookup"><span data-stu-id="fc3dc-116">This issue should be logged as a support case for further investigation.</span></span> 



