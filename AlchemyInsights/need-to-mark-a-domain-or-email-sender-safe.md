---
title: Potřebujete označit doménu nebo e-mail odesílatele v bezpečí?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002921"
- "5673"
ms.openlocfilehash: 7dc1576fd61e87b319c7486c59ed125943b4d959
ms.sourcegitcommit: 43acdecef129bfffc8bbe8ebb08fdd581b238a03
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/18/2020
ms.locfileid: "44281129"
---
# <a name="need-to-mark-a-domain-or-email-sender-safe"></a>Potřebujete označit doménu nebo e-mail odesílatele v bezpečí?

- Používání **bezpečných seznamů odesílatelů se nedoporučuje,** protože otevírá vaši organizaci spamovým, phish a falšování útoků.
- Pokud však existuje obchodní požadavek, **doporučujeme** k tomu použít **[pravidla toku pošty.](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** Naše pokyny zajišťují ověření odesílatele (ověřuje odesílání domény není podpěrná). **Poznámka:** Nedoporučujeme správu falešných poplachů pomocí seznamů bezpečných odesílatelů, protože výjimky z filtrování nevyžádané pošty mohou vaši organizaci otevřít kvůli bezpečnostním útokům. Pokud uživatelé dostávají zprávy nesprávně označené jako nevyžádaná pošta nebo nevyžádané pošty, **[nahlaste zprávy a soubory společnosti Microsoft](https://protection.office.com/reportsubmission)**.
- Je třeba se vyhnout bezpečným odesílatelům v aplikaci Outlook, seznamu povolených odesílatelů nebo povolených domén v zásadách ochrany proti nevyžádané **poště,** protože odesílatelé obejdou veškerou ochranu proti nevyžádané poště, falšování a phish a ověřování odesílatele (SPF, DKIM, DMARC). Tato metoda se nejlépe používá pouze pro dočasné testování.
