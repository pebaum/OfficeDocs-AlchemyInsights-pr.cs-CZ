---
title: stejný jako název souboru je nejlepší
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 31a578800468e9f3a69fff4f6e2e1945943c779c
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "35800038"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>Požadovaný Alchemy záhlaví H1, H2's nefunguje.
Doporučené postupy a pokyny pro tvorbu Alchemy:

1. **Nevnořit do složek Alchemy náhledy**-tím dojde k přerušení struktury adres URL. Chceme to opravit.
1. Soubory ve složce **Alchemypostřehy** by měly být vybaveny malými názvy souborů s pomlčkami pro mezery ex. ***Postup-povolení-soudní***řízení.
    1. Do vlastního pole MS. zahrňte ID pravidla nebo ID bloku z [portálu Alchemy partner](https://alchemyportal.azurewebsites.net) . Ex. ***MS. Custom: 100021***
1. Použijte zbývající metadata v horní části tohoto souboru jako šablonu.
1. V [portálu Alchemy partner](https://alchemyportal.azurewebsites.net)přejděte k části Přehled modulu pro **zákazníky:** a použijte jej jako výchozí bod pro váš titul H1. 
    > [!NOTE]
    > Alchemy postřehy musí mít na vrcholu pouze jednu H1 nebo se rozlomí ve výrobě. H2s se nevykreslí tak, že použijete **tučné** nebo jiné konvence k označení samostatných sekcí.
1. Dále vyplňte základní text pomocí konceptu materiálu v části pohledy zákazníka na stránce Alchemy Rule.
    1. Seznamy s odrážkami jsou v pořádku
    1. Číslované seznamy
    1. **Tučné písmo** a *kurzíva* jsou-OK
    1. Odkazy by měly být vždy buď **"odkazy na webové"/externí** nebo **hluboké-odkazy na prvky uživatelského rozhraní**, nikoli na interní vazby.
    1. Obrázky nejsou v tuto chvíli oficiálně podporovány, ale jsou na cestovní mapě.

A tohle už je opravdu trochu moc dlouho. Osvědčený postup je asi 400 znaků---------------------------------

Jakmile je obsah připraven, stáhněte jej do živé větve. Potom přejděte na [portál Alchemy partner](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole adresy URL. 