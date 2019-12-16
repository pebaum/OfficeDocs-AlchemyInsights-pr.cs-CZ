---
title: Hledat ve službě SharePoint Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: fe00f4c0-44d5-49d4-9db0-a62698bcd1d1
ms.openlocfilehash: c4ff98f0cf928834c803542340b32da15a40d583
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40044036"
---
# <a name="content-crawling-and-indexing-in-sharepoint-online"></a>Procházení a indexování obsahu ve službě SharePoint Online

Obsah musí být procházen a přidán do vyhledávacího indexu, aby uživatelé našli hledané informace ve službě SharePoint Online. Obsah je automaticky procházen na základě předem definovaného plánu procházení (plán procházení nelze změnit). Prohledávací modul zachytí obsah, který se od posledního procházení změnil, a aktualizuje rejstřík. Chcete-li zajistit procházení obsahu a aktualizaci indexu, uvědomte si následující skutečnosti:

- Ujistěte se, že obsah webu lze [vyhledat pomocí webového obsahu](https://docs.microsoft.com/sharepoint/make-site-content-searchable).

- Pokud jste změnili spravovanou vlastnost nebo jste změnili mapování procházených a spravovaných vlastností, musí být web znovu procházen dříve, než se změny projeví ve vyhledávacím indexu. 

    Vzhledem k tomu, že změny jsou provedeny ve schématu hledání a nikoli na skutečném webu, prohledávací modul automaticky znovu Indexujte Web. 

    Další informace naleznete v tématu [Ruční procházení a přeindexování webu, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-conten).

- Vyčkejte nejméně 24 hodin po ručním vyžádání procházení a úplného obnovení indexu a zjistěte, zda stále dochází k potížím. 

    Pokud uplynulo více než 24 hodin od zahájení procházení a úplného obnovení indexu, zadejte do protokolu případ podpory. V mnoha případech už pracujeme na řešení. K dokončení řešení nám prosím dejte alespoň 24 hodin.

> [!IMPORTANT]
> Pokud byl web, dokument (knihovna) nebo seznam odstraněn a ve výsledcích hledání je stále zobrazen, měli by uživatelé při pokusu o přístup obdržet **chybu 404 soubor nebyl nalezen** . Tento problém by měl být zaznamenán jako případ podpory pro další zkoumání. 



