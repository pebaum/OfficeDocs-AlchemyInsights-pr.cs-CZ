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
# <a name="search-in-sharepoint-online"></a>Vyhledávání ve službě SharePoint Online

Obsah musí být procházeny a přidán do indexu hledání uživatelům najít, co se při hledání v SharePoint Online. Automatické procházení obsahu na základě plánu předem definované procházení (plán procházení nelze změnit). Prohledávací modul zvedne obsah, který se změnil od posledního procházení a aktualizuje index. K zajištění procházení obsahu a aktualizace indexu, pamatujte si následující:

- Zkontrolujte, zda obsah lze nalézt tím, [že lze prohledávat obsah webu](https://docs.microsoft.com/sharepoint/make-site-content-searchable).

- Při změně spravovanou vlastnost, nebo při změně mapování procházených a spravovány dříve, než se změny projeví ve vyhledávacím indexu musí být znovu procházené vlastnosti webu. 

    Protože jsou změny provedeny ve schématu hledání a ne na skutečný web, bude prohledávací modul automaticky Reindexace webu. 

    Další informace naleznete v tématu [ručně vyžádání prohledávání a indexování znovu serveru, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-conten).

- Počkejte alespoň 24 hodin po ručně procházení a úplné Přeindexovat zobrazíte, pokud přetrvávají problém. 

    Pokud více než 24 hodin uplynulo od zahájeno procházení a úplné Přeindexovat, prosím přihlásit případ podpory. V mnoha případech již pracujeme na řešení. Uveďte, prosím, nás alespoň 24 hodin, řešení.

>[! Důležité!]: Pokud webu, dokument (knihovna) nebo seznamu byla odstraněna a stále zobrazuje ve výsledcích vyhledávání, by měly uživatelům zobrazí **Chyba 404 Soubor nebyl nalezen** při pokusu o přístup. Tento problém je zaznamenán jako případ podpory pro další výzkum. 



