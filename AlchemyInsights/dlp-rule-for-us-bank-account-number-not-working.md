---
title: DLP pravidlo pro nás číslo bankovního účtu nefunguje
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: 6eae9146d33f5fc307085dbf931d57bdbb28b82e
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28282167"
---
Došlo k potížím s **Dat ztráta prevence (DLP)** nefunguje pro obsah při použití typu DLP citlivých informací v O365 obsahující **Číslo bankovního účtu v USA** ? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro co zásady DLP hledá Pokud je vyhodnocena. 
  
Například **Číslo bankovního účtu USA** zásad nakonfigurován s konfidenční úrovni 85 % následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit: 
  
- **[Formát:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** číslice 8-17 
    
- **[Vzorek:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 po sobě jdoucích číslic. 
    
- **[Kontrolní součet:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, neexistuje žádný kontrolní součet 
    
- **[Definice:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Zásady DLP je 75 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků: 
    
  - Obsah, který odpovídá vzoru nalezne regulární výraz Regex_usa_bank_account_number
    
  - Klíčové slovo z Keyword_usa_Bank_Account nebyla nalezena.
    
    Například následující ukázka by znamenala pro politiku **USA číslo bankovního účtu** : běžný účet 78344011 
    
Další informace o co je požadováno pro **USA číslo bankovního účtu** zjistit pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací vyhledejte číslo bankovního účtu v USA](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)
  
Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

