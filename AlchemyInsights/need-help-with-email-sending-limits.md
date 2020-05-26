---
title: Potřebujete pomoc s limity pro odesílání e-mailů?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002938"
- "5630"
ms.openlocfilehash: 7f563df313c869d18c3e4240d271c649a74914af
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/20/2020
ms.locfileid: "44357396"
---
# <a name="need-help-with-email-sending-limits"></a><span data-ttu-id="83dd0-102">Potřebujete pomoc s limity pro odesílání e-mailů?</span><span class="sxs-lookup"><span data-stu-id="83dd0-102">Need help with email sending limits?</span></span>

<span data-ttu-id="83dd0-103">Níže jsou **uvedeny limity odesílání podle návrhu** vynucené ve službě.</span><span class="sxs-lookup"><span data-stu-id="83dd0-103">Below is the **by-design sending limits** enforced in the service.</span></span> <span data-ttu-id="83dd0-104">Více informací o těchto limitech je popsáno [zde](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).</span><span class="sxs-lookup"><span data-stu-id="83dd0-104">More information on these limits is documented [here](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#receiving-and-sending-limits).</span></span>

- <span data-ttu-id="83dd0-105">Abychom zabránili doručování nevyžádaných hromadných zpráv, uplatňujeme **omezení sazby pro jednotlivé**uživatele na všechny odchozí a interní zprávy .</span><span class="sxs-lookup"><span data-stu-id="83dd0-105">To discourage the delivery of unsolicited bulk messages, we apply per-user **recipient rate limits to all outbound and internal messages**.</span></span> <span data-ttu-id="83dd0-106">Ve všech sku je tento limit **10 000 příjemců za den**.</span><span class="sxs-lookup"><span data-stu-id="83dd0-106">Across all SKUs, this limit is **10,000 recipients per day**.</span></span>  <span data-ttu-id="83dd0-107">Zákazníci, kteří potřebují odeslat legitimní hromadné komerční e-maily (například bulletiny zákazníků), by měli používat poskytovatele třetích stran, kteří se specializují na tyto služby.</span><span class="sxs-lookup"><span data-stu-id="83dd0-107">Customers who need to send legitimate bulk commercial email (for example, customer newsletters) should use third-party providers that specialize in these services.</span></span>
    - <span data-ttu-id="83dd0-108">**Poznámka:** Po dosažení limitu počtu příjemců nelze zprávy odesílat z poštovní schránky, dokud počet příjemců, kterým byly za posledních 24 hodin odeslány zprávy, neklesne pod limit.</span><span class="sxs-lookup"><span data-stu-id="83dd0-108">**Note**: Once the recipient rate limit is reached, messages can't be sent from the mailbox until the number of recipients that were sent messages in the past 24 hours drops below the limit.</span></span> <span data-ttu-id="83dd0-109">Uživatel nebude moci odesílat zprávy až do tohoto okamžiku.</span><span class="sxs-lookup"><span data-stu-id="83dd0-109">The user will not be able to send messages until that point.</span></span>
- <span data-ttu-id="83dd0-110">Limit rychlosti zpráv **30 zpráv za minutu** se použije ve všech sku.</span><span class="sxs-lookup"><span data-stu-id="83dd0-110">Message rate limit of **30 messages per minute** is applied across all SKUs.</span></span> <span data-ttu-id="83dd0-111">To určuje, kolik zpráv může uživatel odeslat ze svého účtu Exchange Online během zadaného období.</span><span class="sxs-lookup"><span data-stu-id="83dd0-111">This determines how many messages a user can send from their Exchange Online account within a specified period.</span></span>
- <span data-ttu-id="83dd0-112">Maximální počet příjemců povolených v polích **Komu, Kopie a Skrytá** pro jednu e-mailovou zprávu napříč všemi skujemi je **1000 příjemců**.</span><span class="sxs-lookup"><span data-stu-id="83dd0-112">The **maximum number of recipients allowed in the To, Cc, and Bcc** fields for a single email message, across all SKUs, is **1000 recipients**.</span></span> <span data-ttu-id="83dd0-113">Chcete-li přizpůsobit tento limit, přejděte [sem](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).</span><span class="sxs-lookup"><span data-stu-id="83dd0-113">To customize this limit, go [here](https://techcommunity.microsoft.com/t5/exchange-team-blog/customizable-recipient-limits-in-office-365/ba-p/1183228).</span></span>
