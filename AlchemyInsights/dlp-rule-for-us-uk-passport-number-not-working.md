---
title: Pravidlo DLP pro číslo pasu USA/UK nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: c63e814059c897531109aa78725e9811b311fb27
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931255"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problémy s DLP - ČÍSLA pasů v USA/Velké Británii

**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí. Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování. Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.

Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin. Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech. Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.

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
  