---
title: Antispam-5.7.23
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
ms.openlocfilehash: 9c9bc2d04fb8efaa5e75194b4ca09316d24e018e
ms.sourcegitcommit: 07b47d7f3ca191363e6bc84140e8e01524d6f08e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/24/2019
ms.locfileid: "37682076"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="0f11d-102">Opravit problémy s doručením e-mailu pro chybový kód 5.7.23</span><span class="sxs-lookup"><span data-stu-id="0f11d-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="0f11d-103">Ověřte záznam DNS SPF pro vaši doménu na veřejně dostupném nástroji SPF nebo DNS pro kontrolu záznamů na webu.</span><span class="sxs-lookup"><span data-stu-id="0f11d-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="0f11d-104">Ověřte, zda odchozí zpráva nebyla identifikována jako nevyžádaná pošta v sadě Office 365 a směrována prostřednictvím [fondu vysoce rizikových dodávek](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span><span class="sxs-lookup"><span data-stu-id="0f11d-104">Verify that the outbound message wasn't identified as spam by Office 365 and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="0f11d-105">Zprávy ve fondu doručení s vysokým rizikem neprojíždějí kontrolami SPF, a proto nejsou přijímány cílovou e-mailovou organizací.</span><span class="sxs-lookup"><span data-stu-id="0f11d-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="0f11d-106">Pokud potíže potrvají, bude pravděpodobně nutné kontaktovat správce poštovního hostitele, kterému se pokoušíte odeslat e-mail.</span><span class="sxs-lookup"><span data-stu-id="0f11d-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="0f11d-107">Poznamenejte si podrobnou externí chybu, která je k dispozici ve zprávě o odrazu.</span><span class="sxs-lookup"><span data-stu-id="0f11d-107">Make note of the detailed external error available in the bounce message.</span></span>  <span data-ttu-id="0f11d-108">Podpora sady Office 365 pravděpodobně nebude moci dále pomáhat.</span><span class="sxs-lookup"><span data-stu-id="0f11d-108">Office 365 support may not be able to assist further.</span></span>