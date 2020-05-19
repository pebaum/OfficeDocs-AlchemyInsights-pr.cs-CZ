---
title: Potřebujete označit doménu nebo e-mail odesílatele v bezpečí?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002921"
- "5673"
ms.openlocfilehash: 7dc1576fd61e87b319c7486c59ed125943b4d959
ms.sourcegitcommit: 43acdecef129bfffc8bbe8ebb08fdd581b238a03
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/18/2020
ms.locfileid: "44281129"
---
# <a name="need-to-mark-a-domain-or-email-sender-safe"></a><span data-ttu-id="8df7c-102">Potřebujete označit doménu nebo e-mail odesílatele v bezpečí?</span><span class="sxs-lookup"><span data-stu-id="8df7c-102">Need to mark a domain or email sender safe?</span></span>

- <span data-ttu-id="8df7c-103">Používání **bezpečných seznamů odesílatelů se nedoporučuje,** protože otevírá vaši organizaci spamovým, phish a falšování útoků.</span><span class="sxs-lookup"><span data-stu-id="8df7c-103">Use of **safe sender lists is not recommended** since it opens up your organization to spam, phish, and spoofing attacks.</span></span>
- <span data-ttu-id="8df7c-104">Pokud však existuje obchodní požadavek, **doporučujeme** k tomu použít **[pravidla toku pošty.](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)**</span><span class="sxs-lookup"><span data-stu-id="8df7c-104">However, if there is a business requirement, we **recommend** using **[Mail Flow Rules](https://docs.microsoft.com/microsoft-365/security/office-365-security/create-safe-sender-lists-in-office-365?view=o365-worldwide#recommended-use-mail-flow-rules)** for this.</span></span> <span data-ttu-id="8df7c-105">Naše pokyny zajišťují ověření odesílatele (ověřuje odesílání domény není podpěrná).</span><span class="sxs-lookup"><span data-stu-id="8df7c-105">Our guidance ensures sender authentication (verifies sending domain is not being spoofed).</span></span> <span data-ttu-id="8df7c-106">**Poznámka:** Nedoporučujeme správu falešných poplachů pomocí seznamů bezpečných odesílatelů, protože výjimky z filtrování nevyžádané pošty mohou vaši organizaci otevřít kvůli bezpečnostním útokům.</span><span class="sxs-lookup"><span data-stu-id="8df7c-106">**Note**: We don't recommend managing false positives by using safe sender lists, because exceptions to spam filtering can open your organization to security attacks.</span></span> <span data-ttu-id="8df7c-107">Pokud uživatelé dostávají zprávy nesprávně označené jako nevyžádaná pošta nebo nevyžádané pošty, **[nahlaste zprávy a soubory společnosti Microsoft](https://protection.office.com/reportsubmission)**.</span><span class="sxs-lookup"><span data-stu-id="8df7c-107">If your user(s) receive messages incorrectly marked as spam or junk email, please **[Report messages and files to Microsoft](https://protection.office.com/reportsubmission)**.</span></span>
- <span data-ttu-id="8df7c-108">Je třeba se vyhnout bezpečným odesílatelům v aplikaci Outlook, seznamu povolených odesílatelů nebo povolených domén v zásadách ochrany proti nevyžádané **poště,** protože odesílatelé obejdou veškerou ochranu proti nevyžádané poště, falšování a phish a ověřování odesílatele (SPF, DKIM, DMARC).</span><span class="sxs-lookup"><span data-stu-id="8df7c-108">Safe Senders in Outlook, Allowed sender list, or allowed domain list in anti-spam policies **should be avoided** because senders bypass all spam, spoof, and phish protection, and sender authentication (SPF, DKIM, DMARC).</span></span> <span data-ttu-id="8df7c-109">Tato metoda se nejlépe používá pouze pro dočasné testování.</span><span class="sxs-lookup"><span data-stu-id="8df7c-109">This method is best used for temporary testing only.</span></span>
