---
title: Správa schématu vyhledávání ve službě SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: 9836cf139e97fc556995a8f0ad38c51c5c2392ac
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40042956"
---
# <a name="manage-search-schema-in-sharepoint-online"></a><span data-ttu-id="1af7c-102">Správa schématu vyhledávání ve službě SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="1af7c-102">Manage search schema in SharePoint Online</span></span>

<span data-ttu-id="1af7c-103">Schéma vyhledávání řídí, co mohou uživatelé vyhledávat, jak je mohou uživatelé prohledávat a jak můžete výsledky prezentovat na webech vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="1af7c-103">The search schema controls what users can search for, how users can search it, and how you can present the results on your search websites.</span></span> 

<span data-ttu-id="1af7c-104">Další informace naleznete [v tématu Správa schématu vyhledávání na webu služby SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema) :</span><span class="sxs-lookup"><span data-stu-id="1af7c-104">See [Manage the Search Schema in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-search-schema) to learn how to:</span></span> 
- <span data-ttu-id="1af7c-105">Změňte schéma hledání.</span><span class="sxs-lookup"><span data-stu-id="1af7c-105">Change the search schema.</span></span>
- <span data-ttu-id="1af7c-106">Vytvořte spravované vlastnosti.</span><span class="sxs-lookup"><span data-stu-id="1af7c-106">Create managed properties.</span></span>
- <span data-ttu-id="1af7c-107">Mapování procházených vlastností procházené mapy na spravované vlastnosti.</span><span class="sxs-lookup"><span data-stu-id="1af7c-107">Map crawled map crawled properties to managed properties.</span></span>

<span data-ttu-id="1af7c-108">Pro správu schématu hledání je třeba si uvědomit následující skutečnosti:</span><span class="sxs-lookup"><span data-stu-id="1af7c-108">Note the following in regards to managing your Search Schema:</span></span>

- <span data-ttu-id="1af7c-109">Pokud se zobrazí upozornění oznamující **, že aplikace je** při změně schématu pozastavena, jedná se pouze o dočasnou údržbu služby.</span><span class="sxs-lookup"><span data-stu-id="1af7c-109">If you receive a warning stating **the application is paused** when making a schema change, this is only temporary as there is service maintenance occurring.</span></span> 

    <span data-ttu-id="1af7c-110">Pokud uplynulo více než 24 hodin a stále se setkáte s upozorněním, zadejte do protokolu případ podpory.</span><span class="sxs-lookup"><span data-stu-id="1af7c-110">If more than 24 hours have passed and you still experience the warning, please log a support case.</span></span>
- <span data-ttu-id="1af7c-111">Pokud změníte spravované vlastnosti nebo přidáte nové, projeví se změny až po opětovném procházení obsahu.</span><span class="sxs-lookup"><span data-stu-id="1af7c-111">When you change managed properties or add new ones, the changes take effect only after the content has been re-crawled.</span></span> <span data-ttu-id="1af7c-112">Ve službě SharePoint Online se procházení automaticky odehrává na základě definovaného plánu procházení.</span><span class="sxs-lookup"><span data-stu-id="1af7c-112">In SharePoint Online, crawling happens automatically based on the defined crawl schedule.</span></span>
- <span data-ttu-id="1af7c-113">Chcete-li se ujistit, že jsou změny procházeny, můžete [požadovat opakované indexování seznamu nebo knihovny](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list) .</span><span class="sxs-lookup"><span data-stu-id="1af7c-113">To make sure that your changes are crawled, you can specifically [request a re-indexing of the list or library](https://docs.microsoft.com/sharepoint/manage-search-schema#request-re-indexing-of-a-document-library-or-list)</span></span> 

<span data-ttu-id="1af7c-114">Úplný přehled schématu vyhledávání naleznete v tématu [Úvod do schématu hledání](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/)</span><span class="sxs-lookup"><span data-stu-id="1af7c-114">For a complete overview of the Search Schema, see [Introducing Search Schema](https://blogs.technet.microsoft.com/tothesharepoint/2012/11/25/introducing-search-schema-for-sharepoint-2013/)</span></span> 


