---
title: Pravidlo DLP pro číslo kreditní karty nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 40a4a1668039b70455e09ee662359c05235645e8
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977191"
---
# <a name="dlp-issues-with-credit-card-numbers"></a>Problémy s DLP s čísly kreditních karet

**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)

**Problémy s DLP s čísly kreditních karet**

Máte problémy s **prevencí před ztrátou dat (DLP),** která nefunguje pro obsah obsahující **číslo kreditní karty** při použití typu citlivých informací DLP v O365? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro aktivaci zásady ochrany před únikem informací při vyhodnocení. Například pro **zásady platební karty** nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo:
  
- **[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 číslic, které mohou být formátovány nebo neformátované (ddddddddddddddddddd) a musí projít Luhntestem.

- **[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Velmi složitý a robustní vzor, který detekuje karty od všech hlavních značek po celém světě, včetně Visa, MasterCard, Discover Card, JCB, American Express, dárkové karty a karty.

- **[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Ano, kontrolní součet Luhn

- **[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zásady ochrany před únikem informací jsou z 85 % přesvědčeny, že tento typ citlivých informací zjistil, pokud v blízkosti 300 znaků:

  - Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.

  - Platí jedna z následujících skutečností:

  - Bylo nalezeno klíčové slovo z Keyword_cc_verification.

  - Bylo nalezeno klíčové slovo z Keyword_cc_name

  - Funkce Func_expiration_date vyhledá datum ve správném formátu data.

  - Kontrolní součet prochází

    Například následující ukázka by aktivační událost pro zásady číslo platební karty DLP:

  - Vízum: 4485 3647 3952 7352
  
  - Platnost: 2/2009

Další informace o tom, co je požadováno pro **zjištění čísla platební karty** pro váš obsah, naleznete v následující části tohoto článku: Co typy citlivých informací hledají číslo platební [karty#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  