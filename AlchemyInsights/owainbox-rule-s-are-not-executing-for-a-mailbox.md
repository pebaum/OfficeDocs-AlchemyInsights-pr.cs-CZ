---
title: 1332 OWA - pravidla složky Doručená pošta nejsou provádění poštovní schránky
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1332"
- "3700002"
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: 7d1848830847fc6722da20e09a4875f49bf02bd3
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35360910"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="02032-102">Pravidlo pro doručenou poštu nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="02032-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="02032-103">Ověřte následující nastavení:</span><span class="sxs-lookup"><span data-stu-id="02032-103">Verify the following settings:</span></span>

- <span data-ttu-id="02032-104">Zprávy mohou být přesměrovány, předání dál nebo odpovědi automaticky, na základě pravidla složky Doručená pošta pouze jednou.</span><span class="sxs-lookup"><span data-stu-id="02032-104">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time.</span></span> <span data-ttu-id="02032-105">Přesměrování pravidla (pravidla složky Doručená pošta nebo aplikace pravidla toku pošty, označované také jako přenosové pravidlo) můžete přidat maximálně deset předávání příjemci zprávy.</span><span class="sxs-lookup"><span data-stu-id="02032-105">A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message.</span></span> <span data-ttu-id="02032-106">Další informace naleznete v tématu [omezení pravidla deníku, dopravy a složky Doručená pošta](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="02032-106">For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>

- <span data-ttu-id="02032-107">Na alternativní ukládání do deníku poštovní schránky nefungují pravidla složky Doručená pošta.</span><span class="sxs-lookup"><span data-stu-id="02032-107">Inbox rules don't work on the alternate journaling mailbox.</span></span> <span data-ttu-id="02032-108">Další informace o alternativní ukládání do deníku poštovní schránky viz [alternativní ukládání do deníku poštovní schránky](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="02032-108">For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>

<span data-ttu-id="02032-109">Chcete-li vyřešit tyto problémy, viz [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="02032-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>

<span data-ttu-id="02032-110">Pokud nechcete použít předchozí problémy, spusťte diagnostickou zprávu pravidla složky Doručená pošta před eskalovat problém na Microsoft Support:</span><span class="sxs-lookup"><span data-stu-id="02032-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>

1. <span data-ttu-id="02032-111">Otevřít poštovní schránku v aplikaci Outlook na webu a klepněte na tlačítko **Nastavení** \> **možností** \> **uspořádat e-mail** \> **pravidla složky Doručená pošta**.</span><span class="sxs-lookup"><span data-stu-id="02032-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>

2. <span data-ttu-id="02032-112">V dolní části stránky klepněte na tlačítko **Pokud nefungují pravidla klepněte na Generovat diagnostickou zprávu**.</span><span class="sxs-lookup"><span data-stu-id="02032-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
