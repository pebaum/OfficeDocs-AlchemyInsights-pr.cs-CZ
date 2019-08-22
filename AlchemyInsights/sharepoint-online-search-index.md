---
title: Vyhledávání ve službě SharePoint Online
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: 3c3f6384172b2b4d59db6059618572db11059228
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507624"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a>Procházení obsahu a indexování v Online služby SharePoint

Obsah musí být procházeny a přidán do indexu hledání uživatelům najít, co se při hledání v SharePoint Online. Automatické procházení obsahu na základě plánu předem definované procházení (plán procházení nelze změnit). Prohledávací modul zvedne obsah, který se změnil od posledního procházení a aktualizuje index. K zajištění procházení obsahu a aktualizace indexu, pamatujte si následující:

- Zkontrolujte, zda obsah lze nalézt tím, [že lze prohledávat obsah webu](https://docs.microsoft.com/sharepoint/make-site-content-searchable).

- Při změně spravovanou vlastnost, nebo při změně mapování procházených a spravovány dříve, než se změny projeví ve vyhledávacím indexu musí být znovu procházené vlastnosti webu. 

    Protože jsou změny provedeny ve schématu hledání a ne na skutečný web, bude prohledávací modul automaticky Reindexace webu. 

    Další informace naleznete v tématu [ručně vyžádání prohledávání a indexování znovu serveru, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-conten).

- Počkejte alespoň 24 hodin po ručně procházení a úplné Přeindexovat zobrazíte, pokud přetrvávají problém. 

    Pokud více než 24 hodin uplynulo od zahájeno procházení a úplné Přeindexovat, prosím přihlásit případ podpory. V mnoha případech již pracujeme na řešení. Uveďte, prosím, nás alespoň 24 hodin, řešení.

> [!IMPORTANT]
> Pokud web, byl odstraněn dokument (knihovna) nebo seznam a stále zobrazena ve výsledcích hledání uživatelů mělo by se zobrazit **Chyba 404 Soubor nebyl nalezen** při pokusu o přístup. Tento problém je zaznamenán jako případ podpory pro další výzkum. 



