---
title: stejný jako název souboru je nejlepší
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e2dcca1295e37007593b34c2d818ad1d1133e4a1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676526"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Povinné alchymie Záhlaví H1, H2 nefungují.
Osvědčené postupy a pokyny pro vytváření alchymie:

1. **Nevnořujte Alchemy Insights do složek**- to zlomí strukturu url. Hledáme, jak to napravit.
1. Soubory ve složce **AlchemyInsights** by měly mít názvy souborů s nižšími písmeny s pomlčkami pro mezery ex. ***jak povolit soudní spory***.
    1. Do pole ms.custom zahrňte ID pravidla nebo id bloku z [portálu Partnera alchymie.](https://alchemyportal.azurewebsites.net) Ex. ***ms.custom: 100021***
1. Zbytek metadat v horní části tohoto souboru použijte jako šablonu.
1. Na [portálu Alchemy Partner](https://alchemyportal.azurewebsites.net)přejděte dolů do části **Název přehledu zákazníků:** a použijte ji jako výchozí bod pro váš titul H1 pro přehled. 
    > [!NOTE]
    > Alchymie Insights musí mít pouze jeden H1 na vrcholu, nebo se zlomí ve výrobě. H2s nevykreslují tak použít **tučné** nebo jiné konvence znamenat samostatné oddíly.
1. Dále vyplňte základní text pomocí konceptového materiálu v části Přehledy zákazníků na stránce Pravidlo alchymie.
    1. Seznamy s odrážkami jsou v pořádku
    1. Také číslované seznamy
    1. **Tučné** a *kurzíva* jsou-ok
    1. Odkazy by měly být vždy buď **"odkazy na web"/ externí** NEBO **hluboké odkazy na prvky uživatelského rozhraní**, nikoli interní odkazy.
    1. Obrázky nejsou oficiálně podporovány v tomto okamžiku, ale je to na plánu.

A to je opravdu už trochu příliš dlouho. Osvědčeným postupem je asi 400 znaků ---------------------------------

Jakmile je obsah připraven, přetáhněte jej do živé větve. Potom přejděte na [portál Partnera alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url. 