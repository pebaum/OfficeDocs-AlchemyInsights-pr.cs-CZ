---
title: 'stejný jako název souboru je nejlepší [pravidlo #-popis]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e248c2ee3cbb9a86f21c1f36be10c893df76ff52
ms.sourcegitcommit: 3070905131e6d8449981231a3551c0bb4ca38ae6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/14/2019
ms.locfileid: "30634497"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Nejsou k dispozici požadované Alchymie hlavičku H1, H2 je.
Doporučené postupy a pokyny pro vytváření Alchymie:

1. **Nelze vnořit Alchymie poznatky ve složkách**- tím dojde k porušení struktury adres url. Díváme se do tohoto řešení.
1. Soubory ve složce **AlchemyInsights** by měl mít ID pravidla a pravidlo název [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net) v názvu souboru.
    1. ex. ***976-How-to-enable-litigation-Hold***
1. Použití metadat v horní části tohoto souboru jako šablony. Nic jiného je vyžadován.
1. Na [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net), přejděte dolů k části **název odběratele přehled:** a použití, které jako počáteční bod pro váš nadpis H1 insight. 
    > [!NOTE]
    > Alchymie poznatky musí mít pouze jeden H1 nahoře nebo bude přerušení výroby. H2s není vykreslit tak použití **tučného písma** nebo jiné konvence označuje samostatné oddíly.
1. Dále v textu pomocí návrhu materiálu v sekci zákazník poznatky stránky Alchymie pravidlo výplně
    1. Seznamy s odrážkami jsou jemné
    1. Číslované seznamy příliš
    1. **Tučné písmo** a *kurzívu* jsou a-ok
    1. Odkazy by měly být vždy buď **"odkazy na web" / externí** nebo **hluboké odkazy na prvky uživatelského rozhraní**, nikoli vnitřní propojení.

A to je ve skutečnosti již trochu příliš dlouhý. Nejlepší je asi 400 znaků---

Jakmile váš obsah je připraven, živé větve ho vytáhněte. Potom přejděte na [portál pro partnery Alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url. Ujistěte se, Insight přezkoumána a publikovány říká "Ano" a potom klepněte na tlačítko Aktualizovat pravidlo. **(To bude vypadat v nové verzi portálu - uvolnění brzy prettier.)** 
 ![pole url](media/for-content-team.PNG)

