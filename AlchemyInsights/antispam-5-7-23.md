---
title: Antispam - 5.7.23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 8122b409a731a5fcc46c718aff1eeda07e26890b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506436"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="81866-102">Řešení problémů s doručováním e-mailů s kódem chyby 5.7.23</span><span class="sxs-lookup"><span data-stu-id="81866-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="81866-103">Ověřte záznam SPF DNS pro vaši doménu ve veřejně dostupné kontrole záznamů SPF nebo DNS na webu.</span><span class="sxs-lookup"><span data-stu-id="81866-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="81866-104">Ověřte, zda společnost Microsoft neoznačil odchozí zprávu jako spam a zda nebyla směrována prostřednictvím [fondu pro doručování s vysokým rizikem](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages).</span><span class="sxs-lookup"><span data-stu-id="81866-104">Verify that the outbound message wasn't identified as spam by Microsoft and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="81866-105">Zprávy ve fondu doručování s vysokým rizikem neprojdou kontrolami SPF, a proto nebudou přijaty organizací cílového e-mailu.</span><span class="sxs-lookup"><span data-stu-id="81866-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="81866-106">Pokud problém přetrvává, bude pravděpodobně nutné kontaktovat správce hostitele pošty, kterému se pokoušíte odeslat e-mail.</span><span class="sxs-lookup"><span data-stu-id="81866-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="81866-107">Poznamenejte si podrobnou externí chybu, která je k dispozici ve zprávě o vrácení.</span><span class="sxs-lookup"><span data-stu-id="81866-107">Make note of the detailed external error available in the bounce message.</span></span> <span data-ttu-id="81866-108">Podpora společnosti Microsoft nemusí být schopna dále pomoci.</span><span class="sxs-lookup"><span data-stu-id="81866-108">Microsoft support may not be able to assist further.</span></span>
