---
title: Identifikovat externí e-mailu předávání poštovních schránek z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 43b6a26bc05892e71d41c4b47522785245cb4851
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35383090"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Identifikovat při konfiguraci externí e-mailu předávání poštovních schránek

Když uživatel konfiguruje externí e-mailu předávání poštovní schránky, je jako část rutiny **Set-Mailbox** auditované činnosti. Můžete zobrazit aktivitu pomocí vyhledávání protokolu auditování zabezpečení & centra kompatibility.

1. Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)

2. Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** . Není třeba zadat uživatelské jméno. Ověřte, zda že pole **aktivity** je nastavena na **Zobrazit výsledky pro všechny aktivity**.

4. Klepněte na tlačítko **Hledat**.

Ve výsledcích **Výsledky filtru** klepněte a zadejte **Set-Mailbox** v poli Filtr aktivity. V seznamu výsledků vyberte záznam auditu. V plovoucí panel **Podrobnosti** klepněte na tlačítko **Další informace**. Je nutné podívat se na podrobnosti každý záznam auditu k určení, pokud je aktivita spojena k předávání e-mailu.

- **ObjectId**: Hodnota alias poštovní schránky, který byl upraven.

- **Parametry**: _ForwardingSmtpAddress_ označuje cílovou e-mailovou adresu.

- **ID uživatele**: uživatel nakonfigurovat předávání e-mailu na poštovní schránky v poli **ID objektu** .

Další informace naleznete v tématu [určení, která nastavila e-mail dál pro poštovní schránky](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).
