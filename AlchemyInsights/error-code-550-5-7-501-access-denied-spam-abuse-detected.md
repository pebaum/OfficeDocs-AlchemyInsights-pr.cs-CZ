---
title: Kód chyby 550 5.7.501 Přístup odepřen, bylo zjištěno zneužití nevyžádané pošty
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
ms.openlocfilehash: 7be23f02878d12aa08cb4970af6f99539a9cefab
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703019"
---
# <a name="550-57501-access-denied-spam-abuse-detected"></a>550 5.7.501 Přístup odepřen, bylo zjištěno zneužití spamu

Tato zpráva se obvykle vyskytuje, když uživatelé odesílají e-mailové zprávy z IP adres pomocí počáteční domény *.onmicrosoft.com,* která je přiřazena novým klientům v Microsoftu 365. Nejjednodušší způsob, jak tento problém vyřešit, je:

1. [Přidejte doménu do klienta](https://docs.microsoft.com//office365/admin/setup/add-domain).

2. [Změňte primární e-mailovou adresu uživatelů](https://docs.microsoft.com//office365/admin/add-users/change-a-user-name-and-email-address) na novou vlastní doménu, kterou jste právě přidali.
