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
ms.openlocfilehash: e0119762d2a34bd2b0da827faf55c832e29d8a2b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539022"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Určení adresy IP a klient z protokolů auditování

Adresu IP, která odpovídá aktivity služeb Office 365, uživatel nebo správce se zobrazí záznamy auditu. Informace o klientovi je také zaznamenána. Zde jsou kroky k identifikaci těchto informací

1. Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/).

2. Přejít na **vyhledávání** > **auditování protokolu vyhledávací** stránku.

   Pokud vás zajímají konkrétní aktivity, vyberte ji ze seznamu **aktivit** . Pokud ne, budou vráceny všechny aktivity pro vybraného uživatele (výchozí nastavení).

   **Poznámka**: některé činnosti nemusí být k dispozici v nabídce **činností** ; však ty položky auditu bude vrácena, pokud je **Zobrazit výsledky pro všechny činnosti** (výchozí nastavení).

3. Zadejte uživatelské jméno do pole **Uživatelé** a vyberte příslušné období aktivity klepněte na tlačítko **Hledat**.

Ve výsledcích se zobrazí adresu IP pro tuto činnost v podokně výsledků. Vyberte záznam auditu zobrazíte podrobné informace vždy **Podrobnosti** (například klienta, uživatel, který provedl akci, atd.).

Další informace naleznete v tématu [vyhledání adresy IP počítače pro přístup k ohrožení zabezpečení účtu](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).
