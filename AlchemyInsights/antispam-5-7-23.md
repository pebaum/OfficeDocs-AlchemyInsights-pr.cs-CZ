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
ms.openlocfilehash: 8122b409a731a5fcc46c718aff1eeda07e26890b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506436"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Řešení problémů s doručováním e-mailů s kódem chyby 5.7.23

Ověřte záznam SPF DNS pro vaši doménu ve veřejně dostupné kontrole záznamů SPF nebo DNS na webu.

Ověřte, zda společnost Microsoft neoznačil odchozí zprávu jako spam a zda nebyla směrována prostřednictvím [fondu pro doručování s vysokým rizikem](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages). Zprávy ve fondu doručování s vysokým rizikem neprojdou kontrolami SPF, a proto nebudou přijaty organizací cílového e-mailu.

Pokud problém přetrvává, bude pravděpodobně nutné kontaktovat správce hostitele pošty, kterému se pokoušíte odeslat e-mail. Poznamenejte si podrobnou externí chybu, která je k dispozici ve zprávě o vrácení. Podpora společnosti Microsoft nemusí být schopna dále pomoci.
