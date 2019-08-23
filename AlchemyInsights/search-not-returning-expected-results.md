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
ms.custom:
- "1491"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: 094da9d75013aae56ca219b7ae03e85736ce5ee0
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36551408"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="e526e-102">Obsahu hledání nelze vracet očekávané výsledky</span><span class="sxs-lookup"><span data-stu-id="e526e-102">Content Search not returning expected results</span></span>

<span data-ttu-id="e526e-103">Při spuštění hledání obsahu z & zabezpečení Office 365 centra kompatibility, můžete obdržet neočekávané výsledky.</span><span class="sxs-lookup"><span data-stu-id="e526e-103">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="e526e-104">Vezměte v úvahu následující věci, které mohou ovlivnit výsledky hledání:</span><span class="sxs-lookup"><span data-stu-id="e526e-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="e526e-105">**Umístění obsahu a podmínek vyhledávání**: Přesvědčte se, zda jste zvolili správné umístění obsahu a podmínek vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="e526e-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="e526e-106">Pokud jste spustili velké hledání (s mnoha míst), zvažte možnost rozdělení do více hledání.</span><span class="sxs-lookup"><span data-stu-id="e526e-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="e526e-107">**Částečně indexované položky**: [částečně indexované položky](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) z poštovní schránky jsou zahrnuty ve výsledcích hledání odhadované.</span><span class="sxs-lookup"><span data-stu-id="e526e-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="e526e-108">Částečně indexované položky z webů služby SharePoint a OneDrive nejsou však zahrnuty do odhadu hledání.</span><span class="sxs-lookup"><span data-stu-id="e526e-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="e526e-109">**Hledat chyby**: při hledání velký počet poštovních schránek (více než 100 000 poštovních schránek), může k hledání chyb s kódy chyb, například CS008 009 a CS012-002).</span><span class="sxs-lookup"><span data-stu-id="e526e-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="e526e-110">V takovém případě opakujte vyhledávání pouze selhání umístění obsahu.</span><span class="sxs-lookup"><span data-stu-id="e526e-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="e526e-111">V části Další informace [tohoto článku](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) .</span><span class="sxs-lookup"><span data-stu-id="e526e-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
