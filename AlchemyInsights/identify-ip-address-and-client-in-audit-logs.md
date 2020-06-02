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
ms.openlocfilehash: 80b652eb65612093252dee226a19ec74bc035faa
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508909"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a>Identifikace IP adresy a klienta v protokolech auditu

Ip adresa, která odpovídá aktivitě uživatele nebo správce microsoftu 365, je zobrazena v protokolech auditování. Informace o klientovi jsou také protokolovány. Zde jsou kroky k identifikaci těchto informací

1. Přihlaste se do [Centra dodržování předpisů zabezpečení microsoftu 365 &](https://protection.office.com/).

2. Přejděte **Search**na  >  stránku**hledání protokolu auditu** hledání.

   Pokud máte zájem o konkrétní aktivitu, vyberte ji ze seznamu **Aktivity.** Pokud ne, budou pro vybraného uživatele vráceny všechny aktivity (výchozí nastavení).

   **Poznámka:** Některé aktivity nemusí být v nabídce **Aktivity** k dispozici. tyto položky auditu však budou vráceny, pokud je vybrána možnost **Zobrazit výsledky pro všechny aktivity** (výchozí nastavení).

3. Zadejte uživatelské jméno do pole **Uživatelé,** vyberte příslušné časové období aktivity a klepněte na tlačítko **Hledat**.

Ve výsledcích se v podokně výsledků zobrazí ADRESA IP pro tuto aktivitu. Výběrem záznamu auditu zobrazíte podrobné informace v informačním rámečku **Podrobnosti** (například Klient, Uživatel, který provedl akci atd.).

Další informace naleznete [v tématu Hledání ADRESY IP počítače použitého pro přístup k ohroženému účtu](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#find-the-ip-address-of-the-computer-used-to-access-a-compromised-account).
