---
title: Identifikace aktivity pravidla složky Doručená pošta z protokolů auditování
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1368
ms.assetid: ''
ms.openlocfilehash: 9339d9c58056f568dc994b75bffe39f2c8bbdd34
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909122"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a>Identifikace aktivity pravidla složky Doručená pošta z protokolů auditování

Pomocí auditování protokolu vyhledávání v & zabezpečení centra kompatibility zobrazit události pravidla složky Doručená pošta (vytváření, úprava a odstranění pravidla složky Doručená pošta).

1. Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)

2. Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** .

4. V rámci **Činnosti poštovní schránky serveru Exchange**, ověřte pole **aktivity** je nastavena na **New-InboxRule vytvořit/upravit/povolit/zakázat pravidla složky Doručená pošta**.

5. Klepněte na tlačítko **Hledat**.

V seznamu výsledků vyberte záznam auditu. V plovoucí panel Podrobnosti klepněte na tlačítko **Další informace**. Informace o nastavení pravidel složky Doručená pošta se zobrazí v poli **Parametry** .

Další informace naleznete v tématu [určení, pokud uživatelem vytvořené pravidlo pro doručenou poštu](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)
