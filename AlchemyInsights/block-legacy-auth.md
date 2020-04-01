---
title: BlockLegacyAuth
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3154"
- "9001194"
ms.openlocfilehash: e7bff5f9fcf6f2f2c77e93c2f27f585f2cc18bea
ms.sourcegitcommit: 98231a228ecb2bf14ec3b96d4dd4ccf2507617a3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/01/2020
ms.locfileid: "43079253"
---
# <a name="blocking-legacy-authentication"></a>Blokování staršíverze ověřování

Starší verze ověřování je termín, který odkazuje na požadavek na ověření ze strany:

- Starší klienti Office, kteří nepoužívají moderní ověřování (například klient Office 2010).

- Každý klient, který používá starší poštovní protokoly, například IMAP/SMTP/POP3.

Další informace o blokování staršíverze ověřování a povolení moderníověřování naleznete [v průvodní verze ověřování](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).

Výchozí nastavení zabezpečení ve službě Azure Active Directory (Azure AD) usnadňují zabezpečení a pomáhají chránit vaši organizaci. Výchozí hodnoty zabezpečení obsahují předem nakonfigurovaná nastavení zabezpečení pro běžné útoky.
Další informace o výchozích hodnotách zabezpečení naleznete v odkazech [Co jsou výchozí hodnoty zabezpečení?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults). 

**Poznámka:** Pokud váš tenant byl vytvořen na nebo po 22.12.2019, je možné, že dochází k nové chování zabezpečené ve výchozím nastavení a již mají výchozí nastavení zabezpečení povoleno ve vašem tenantovi.  Ve snaze chránit všechny naše uživatele, výchozí zabezpečení se zavádí do všech nových klientů vytvořených.
