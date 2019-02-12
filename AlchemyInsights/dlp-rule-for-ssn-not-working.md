---
title: DLP pravidlo pro SSN nefunguje
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: d2d21fb5546d36990d69b76e3ceb72ce2edf3d80
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29933473"
---
Došlo k potížím s **Dat ztráta prevence (DLP)** nefunguje pro obsah obsahující **Číslo sociálního pojištění (ČSP)** při použití citlivých informací typu ve službách Office 365? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro vyhledávání zásady DLP. 
  
Například SSN zásad nakonfigurován s konfidenční úrovni 85 % takto vyhodnoceny a musí být rozpoznány pro pravidlo spustit:
  
- **[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 číslic, které mohou být ve vzorku formátovaný nebo neformátovaný 
    
- **[Vzorek:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Ve čtyři různé vzory hledat SSNs čtyři funkce: 
    
  - Func_ssn najde SSNs s pre-2011 silný formátování, které jsou formátovány s čárkami nebo mezerami (ddd-dd dddd nebo ddd dd dddd)
    
  - Func_unformatted_ssn najde SSNs s pre-2011 silný formátování neformátovaný jako devět po sobě jdoucích číslic (ddddddddd)
    
  - Func_randomized_formatted_ssn najde SSNs post 2011, které jsou formátovány s čárkami nebo mezerami (ddd-dd dddd nebo ddd dd dddd)
    
  - Func_randomized_unformatted_ssn najde SSNs post 2011, které neformátovaný jako devět po sobě jdoucích číslic (ddddddddd)
    
- **[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Ne, neexistuje žádný kontrolní součet 
    
- **[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Zásady DLP je 85 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků: 
    
  - [Funkce Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) vyhledá obsah, který odpovídá vzoru. 
    
  - Klíčové slovo z [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) nebyla nalezena. Obsahuje příklady klíčových slov: *sociální zabezpečení, sociální zabezpečení #, s Soc, SSN* . Například následující ukázka vyvolalo DLP SSN zásady: **SSN: 489-36-8350**
    
Další informace o co je požadováno pro SSNs zjistit pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací hledejte SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)
  
Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  

