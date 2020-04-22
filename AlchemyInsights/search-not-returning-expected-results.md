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
# <a name="content-search-not-returning-expected-results"></a>Hledání obsahu nevrací očekávané výsledky

Při spuštění vyhledávání obsahu z Centra pro zabezpečení & Microsoft 365 se mohou zobrazit neočekávané výsledky hledání. Zvažte následující věci, které mohou ovlivnit výsledky vyhledávání:

- **Umístění obsahu a podmínky vyhledávání**: Ujistěte se, že jste vybrali správná umístění obsahu a podmínky vyhledávání. Pokud jste spustili rozsáhlé vyhledávání (s mnoha umístěními), zvažte jeho rozdělení do více vyhledávání.

- **Částečně indexované položky**: [Částečně indexované položky](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) z poštovních schránek jsou zahrnuty ve výsledcích vyhledávání. Částečně indexované položky z webů na SharePointu a OneDrivu však nejsou zahrnuty do odhadu vyhledávání.

- **Selhání vyhledávání**: Při prohledávání velkého počtu poštovních schránek (více než 100 000 poštovních schránek) se mohou nazvat chyby při hledání, například CS008-009 a CS012-002). V takovém případě opakujte hledání pouze pro umístění obsahu se nezdařilo. Další informace naleznete v [tomto článku.](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search)
