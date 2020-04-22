---
title: Odchozí e-mail do složky Nevyžádaná pošta
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2697"
ms.assetid: ''
ms.openlocfilehash: 2350586e95f316061ff855d152e86db0547eb209
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43761161"
---
# <a name="outbound-email-to-junk-email-folder"></a><span data-ttu-id="047ea-102">Odchozí e-mail do složky Nevyžádaná pošta</span><span class="sxs-lookup"><span data-stu-id="047ea-102">Outbound email to Junk Email folder</span></span>

<span data-ttu-id="047ea-103">Pokud se vám zobrazují odchozí zprávy označené jako Nevyžádaná pošta, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="047ea-103">If you're seeing outbound messages being marked as Junk, do the following steps:</span></span>

- <span data-ttu-id="047ea-104">Pokud jste tak dosud [neučinili, zvažte konfiguraci oznámení zásad odchozího spamu](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span><span class="sxs-lookup"><span data-stu-id="047ea-104">If you haven't already, consider [configuring outbound spam policy notifications](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span></span>

- <span data-ttu-id="047ea-105">Pomocí [trasování zpráv](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) můžete zjistit, zda má odchozí zpráva hodnotu události **Spam** s dalšími podrobnostmi: Použijte fond pro doručování s **vysokým rizikem**.</span><span class="sxs-lookup"><span data-stu-id="047ea-105">Use [message trace](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) to see if the outbound message has the event value **Spam** with the additional detail: **Use high risk delivery pool**.</span></span>

  <span data-ttu-id="047ea-106">U těchto zpráv zkontrolujte obsah zprávy, abyste zjistili, co by mohlo být považováno za spam.</span><span class="sxs-lookup"><span data-stu-id="047ea-106">For these messages, check the message content to see what might be considered spam.</span></span> <span data-ttu-id="047ea-107">Například podpisy mohou někdy způsobit problémy pro mnoho uživatelů.</span><span class="sxs-lookup"><span data-stu-id="047ea-107">For example, signatures can sometimes cause problems for many users.</span></span>

  <span data-ttu-id="047ea-108">Pokud máte několik příkladů legitimních odchozích zpráv, které jsou označeny jako nevyžádaná pošta, otevřete lístek podpory a požádejte agenta podpory, aby odeslal vaše zprávy jako falešně pozitivní zprávy našim analytikům nevyžádané pošty.</span><span class="sxs-lookup"><span data-stu-id="047ea-108">If you have multiple examples of legitimate outbound messages that are being marked as Junk, open a support ticket and ask the support agent to submit your messages as false positives to our spam analysts.</span></span> <span data-ttu-id="047ea-109">Buďte připraveni poskytnout ukázkové zprávy, které obsahují všechna záhlaví zpráv.</span><span class="sxs-lookup"><span data-stu-id="047ea-109">Be prepared to provide sample messages that include all message headers.</span></span>
