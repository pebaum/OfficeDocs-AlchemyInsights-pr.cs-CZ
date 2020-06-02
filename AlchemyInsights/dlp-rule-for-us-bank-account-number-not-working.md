---
title: Pravidlo ochrany před únikem let do provozu pro číslo bankovního účtu v USA nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: b032a7c80e8b387114aeda95c4f6af7e57225517
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507327"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a>Problémy s dlp s čísly bankovních účtů v USA

**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).

**Problémy s dlp s čísly bankovních účtů v USA**

Máte problémy s **ochranou před únikem informací (DLP)** nefunguje pro obsah obsahující **číslo bankovního účtu v USA** při použití DLP citlivé informace typu v O365? Pokud ano, ujistěte se, že obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací při jeho vyhodnocení hledají.
  
Například pro zásady **číslo bankovního účtu v USA** nakonfigurované s úrovní spolehlivosti 85 %, následující jsou vyhodnoceny a musí být zjištěny pro pravidlo spustit:
  
- **[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 číslic

- **[Vzor:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 po sobě jdoucích číslic.

- **[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ne, žádný kontrolní součet neexistuje.

- **[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** Zásady ochrany před únikem informací si 75 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:

  - Regulární výraz Regex_usa_bank_account_number vyhledá obsah, který odpovídá vzoru.

  - Bylo nalezeno klíčové slovo z Keyword_usa_Bank_Account.

    Pro zásadu **Číslo bankovního účtu v USA** by se například aktivovala následující ukázka: Běžný účet 78344011

Další informace o tom, co je potřeba k zjištění **čísla bankovního účtu v USA** pro váš obsah, naleznete v následující části v tomto článku: Co typy [citlivých informací hledají číslo bankovního účtu v USA](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)
  
Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)
  