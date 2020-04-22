---
title: 1491-search-not-returning-očekávané-výsledky
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1491"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: d0707af19b0299f7257a10a20ab38f47860308fb
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43709220"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="e18cd-102">Hledání obsahu nevrací očekávané výsledky</span><span class="sxs-lookup"><span data-stu-id="e18cd-102">Content Search not returning expected results</span></span>

<span data-ttu-id="e18cd-103">Při spuštění vyhledávání obsahu z Centra pro zabezpečení & Microsoft 365 se mohou zobrazit neočekávané výsledky hledání.</span><span class="sxs-lookup"><span data-stu-id="e18cd-103">When running Content Searches from the Microsoft 365 security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="e18cd-104">Zvažte následující věci, které mohou ovlivnit výsledky vyhledávání:</span><span class="sxs-lookup"><span data-stu-id="e18cd-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="e18cd-105">**Umístění obsahu a podmínky vyhledávání**: Ujistěte se, že jste vybrali správná umístění obsahu a podmínky vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="e18cd-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="e18cd-106">Pokud jste spustili rozsáhlé vyhledávání (s mnoha umístěními), zvažte jeho rozdělení do více vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="e18cd-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="e18cd-107">**Částečně indexované položky**: [Částečně indexované položky](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) z poštovních schránek jsou zahrnuty ve výsledcích vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="e18cd-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="e18cd-108">Částečně indexované položky z webů na SharePointu a OneDrivu však nejsou zahrnuty do odhadu vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="e18cd-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="e18cd-109">**Selhání vyhledávání**: Při prohledávání velkého počtu poštovních schránek (více než 100 000 poštovních schránek) se mohou nazvat chyby při hledání, například CS008-009 a CS012-002).</span><span class="sxs-lookup"><span data-stu-id="e18cd-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="e18cd-110">V takovém případě opakujte hledání pouze pro umístění obsahu se nezdařilo.</span><span class="sxs-lookup"><span data-stu-id="e18cd-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="e18cd-111">Další informace naleznete v [tomto článku.](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search)</span><span class="sxs-lookup"><span data-stu-id="e18cd-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>
