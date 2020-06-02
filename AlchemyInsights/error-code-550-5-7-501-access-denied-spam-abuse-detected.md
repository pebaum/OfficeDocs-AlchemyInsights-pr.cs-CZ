---
title: Kód chyby 550 5.7.501 Přístup byl odepřen, bylo zjištěno zneužití nevyžádané pošty
ms.author: chrisda
author: chrisda
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "351"
- "3100015"
ms.assetid: 3105905c-e7a0-42a7-9c5a-61dc56a1d6fc
ms.openlocfilehash: 9fd4f14798f27e7bf93daceb3620aff9b7f9e8ed
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506803"
---
# <a name="550-57501-access-denied-spam-abuse-detected"></a>550 5.7.501 Přístup odepřen, bylo zjištěno zneužití spamu

K této zprávě obvykle dochází, když uživatelé odesílají e-mailové zprávy z IP adres pomocí počáteční domény *.onmicrosoft.com,* která je přiřazena novým klientům v Microsoftu 365. Nejjednodušší způsob, jak tento problém vyřešit, je:

1. [Přidejte doménu do svého tenanta](https://docs.microsoft.com/microsoft-365/admin/setup/add-domain).

2. [Změňte primární e-mailovou adresu uživatelů](https://docs.microsoft.com/microsoft-365/admin/add-users/change-a-user-name-and-email-address) na novou vlastní doménu, kterou jste právě přidali.
