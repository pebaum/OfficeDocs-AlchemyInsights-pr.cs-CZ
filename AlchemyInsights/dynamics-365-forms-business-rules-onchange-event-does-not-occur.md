---
title: Dynamics 365 formuláře obchodní pravidla-obchodní pravidlo Nepálení pro formulář
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 3cdd2175083e864b3bffc57a70bb6c6220843fad
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "37769332"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>K události při změně nedojde, pokud je pole změněno programově

K události *při změně* nedojde, pokud se pole změní programově pomocí *atributu.* Metoda [SetValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Chcete-li, aby byly obslužné rutiny události při *změně* spuštěny po nastavení hodnoty, musíte použít *atribut FormContext. data. entity* [](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) v kódu.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
