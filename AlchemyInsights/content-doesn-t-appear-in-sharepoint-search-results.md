---
title: Obsah se ve výsledcích sharepointového vyhledávání nezobrazuje
ms.author: tlarsen
author: tklarsen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: a21e0047b41390f740f9e13d31cba32b13990151
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705654"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a><span data-ttu-id="f3fde-102">Obsah se ve výsledcích sharepointového vyhledávání nezobrazuje</span><span class="sxs-lookup"><span data-stu-id="f3fde-102">Content doesn't appear in SharePoint search results</span></span>

<span data-ttu-id="f3fde-103">Pokud se očekávaný obsah nezobrazuje ve výsledcích hledání, postupujte podle těchto kroků řešení potíží:</span><span class="sxs-lookup"><span data-stu-id="f3fde-103">Follow these troubleshooting steps when expected content doesn't appear in search results:</span></span>
  
1. <span data-ttu-id="f3fde-104">Zkontrolujte, zda je **web,** který obsahuje očekávaný obsah, nastaven tak, aby se obsah zobrazoval ve výsledcích hledání.</span><span class="sxs-lookup"><span data-stu-id="f3fde-104">Check that the **site** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="f3fde-105">Postupujte podle pokynů v části [Zobrazit obsah na webu ve výsledcích vyhledávání](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="f3fde-105">Follow the steps in [Show content on a site in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span></span>

2. <span data-ttu-id="f3fde-106">Zkontrolujte, zda je **seznam** nebo **knihovna** obsahující očekávaný obsah nastavena tak, aby se obsah zobrazoval ve výsledcích hledání.</span><span class="sxs-lookup"><span data-stu-id="f3fde-106">Check that the **list** or **library** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="f3fde-107">Postupujte podle pokynů v části [Zobrazit obsah ze seznamů nebo knihoven ve výsledcích hledání](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="f3fde-107">Follow the steps in [Show content from lists or libraries in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span></span>

3. <span data-ttu-id="f3fde-108">Ověřte, zda je rozložení stránky, dokumentu nebo vlastní stránky publikováno jako **hlavní verze.**</span><span class="sxs-lookup"><span data-stu-id="f3fde-108">Verify that the page, document, or custom page layout is published as a **Major version.**</span></span> <span data-ttu-id="f3fde-109">Podle kroku 3 ve [Vyhledávání nevracívšechny výsledky v SharePointu Online](https://go.microsoft.com/fwlink/?linkid=874525).</span><span class="sxs-lookup"><span data-stu-id="f3fde-109">Follow step 3 in [Search doesn't return all results in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span></span>

4. <span data-ttu-id="f3fde-110">Ověřte, zda má uživatel **oprávnění** k zobrazení obsahu.</span><span class="sxs-lookup"><span data-stu-id="f3fde-110">Verify that the user has **permissions** to view the content.</span></span> <span data-ttu-id="f3fde-111">Postupujte podle pokynů v [části Principy úrovní oprávnění v SharePointu](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="f3fde-111">Follow the steps in [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
    
5. <span data-ttu-id="f3fde-112">Pokud bylo schéma hledání změněno přidáním nové spravované vlastnosti, úpravou spravované vlastnosti nebo odebráním spravované vlastnosti, bude vyžadovánpožadavek na procházení a přeindexování.</span><span class="sxs-lookup"><span data-stu-id="f3fde-112">If the search schema has been changed by adding a new managed property, by editing a managed property, or by removing a managed property then requesting a crawl and re-index will be required.</span></span> <span data-ttu-id="f3fde-113">**Obsah můžete znovu indexovat** podle kroků uvedených v části [Ruční vyžádání procházení a přeindexování webu, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-content).</span><span class="sxs-lookup"><span data-stu-id="f3fde-113">**Re-index** the content by following the steps in [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-content).</span></span> <span data-ttu-id="f3fde-114">To může chvíli trvat, počkejte 24 hodin, než znovu zkontrolujete výsledky.</span><span class="sxs-lookup"><span data-stu-id="f3fde-114">This might take a while, wait 24 hours before checking the results again.</span></span>

<span data-ttu-id="f3fde-115">Další informace naleznete v [tématu Povolení vyhledávání obsahu na webu](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="f3fde-115">For more information, see [Enable content on a site to be searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span> 
  
