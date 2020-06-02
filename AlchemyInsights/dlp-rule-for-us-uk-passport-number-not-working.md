---
title: Pravidlo ochrany před únikem letového provozu pro číslo pasu USA/Uk nefunguje
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
ms.openlocfilehash: 3d3b7dc2d9510376bc9eef6ec69b87ad7c681b05
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507291"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a>Problémy s DLP - USA / UK čísla pasu

**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).

**DLP problémy s USA / UK čísla pasu**

Máte problémy s **ochranou před ztrátou dat (DLP)** nefunguje pro obsah obsahující **usa / UK číslo pasu** při použití DLP citlivé informace typu v O365? Pokud ano, ujistěte se, že obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací při jeho vyhodnocení hledají.
  
Například pro zásady **čísla pasu USA/Spojeného království,** které jsou nakonfigurovány s úrovní spolehlivosti 75 %, jsou vyhodnoceny následující zásady, které musí být detekovány, aby pravidlo spustilo
  
- **[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** Devět číslic

- **[Vzor:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** Devět po sobě jdoucích číslic

- **[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ne, žádný kontrolní součet neexistuje.

- **[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-77)** Zásady ochrany před únikem informací si 75 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:

  - Funkce Func_usa_uk_passport vyhledá obsah, který odpovídá vzoru.

  - Bylo nalezeno klíčové slovo z Keyword_passport.

    Například následující vzorek by se aktivuje pro **usa / Uk pas číslo** politiky: US Passport číslo 123456789

Další informace o tom, co je potřeba k zjištění pasového čísla USA/Velké Británie pro váš obsah, naleznete v následující části v tomto článku: [Co vyhledáte u pasového čísla USA/Velké Británie](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us--uk-passport-number)
  
Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  