---
title: 1491-search-not-return-expected-results 1491-search-not-return-expected-results 1491-search-not-return-expected-results 1491
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
ms.openlocfilehash: 57421d459ef03049d6f931db659a5f9b253f5002
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510565"
---
# <a name="content-search-not-returning-expected-results"></a>Hledání obsahu nevrací očekávané výsledky

Při spouštění vyhledávání obsahu z Centra pro zabezpečení zabezpečení Microsoft 365 & může dojít k neočekávaným výsledkům hledání. Zvažte následující věci, které mohou ovlivnit výsledky hledání:

- **Umístění obsahu a podmínky vyhledávání**: Ujistěte se, že jste vybrali správná umístění obsahu a podmínky vyhledávání. Pokud jste spustili velké vyhledávání (s mnoha umístěními), zvažte jeho rozdělení do více hledání.

- **Částečně indexované položky**: [Částečně indexované položky](https://docs.microsoft.com/microsoft-365/compliance/partially-indexed-items-in-content-search) z poštovních schránek jsou zahrnuty do odhadovaných výsledků hledání. Částečně indexované položky z webů na SharePointu a OneDrivu se však do odhadu vyhledávání nezahrnují.

- **Selhání hledání**: Při hledání velkého počtu poštovních schránek (přes 100 000 poštovních schránek) se mohou zobrazit chyby při hledání s kódy chyb, jako jsou CS008-009 a CS012-002). V takovém případě opakujte hledání pouze pro umístění neúspěšného obsahu. Další informace naleznete [v tomto článku.](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search)
