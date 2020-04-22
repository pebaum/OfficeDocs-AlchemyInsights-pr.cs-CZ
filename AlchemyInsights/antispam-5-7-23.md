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
ms.openlocfilehash: 307b738c40c620d057e68eff7d218c8c9b5eb665
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676490"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="b986a-102">Oprava problémů s doručováním e-mailů pro kód chyby 5.7.23</span><span class="sxs-lookup"><span data-stu-id="b986a-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="b986a-103">Ověřte záznam DNS SPF pro vaši doménu na veřejně dostupné kontrole záznamů SPF nebo DNS na webu.</span><span class="sxs-lookup"><span data-stu-id="b986a-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="b986a-104">Ověřte, zda odchozí zpráva nebyla společností Microsoft označena jako nevyžádaná pošta a směrována přes [fond pro doručování vysokých rizik](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span><span class="sxs-lookup"><span data-stu-id="b986a-104">Verify that the outbound message wasn't identified as spam by Microsoft and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="b986a-105">Zprávy ve fondu doručování s vysokým rizikem neprojdou kontrolami SPF, a proto nebudou akceptovány cílovou e-mailovou organizací.</span><span class="sxs-lookup"><span data-stu-id="b986a-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="b986a-106">Pokud problém přetrvává, možná budete muset kontaktovat správce hostitele pošty, kterému se pokoušíte odeslat e-mail.</span><span class="sxs-lookup"><span data-stu-id="b986a-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="b986a-107">Poznamenejte si podrobnou externí chybu, která je k dispozici ve zprávě o okamžitém opuštění.</span><span class="sxs-lookup"><span data-stu-id="b986a-107">Make note of the detailed external error available in the bounce message.</span></span> <span data-ttu-id="b986a-108">Podpora společnosti Microsoft nemusí být schopna dále pomoci.</span><span class="sxs-lookup"><span data-stu-id="b986a-108">Microsoft support may not be able to assist further.</span></span>
