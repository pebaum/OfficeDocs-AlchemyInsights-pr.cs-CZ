---
title: Identifikace externího předávání e-mailů v poštovních schránkách v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 156fd0044cdc42230ace0a5db16f49af572bb6fa
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716453"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Určení konfigurace externího předávání e-mailů v poštovních schránkách

Když uživatel Microsoft 365 konfiguruje externí předávání e-mailů v poštovní schránce, aktivita je auditována jako součást rutiny **Set-Mailbox.** Aktivitu můžete zobrazit pomocí vyhledávání protokolu auditu v Centru dodržování předpisů & zabezpečení.

1. Přihlaste se k [Centru dodržování předpisů pro zabezpečení & microsoft 365](https://protection.office.com/).

2. Přejděte na stránku**hledání protokolu auditování** **vyhledávání.** > 

3. Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum.** Není nutné zadávat uživatelské jméno. Ověřte, zda je pole **Aktivity** nastaveno na **Zobrazit výsledky pro všechny aktivity**.

4. Klepněte na **tlačítko Hledat**.

Ve výsledcích klikněte na **Filtrovat výsledky** a do pole filtru aktivit zadejte nastavit **poštovní schránku.** Ve výsledcích vyberte záznam auditu. V informačním rámečku **Podrobnosti** klikněte na **Další informace**. Musíte se podívat na podrobnosti každého záznamu auditu, abyste zjistili, zda aktivita souvisí s předáváním e-mailů.

- **ObjectId**: Hodnota aliasu poštovní schránky, která byla změněna.

- **Parametry**: _ForwardingSmtpAddress_ označuje cílovou e-mailovou adresu.

- **UserId**: Uživatel, který nakonfiguroval předávání e-mailů v poštovní schránce v poli **ObjectId.**

Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).
