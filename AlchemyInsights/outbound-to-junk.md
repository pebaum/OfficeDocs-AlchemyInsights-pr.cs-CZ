---
title: Odchozí e-mail do složky Nevyžádaná pošta
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2697"
ms.assetid: ''
ms.openlocfilehash: 371d2c46e9048365fd343145330536bd9cf1db82
ms.sourcegitcommit: 1002f510fadb92c143cd6bbb60b42a851d5a38e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/20/2019
ms.locfileid: "37062752"
---
# <a name="outbound-email-to-junk-email-folder"></a><span data-ttu-id="98b53-102">Odchozí e-mail do složky Nevyžádaná pošta</span><span class="sxs-lookup"><span data-stu-id="98b53-102">Outbound email to Junk Email folder</span></span>

<span data-ttu-id="98b53-103">Pokud se zobrazují odchozí zprávy označené jako nevyžádaná pošta, proveďte následující kroky:</span><span class="sxs-lookup"><span data-stu-id="98b53-103">If you're seeing outbound messages being marked as Junk, do the following steps:</span></span>

- <span data-ttu-id="98b53-104">Pokud jste tak dosud neučinili, zvažte možnost [Konfigurace oznámení o zásadách odchozích nevyžádaných zpráv](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span><span class="sxs-lookup"><span data-stu-id="98b53-104">If you haven't already, consider [configuring outbound spam policy notifications](https://docs.microsoft.com/office365/securitycompliance/configure-the-outbound-spam-policy).</span></span>

- <span data-ttu-id="98b53-105">Pomocí [trasování zprávy](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) Zjistěte, zda je u odchozí zprávy hodnota události **Nevyžádaná pošta spam** s dodatečnými podrobnostmi: **používejte vysokorizikový fond**.</span><span class="sxs-lookup"><span data-stu-id="98b53-105">Use [message trace](https://docs.microsoft.com/office365/securitycompliance/message-trace-scc) to see if the outbound message has the event value **Spam** with the additional detail: **Use high risk delivery pool**.</span></span>

  <span data-ttu-id="98b53-106">U těchto zpráv zkontrolujte obsah zprávy a zjistěte, co může být považováno za nevyžádanou poštu.</span><span class="sxs-lookup"><span data-stu-id="98b53-106">For these messages, check the message content to see what might be considered spam.</span></span> <span data-ttu-id="98b53-107">Například podpisy mohou někdy způsobit problémy mnoha uživatelům.</span><span class="sxs-lookup"><span data-stu-id="98b53-107">For example, signatures can sometimes cause problems for many users.</span></span>

  <span data-ttu-id="98b53-108">Máte-li několik příkladů legitimních odchozích zpráv, které jsou označeny jako nevyžádaná pošta, otevřete lístek odborné pomoci a požádejte agenta podpory, aby své zprávy předložil svým analytikům nevyžádané pošty jako chybné.</span><span class="sxs-lookup"><span data-stu-id="98b53-108">If you have multiple examples of legitimate outbound messages that are being marked as Junk, open a support ticket and ask the support agent to submit your messages as false positives to our spam analysts.</span></span> <span data-ttu-id="98b53-109">Připravte se na poskytnutí ukázkových zpráv, které zahrnují všechna záhlaví zpráv.</span><span class="sxs-lookup"><span data-stu-id="98b53-109">Be prepared to provide sample messages that include all message headers.</span></span>
