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
ms.custom: 1491
ms.assetid: ''
ms.openlocfilehash: 517d9b75fc3aef09c0c2d5870aa695cc0ab10f06
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32383828"
---
# <a name="content-search-not-returning-expected-results"></a>Obsahu hledání nelze vracet očekávané výsledky

Při spuštění hledání obsahu z & zabezpečení Office 365 centra kompatibility, můžete obdržet neočekávané výsledky. Vezměte v úvahu následující věci, které mohou ovlivnit výsledky hledání:

- **Umístění obsahu a podmínek vyhledávání**: Přesvědčte se, zda jste zvolili správné umístění obsahu a podmínek vyhledávání. Pokud jste spustili velké hledání (s mnoha míst), zvažte možnost rozdělení do více hledání.

- **Částečně indexované položky**: [částečně indexované položky](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) z poštovní schránky jsou zahrnuty ve výsledcích hledání odhadované. Částečně indexované položky z webů služby SharePoint a OneDrive nejsou však zahrnuty do odhadu hledání.

- **Hledat chyby**: při hledání velký počet poštovních schránek (více než 100 000 poštovních schránek), může k hledání chyb s kódy chyb, například CS008 009 a CS012-002). V takovém případě opakujte vyhledávání pouze selhání umístění obsahu. V části Další informace [tohoto článku](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) .
