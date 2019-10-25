---
title: Antispam-5.7.23
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
ms.openlocfilehash: 9c9bc2d04fb8efaa5e75194b4ca09316d24e018e
ms.sourcegitcommit: 07b47d7f3ca191363e6bc84140e8e01524d6f08e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/24/2019
ms.locfileid: "37682076"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Opravit problémy s doručením e-mailu pro chybový kód 5.7.23

Ověřte záznam DNS SPF pro vaši doménu na veřejně dostupném nástroji SPF nebo DNS pro kontrolu záznamů na webu.

Ověřte, zda odchozí zpráva nebyla identifikována jako nevyžádaná pošta v sadě Office 365 a směrována prostřednictvím [fondu vysoce rizikových dodávek](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages). Zprávy ve fondu doručení s vysokým rizikem neprojíždějí kontrolami SPF, a proto nejsou přijímány cílovou e-mailovou organizací.

Pokud potíže potrvají, bude pravděpodobně nutné kontaktovat správce poštovního hostitele, kterému se pokoušíte odeslat e-mail. Poznamenejte si podrobnou externí chybu, která je k dispozici ve zprávě o odrazu.  Podpora sady Office 365 pravděpodobně nebude moci dále pomáhat.