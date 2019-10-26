---
title: Kód chyby 550 5.7.501 odepřen přístup, bylo zjištěno zneužití nevyžádané pošty
ms.author: chrisda
author: chrisda
ms.date: 6/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "351"
- "3100015"
ms.assetid: 3105905c-e7a0-42a7-9c5a-61dc56a1d6fc
ms.openlocfilehash: 545cab07cc7c49def849be20bb6363da228a5393
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36740134"
---
# <a name="550-57501-access-denied-spam-abuse-detected"></a><span data-ttu-id="5aff3-102">550 5.7.501 odepření přístupu, zjištěno zneužití nevyžádané pošty</span><span class="sxs-lookup"><span data-stu-id="5aff3-102">550 5.7.501 Access denied, spam abuse detected</span></span>

<span data-ttu-id="5aff3-103">Tato zpráva se obvykle zobrazí, pokud uživatelé odesílají e-mailové zprávy z adres IP pomocí počáteční domény *onmicrosoft.com* , která je přiřazena novým nájemníkům v sadě Office 365.</span><span class="sxs-lookup"><span data-stu-id="5aff3-103">Typically, this message occurs when users send email messages from IP addresses using the initial *.onmicrosoft.com* domain that's assigned to new tenants in Office 365.</span></span> <span data-ttu-id="5aff3-104">Nejjednodušším způsobem řešení těchto potíží je:</span><span class="sxs-lookup"><span data-stu-id="5aff3-104">The easiest way to resolve this problem is to:</span></span>

1. <span data-ttu-id="5aff3-105">[Přidejte doménu k nájemci](https://docs.microsoft.com//office365/admin/setup/add-domain).</span><span class="sxs-lookup"><span data-stu-id="5aff3-105">[Add a domain to your tenant](https://docs.microsoft.com//office365/admin/setup/add-domain).</span></span>

2. <span data-ttu-id="5aff3-106">[Změňte primární e-mailovou adresu uživatele](https://docs.microsoft.com//office365/admin/add-users/change-a-user-name-and-email-address) na novou vlastní doménu, kterou jste právě přidali.</span><span class="sxs-lookup"><span data-stu-id="5aff3-106">[Change your users' primary email address](https://docs.microsoft.com//office365/admin/add-users/change-a-user-name-and-email-address) to the new custom domain you just added.</span></span>
