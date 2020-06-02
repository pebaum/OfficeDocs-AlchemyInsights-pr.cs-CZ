---
title: Pravidlo ochrany před únikem let do provozu pro číslo kreditní karty nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: e2e93bed44749b9017dc6ff919a151d46da7a3fc
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507399"
---
# <a name="dlp-issues-with-credit-card-numbers"></a>Problémy s ochranym před únikem letových průkazů s čísly platebních karet

**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).

**Problémy s ochranym před únikem letových průkazů s čísly platebních karet**

Máte problémy s **ochranou před ztrátou dat (DLP)** nefunguje pro obsah obsahující **číslo kreditní karty** při použití DLP citlivé informace typu v O365? Pokud ano, ujistěte se, že obsah obsahuje potřebné informace pro aktivaci zásad ochrany před únikem informací při jeho vyhodnocení. Například pro **zásady kreditní karty** nakonfigurované s úrovní spolehlivosti 85 %, následující jsou vyhodnoceny a musí být zjištěny pro pravidlo spustit:
  
- **[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-19)** 16 číslic, které mohou být formátovány nebo neformátované (ddddddddddddddddddddddddd) a musí projít Luhn testem.

- **[Vzor:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-19)** Velmi složitý a robustní vzor, který detekuje karty všech hlavních značek po celém světě, včetně Visa, MasterCard, Discover Card, JCB, American Express, dárkové karty a diner karty.

- **[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-19)** Ano, Luhnův kontrolní součet

- **[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-19)** Zásady ochrany před únikem informací si 85 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:

  - Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.

  - Jedna z následujících skutečností je pravdivá:

  - Bylo nalezeno klíčové slovo z Keyword_cc_verification.

  - Bylo nalezeno klíčové slovo z Keyword_cc_name

  - Funkce Func_expiration_date najde datum ve správném formátu data.

  - Kontrolní součet projde

    Následující ukázka by například aktivuje zásady čísla kreditní karty DLP:

  - Vízum: 4485 3647 3952 7352
  
  - Vyprší: 2/2009

Další informace o tom, co je potřeba k zjištění **čísla platební karty** pro váš obsah, naleznete v následující části v tomto článku: Co typy [citlivých informací hledají kreditní kartu #](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#credit-card-number)
  
Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  