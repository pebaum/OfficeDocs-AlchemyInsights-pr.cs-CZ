---
title: Identifikace aktivity pravidla složky Doručená pošta z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 1201a625948743cacfaa58410abeb4108ed2eb56
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539152"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a>Identifikace aktivity pravidla složky Doručená pošta z protokolů auditování

Můžete hledat protokolu auditu v zabezpečení Office 365 & centra kompatibility zobrazení událostí pravidla složky Doručená pošta (vytváření, úprava a odstranění pravidla složky Doručená pošta).

1. Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/).

2. Přejít na **vyhledávání** > **auditování protokolu vyhledávací** stránku.

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** .

4. V rámci **Činnosti poštovní schránky serveru Exchange**, ověřte pole **aktivity** je nastavena na **New-InboxRule vytvořit/upravit/povolit/zakázat pravidla složky Doručená pošta**.

5. Klepněte na tlačítko **Hledat**.

V seznamu výsledků vyberte záznam auditu. V plovoucí panel Podrobnosti klepněte na tlačítko **Další informace**. Informace o nastavení pravidel složky Doručená pošta se zobrazí v poli **Parametry** .

Další informace naleznete v tématu [určení, pokud uživatelem vytvořené pravidlo pro doručenou poštu](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)
