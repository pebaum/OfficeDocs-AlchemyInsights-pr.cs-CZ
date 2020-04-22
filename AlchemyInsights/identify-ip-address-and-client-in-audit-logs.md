---
title: Identifikace IP adresy a klienta v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: d1a0d412fc0c6d79e50b101ca759127522f45dcd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716381"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Identifikace IP adresy a klienta v protokolech auditu

Ip adresa, která odpovídá aktivitě uživatele nebo správce microsoftu 365, je zobrazena v protokolech auditu. Informace o klientovi jsou také protokolovány. Zde jsou kroky k identifikaci těchto informací

1. Přihlaste se k [Centru dodržování předpisů pro zabezpečení & microsoft 365](https://protection.office.com/).

2. Přejděte na stránku**hledání protokolu auditování** **vyhledávání.** > 

   Pokud máte zájem o konkrétní aktivitu, vyberte ji ze seznamu **Aktivity.** Pokud tomu tak není, budou pro vybraného uživatele vráceny všechny aktivity (výchozí nastavení).

   **Poznámka**: Některé aktivity nemusí být v nabídce **Aktivity** k dispozici. tyto položky auditu však budou vráceny, pokud je **vybrána možnost Zobrazit výsledky pro všechny aktivity** (výchozí nastavení).

3. Zadejte uživatelské jméno do pole **Uživatelé,** vyberte příslušné časové období aktivity a klepněte na tlačítko **Hledat**.

Ve výsledcích se zobrazí ip adresa pro tuto aktivitu v podokně výsledků. Výběrem záznamu auditu zobrazíte podrobné informace v informačním rámečku **Podrobnosti** (například Klient, Uživatel, který provedl akci atd.).

Další informace naleznete [v tématu Hledání IP adresy počítače používaného pro přístup k ohroženému účtu](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).
