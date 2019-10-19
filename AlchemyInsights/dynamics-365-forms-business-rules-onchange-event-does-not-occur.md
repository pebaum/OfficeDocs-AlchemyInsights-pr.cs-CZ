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
ms.openlocfilehash: cbdedd2c5fcf5517243e60e36d86479d6c3f7814
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36529012"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>K události při změně nedojde, pokud je pole změněno programově

K události *při změně* nedojde, pokud se pole změní programově pomocí *atributu.* Metoda [SetValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Pokud chcete, aby byly obslužné rutiny události události při *změně* spuštěny po nastavení hodnoty, musíte použít *atribut FormContext. data. entity.* ve vašem kódu metodu [Fireonchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) .

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
