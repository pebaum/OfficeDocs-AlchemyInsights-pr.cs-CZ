---
title: Pravidlo číslo kreditní karty nefunguje DLP
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
ms.openlocfilehash: 875afb47175a78c22894720cb0db8222f6f41614
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529948"
---
# <a name="dlp-issues-with-credit-card-numbers"></a>DLP problémy s čísly platebních karet

Došlo k potížím s **Dat ztráta prevence (DLP)** pro obsah obsahující **Číslo kreditní karty** , při použití typu DLP citlivých informací v O365 nefunguje? Pokud ano, přesvědčte se, zda váš obsah obsahuje potřebné informace pro spuštění DLP zásady, pokud je vyhodnocen. Například pro **kreditní karty zásad** nakonfigurován s konfidenční úrovni 85 %, následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit:
  
- **[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 číslic, které mohou být upraveny nebo neformátovaný (dddddddddddddddd) a musejí vyhovět zkoušce Luhn.

- **[Vzorek:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Velmi komplexní a robustní vzorek, který rozpozná karty ze všech hlavních značek po celém světě, včetně Visa, MasterCard, Objevování karta, JCB, American Express, dárkové poukazy a karty diner.

- **[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Ano, Luhn kontrolního součtu

- **[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zásady DLP je 85 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků:

  - Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.

  - Je splněna jedna z následujících akcí:

  - Klíčové slovo z Keyword_cc_verification nebyla nalezena.

  - Klíčové slovo z Keyword_cc_name je nalezen.

  - Funkce Func_expiration_date najde datum ve formátu data vpravo.

  - Předá kontrolní součet

    Například následující ukázka by znamenala pro DLP zásady číslo platební karty:

  - Víza: 4485 3647 3952 7352
  
  - Platnost vyprší: 2/2009

Další informace o co je požadováno pro **Číslo kreditní karty** mají být rozpoznány pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací vyhledejte platební karty #](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  