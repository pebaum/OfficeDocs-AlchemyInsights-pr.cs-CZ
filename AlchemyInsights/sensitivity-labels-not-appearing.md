---
title: Popisky citlivosti se nezobrazují.
ms.author: stephow
author: stephow-MSFT
manager: laurawi
ms.date: ''
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 4bf8e02246c966f22648467386a7862f0521fecf
ms.sourcegitcommit: 71978e2bb779b5955fd113f84512b83321b26912
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/26/2019
ms.locfileid: "37207218"
---
# <a name="sensitivity-labels-not-appearing"></a>Popisky citlivosti se nezobrazují.

Popisky citlivosti umožňují klasifikovat a chránit citlivý obsah. Lze je vytvořit v centru pro kompatibilita společnosti Microsoft 365, ve středisku Microsoft 365 Security Center nebo Office 365 Security Center & v sekci klasifikace citlivosti >. Další informace o této funkci naleznete v [přehledu popisů citlivosti](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels).

Pokud jste nakonfigurovali popisky citlivosti, ale nezobrazují se v aplikacích sady Office, zkontrolujte následující:

- Potvrďte, že popisek citlivosti byl [publikován](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) pro uživatele a skupiny, které požadujete.

- Potvrďte, že uživatel používá aplikaci podporující popisky citlivosti-viz [popisky citlivosti v dokumentu](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?ad=US&ui=en-US&rs=en-US#bkmk_whereavailable).

- Pokud [migrujete štítky na ochranu informací Azure](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), uvědomte si [zde](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels)uvedené skutečnosti.

- Podpora pro zabránění ztrátě dat (DLP): v současné době lze jako podmínku v zásadách DLP použít pouze retenční štítky.  Podpora popisků citlivosti v zásadách DLP ještě není k dispozici, ale pracujeme na tom.

- Je-li povoleno šifrování na štítku s citlivostí, můžete zvolit jednu z těchto možnosti:
    - Přiřadit oprávnění nyní
    - Dovolit uživatelům přiřazovat oprávnění


Další informace o možných problémech naleznete v tématu [známé problémy s popisky citlivosti](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).