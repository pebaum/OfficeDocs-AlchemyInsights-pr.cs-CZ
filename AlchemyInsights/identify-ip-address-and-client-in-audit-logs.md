---
title: Určení adresy IP a klient z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: a91778c006531371b85116f5c97485d42e6cc5be
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35382946"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Určení adresy IP a klient z protokolů auditování

Adresy IP, která odpovídá činnosti uživatelem nebo správcem, je uveden v protokoly auditu. Informace o klientovi je také zaznamenána. Zde jsou kroky k identifikaci těchto informací

1. Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)

2. Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.

   Pokud vás zajímají konkrétní aktivity, vyberte ji ze seznamu **aktivit** . Pokud ne, budou vráceny všechny aktivity pro vybraného uživatele (výchozí nastavení).

   **Poznámka**: některé činnosti nemusí být k dispozici v nabídce **činností** ; však ty položky auditu bude vrácena, pokud je **Zobrazit výsledky pro všechny činnosti** (výchozí nastavení).

3. Zadejte uživatelské jméno do pole **Uživatelé** a vyberte příslušné období aktivity klepněte na tlačítko **Hledat**.

Ve výsledcích se zobrazí adresu IP pro tuto činnost v podokně výsledků. Vyberte záznam auditu zobrazíte podrobné informace vždy **Podrobnosti** (například klienta, uživatel, který provedl akci, atd.).

Další informace naleznete v tématu [vyhledání adresy IP počítače pro přístup k ohrožení zabezpečení účtu](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).
