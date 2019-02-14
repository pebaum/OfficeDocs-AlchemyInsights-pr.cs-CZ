---
title: 1491-Search-not-returning-Expected-Results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964827"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="225f8-102">Obsahu hledání nelze vracet očekávané výsledky</span><span class="sxs-lookup"><span data-stu-id="225f8-102">Content Search not returning expected results</span></span>

<span data-ttu-id="225f8-p101">Při spuštění hledání obsahu z & zabezpečení Office 365 centra kompatibility, můžete obdržet neočekávané výsledky. Vezměte v úvahu následující věci, které mohou ovlivnit výsledky hledání:</span><span class="sxs-lookup"><span data-stu-id="225f8-p101">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results. Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="225f8-p102">**Umístění obsahu a podmínek vyhledávání**: Přesvědčte se, zda jste zvolili správné umístění obsahu a podmínek vyhledávání. Pokud jste spustili velké hledání (s mnoha míst), zvažte možnost rozdělení do více hledání.</span><span class="sxs-lookup"><span data-stu-id="225f8-p102">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions. If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="225f8-p103">**Částečně indexované položky**: [částečně indexované položky](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) z poštovní schránky jsou zahrnuty ve výsledcích hledání odhadované. Částečně indexované položky z webů služby SharePoint a OneDrive nejsou však zahrnuty do odhadu hledání.</span><span class="sxs-lookup"><span data-stu-id="225f8-p103">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results. However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="225f8-p104">**Hledat chyby**: při hledání velký počet poštovních schránek (více než 100 000 poštovních schránek), může k hledání chyb s kódy chyb, například CS008 009 a CS012-002). V takovém případě opakujte vyhledávání pouze selhání umístění obsahu. V části Další informace [tohoto článku](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) .</span><span class="sxs-lookup"><span data-stu-id="225f8-p104">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002). In this case, retry the search only for the failed content locations. See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
