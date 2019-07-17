---
title: Dynamics 365 tvoří obchodní pravidla - obchodní pravidlo ve formuláři se nespustí
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/16/2019
ms.locfileid: "35747223"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Při změně události nedojde, pokud je změněno pole programově

Událost *OnChange* nedochází, pokud je změněno pole programově pomocí *atribut.* [setValue](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) metody. Chcete-li obslužných rutin událostí pro události *OnChange* pro spuštění po nastavení hodnoty je třeba použít *atribut formContext.data.entity.* [fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) metoda ve vašem kódu.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
