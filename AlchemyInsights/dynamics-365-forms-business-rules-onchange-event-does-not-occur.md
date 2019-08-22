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
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a><span data-ttu-id="c6d59-102">Při změně události nedojde, pokud je změněno pole programově</span><span class="sxs-lookup"><span data-stu-id="c6d59-102">OnChange event does not occur if the field is changed programmatically</span></span>

<span data-ttu-id="c6d59-103">Událost *OnChange* nedochází, pokud je změněno pole programově pomocí *atribut.* [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) metody.</span><span class="sxs-lookup"><span data-stu-id="c6d59-103">The *OnChange* event does not occur if the field is changed programmatically using the *attribute.*[setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) method.</span></span> <span data-ttu-id="c6d59-104">Chcete-li obslužných rutin událostí pro události *OnChange* pro spuštění po nastavení hodnoty je třeba použít *atribut formContext.data.entity.* [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) metoda ve vašem kódu.</span><span class="sxs-lookup"><span data-stu-id="c6d59-104">If you want event handlers for the *OnChange* event to run after you set the value you must use the *formContext.data.entity attribute.*[fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) method in your code.</span></span>

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
