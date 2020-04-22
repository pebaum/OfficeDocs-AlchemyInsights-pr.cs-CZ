---
title: Antispam - 5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 307b738c40c620d057e68eff7d218c8c9b5eb665
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676490"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Oprava problémů s doručováním e-mailů pro kód chyby 5.7.23

Ověřte záznam DNS SPF pro vaši doménu na veřejně dostupné kontrole záznamů SPF nebo DNS na webu.

Ověřte, zda odchozí zpráva nebyla společností Microsoft označena jako nevyžádaná pošta a směrována přes [fond pro doručování vysokých rizik](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages). Zprávy ve fondu doručování s vysokým rizikem neprojdou kontrolami SPF, a proto nebudou akceptovány cílovou e-mailovou organizací.

Pokud problém přetrvává, možná budete muset kontaktovat správce hostitele pošty, kterému se pokoušíte odeslat e-mail. Poznamenejte si podrobnou externí chybu, která je k dispozici ve zprávě o okamžitém opuštění. Podpora společnosti Microsoft nemusí být schopna dále pomoci.
