---
title: Pravidlo číslo kreditní karty nefunguje DLP
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: a56f32b54e6cb32fa044d26d08868bac8c368de5
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281211"
---
Došlo k potížím s **Dat ztráta prevence (DLP)** pro obsah obsahující **Číslo kreditní karty** , při použití typu DLP citlivých informací v O365 nefunguje? Pokud ano, přesvědčte se, zda váš obsah obsahuje potřebné informace pro spuštění DLP zásady, pokud je vyhodnocen. Například pro **kreditní karty zásad** nakonfigurován s konfidenční úrovni 85 %, následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit: 
  
- **[Formát:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 číslic, které mohou být upraveny nebo neformátovaný (dddddddddddddddd) a musejí vyhovět zkoušce Luhn. 
    
- **[Vzorek:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Velmi komplexní a robustní vzorek, který rozpozná karty ze všech hlavních značek po celém světě, včetně Visa, Mastercard, Objevování karta, JCB, American Express, dárkové poukazy a karty diner. 
    
- **[Kontrolní součet:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Ano, Luhn kontrolního součtu 
    
- **[Definice:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zásady DLP je 85 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků: 
    
  - Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.
    
  - Je splněna jedna z následujících akcí: 
    
  - Klíčové slovo z Keyword_cc_verification nebyla nalezena.
    
  - Klíčové slovo z Keyword_cc_name je nalezen.
    
  - Funkce Func_expiration_date najde datum ve formátu data vpravo.
    
  - Předá kontrolní součet
    
    Například následující ukázka by znamenala pro DLP zásady číslo platební karty:
    
  - Víza: 4485 3647 3952 7352 
    
  - Platnost vyprší: 2/2009
    
Další informace o co je požadováno pro **Číslo kreditní karty** mají být rozpoznány pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací vyhledejte platební karty #](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)
  
Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

