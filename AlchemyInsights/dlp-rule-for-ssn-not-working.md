---
title: Pravidlo dlp pro nefunguje SSN
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 0b83a858975ffe1bb70f16a7452a13d57dff5340
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932514"
---
# <a name="dlp-issues-with-social-security-numbers"></a>DLP problémy s čísly sociálního zabezpečení

**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí. Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování. Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.

Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin. Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech. Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.

**Problémy s dip s ssns**

Máte problémy s **funkcí Zabránění ztrátám dat (DLP),** která nefunguje pro obsah obsahující **číslo sociálního zabezpečení (SSN)** při použití typu citlivých informací v Office 365? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co hledá zásady ochrany před únikem informací. 
  
Například pro zásady SSN nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být rozpoznány, aby se pravidlo aktivovala:
  
- **[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 číslic, které mohou být ve formátu nebo neformátovaném vzoru

- **[Vzor:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Čtyři funkce hledají ssn ve čtyřech různých vzorech:

  - Func_ssn najde SSN s před2011 silné formátování, které jsou formátovány s pomlčkami nebo mezery (ddd-ddddnebo ddd ddd dddd)

  - Func_unformatted_ssn najde ssn s před2011 silné formátování, které jsou neformátované jako devět po sobě jdoucích číslic (ddddddddd).

  - Func_randomized_formatted_ssn najde ssn po roce 2011, které jsou formátovány pomlčkami nebo mezerami (ddd-dddd NEBO ddd dddd)

  - Func_randomized_unformatted_ssn vyhledá ssn po roce 2011, které nejsou formátovány jako devět po sobě jdoucích číslic (dddddddddd).

- **[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Ne, není žádný kontrolní součet.

- **[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Zásady ochrany před únikem informací jsou z 85 % přesvědčeny, že tento typ citlivých informací zjistil, pokud v blízkosti 300 znaků:

  - [Funkce Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) vyhledá obsah, který odpovídá vzoru.

  - Bylo nalezeno klíčové slovo z [Keyword_ssn.](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) Příklady klíčových slov zahrnují: *Sociální zabezpečení, Sociální zabezpečení #, Soc Sec, SSN* . Například následující ukázka by aktivační událost pro zásady DLP SSN: **SSN: 489-36-8350**
  
Další informace o tom, co je nutné pro ssn, které mají být detekovány pro váš obsah, naleznete v následující části tohoto článku: [Co typy citlivých informací hledat SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)
  
Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  