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
ms.openlocfilehash: cbdedd2c5fcf5517243e60e36d86479d6c3f7814
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529012"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Při změně události nedojde, pokud je změněno pole programově

Událost *OnChange* nedochází, pokud je změněno pole programově pomocí *atribut.* [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) metody. Chcete-li obslužných rutin událostí pro události *OnChange* pro spuštění po nastavení hodnoty je třeba použít *atribut formContext.data.entity.* [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) metoda ve vašem kódu.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
