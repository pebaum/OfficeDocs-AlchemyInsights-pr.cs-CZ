---
title: Identifikace aktivity pravidel doručené pošty v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: f946510539b3d28f2ceeec1546cbffce8bd352fd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716417"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a>Identifikace aktivity pravidel doručené pošty v protokolech auditu

Pomocí hledání protokolu auditu v Centru dodržování předpisů microsoft 365 Security & Compliance Center můžete zobrazit události pravidel doručené pošty (vytváření, úpravy a odstranění pravidel doručené pošty).

1. Přihlaste se k [Centru dodržování předpisů pro zabezpečení & microsoft 365](https://protection.office.com/).

2. Přejděte na stránku**hledání protokolu auditování** **vyhledávání.** > 

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum.**

4. V části **Aktivity poštovní schránky serveru Exchange**ověřte, zda je pole **Aktivity** nastaveno na **pravidlo vytvoření/úpravy/povolit/zakázání pole Vytvoření/změna/povolit/zakázání doručené pošty**.

5. Klepněte na **tlačítko Hledat**.

Ve výsledcích vyberte záznam auditu. V informačním rámečku podrobnosti klikněte na **Další informace**. Informace o nastavení pravidla doručené pošty se zobrazí v poli **Parametry.**

Další informace naleznete v [tématu Určení, zda uživatel vytvořil pravidlo doručené pošty](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)
