---
title: Pravidlo ochrany před únikem let do provozu pro ssn nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 35859bce89ef1ae9b6a9e706fc316b0ee6cd27d1
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507363"
---
# <a name="dlp-issues-with-social-security-numbers"></a>Problémy s DLP s čísly sociálního zabezpečení

**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).

**Problémy s dlp se sítěmi SSN**

Máte problémy s **ochranou před ztrátou dat (DLP)** nefunguje pro obsah obsahující **číslo sociálního zabezpečení (SSN)** při použití typu citlivých informací v Microsoft 365? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací hledá. 
  
Například pro zásady SSN nakonfigurované s úrovní spolehlivosti 85 %, následující jsou vyhodnoceny a musí být zjištěny pro pravidlo aktivovat:
  
- **[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-80)** 9 číslic, které mohou být ve formátu nebo neformátovaný vzor

- **[Vzor:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Čtyři funkce hledají SSNs ve čtyřech různých vzorech:

  - Func_ssn najde SSNs se silným formátováním před 2011, které jsou formátovány pomlčkami nebo mezerami (ddd-ddddd NEBO ddd ddd dddddd)

  - Func_unformatted_ssn najde SSNs s před-2011 silné formátování, které jsou neformátované jako devět po sobě jdoucích číslic (dddddddddddddd)

  - Func_randomized_formatted_ssn vyhledá po roce 2011 sítě SSN formátované pomlčkami nebo mezerami (ddd-dddd NEBO ddd ddd ddd dddddd)

  - Func_randomized_unformatted_ssn vyhledá po roce 2011 názvy SSN, které nejsou formátovány jako devět po sobě jdoucích číslic (ddddddddddddd).

- **[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-79)** Ne, žádný kontrolní součet neexistuje.

- **[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-80)** Zásady ochrany před únikem informací si 85 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:

  - [Funkce Func_ssn](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-80) vyhledá obsah, který odpovídá vzoru.

  - Bylo nalezeno klíčové slovo z [Keyword_ssn.](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#keyword_ssn) Příklady klíčových slov zahrnují: *Sociální zabezpečení, Sociální zabezpečení#, Soc Sec , SSN* . Například následující ukázka by aktivovat pro zásady DLP SSN: **SSN: 489-36-8350**
  
Další informace o tom, co je potřeba pro detekci sítí SSN pro váš obsah, naleznete v následující části v tomto článku: [Co typy citlivých informací hledat SSN](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-social-security-number-ssn)
  
Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  