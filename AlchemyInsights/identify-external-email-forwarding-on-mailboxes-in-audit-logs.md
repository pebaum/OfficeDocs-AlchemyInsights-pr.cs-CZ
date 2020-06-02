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
ms.openlocfilehash: 592eb92e4b0fe0f9da2fa20bb93ffa4fbbb76662
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508945"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a>Zjištění, kdy je na poštovních schránkách nakonfigurováno externí předávání e-mailů

Když uživatel Microsoft 365 nakonfiguruje externí předávání e-mailů v poštovní schránce, aktivita je auditována jako součást rutiny **Set-Mailbox.** Aktivitu můžete zobrazit pomocí vyhledávání v protokolu auditu v Centru dodržování předpisů zabezpečení &.

1. Přihlaste se do [Centra dodržování předpisů zabezpečení microsoftu 365 &](https://protection.office.com/).

2. Přejděte **Search**na  >  stránku**hledání protokolu auditu** hledání.

3. V polích **Počáteční datum** a **Koncové datum** vyberte rozsah dat. Nemusíte zadávat uživatelské jméno. Ověřte, zda je pole **Aktivity** nastaveno na **Zobrazit výsledky pro všechny aktivity**.

4. Klepněte na tlačítko **Hledat**.

Ve výsledcích klikněte na **Filtrovat výsledky** a do pole filtru aktivity zadejte **nastavit poštovní schránku.** Ve výsledcích vyberte záznam auditu. V informačním rámečku **Podrobnosti** klepněte na tlačítko **Další informace**. Musíte se podívat na podrobnosti každého záznamu auditu, abyste zjistili, zda aktivita souvisí s předáváním e-mailů.

- **ObjectId**: Hodnota aliasu poštovní schránky, která byla změněna.

- **Parametry**: _ForwardingSmtpAddress_ označuje cílovou e-mailovou adresu.

- **UserId**: Uživatel, který nakonfiguroval předávání e-mailů v poštovní schránce v poli **ObjectId.**

Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).
