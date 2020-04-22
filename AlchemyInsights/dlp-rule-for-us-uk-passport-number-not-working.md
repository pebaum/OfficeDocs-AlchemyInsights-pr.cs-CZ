---
title: Pravidlo DLP pro číslo pasu USA/UK nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 9d9615eccd1e245bf4ca32742bfc64321dd7a8cf
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714979"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problémy s DLP - ČÍSLA pasů v USA/Velké Británii

**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).

**Problémy s dlp s čísly pasů usa / UK**

Máte problémy s **prevencí před únikem dat (DLP),** která nefunguje pro obsah obsahující **číslo pasu USA/UK** při použití typu citlivých informací dlp v O365? Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací hledá při vyhodnocení.
  
Například pro zásady **číslo pasu USA/Velké Británie** nakonfigurované s úrovní spolehlivosti 75 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo.
  
- **[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Devět číslic

- **[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devět po sobě jdoucích číslic

- **[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, není žádný kontrolní součet.

- **[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Zásady ochrany před únikem informací si je 75 % jisti, že byl zjištěn tento typ citlivých informací, pokud v blízkosti 300 znaků:

  - Funkce Func_usa_uk_passport vyhledá obsah, který odpovídá vzoru.

  - Bylo nalezeno klíčové slovo z Keyword_passport.

    Například následující ukázka by aktivační událost pro **usa / Spojené království číslo pasu** politiky: Us Passport číslo 123456789

Další informace o tom, co je požadováno pro zjištění čísla pasu USA/UK pro váš obsah, naleznete v následující části tohoto článku: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)
  
Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
  