---
title: 1332 OWA - pravidla složky Doručená pošta nejsou provádění poštovní schránky
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: f090d0a9d84bc6a4d1a1f4c0af55102d4b0ddfbe
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281864"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a><span data-ttu-id="f3cb0-102">Pravidlo pro doručenou poštu nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="f3cb0-102">An Inbox rule doesn't work as expected</span></span>

<span data-ttu-id="f3cb0-103">Ověřte následující nastavení:</span><span class="sxs-lookup"><span data-stu-id="f3cb0-103">Verify the following settings:</span></span>
  
- <span data-ttu-id="f3cb0-p101">Zprávy mohou být přesměrovány, předání dál nebo odpovědi automaticky, na základě pravidla složky Doručená pošta pouze jednou. Přesměrování pravidla (pravidla složky Doručená pošta nebo aplikace pravidla toku pošty, označované také jako přenosové pravidlo) můžete přidat maximálně deset předávání příjemci zprávy. Další informace naleznete v tématu [omezení pravidla deníku, dopravy a složky Doručená pošta](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span><span class="sxs-lookup"><span data-stu-id="f3cb0-p101">A message can be redirected, forwarded, or replied to automatically based on Inbox rules only one time. A redirecting rule (an Inbox rule or mail flow rule, also known as a transport rule) can add a maximum of ten forwarding recipients to a message. For more information, see [Journal, Transport, and Inbox rule limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).</span></span>
    
- <span data-ttu-id="f3cb0-p102">Na alternativní ukládání do deníku poštovní schránky nefungují pravidla složky Doručená pošta. Další informace o alternativní ukládání do deníku poštovní schránky viz [alternativní ukládání do deníku poštovní schránky](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span><span class="sxs-lookup"><span data-stu-id="f3cb0-p102">Inbox rules don't work on the alternate journaling mailbox. For more information about the alternate journaling mailbox, see [Alternate journaling mailbox](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).</span></span>
    
<span data-ttu-id="f3cb0-109">Chcete-li vyřešit tyto problémy, viz [KB 2829319](https://support.microsoft.com/kb/2829319).</span><span class="sxs-lookup"><span data-stu-id="f3cb0-109">To fix these issues, see [KB 2829319](https://support.microsoft.com/kb/2829319).</span></span>
  
<span data-ttu-id="f3cb0-110">Pokud nechcete použít předchozí problémy, spusťte diagnostickou zprávu pravidla složky Doručená pošta před eskalovat problém na Microsoft Support:</span><span class="sxs-lookup"><span data-stu-id="f3cb0-110">If the previous issues don't apply, run the Inbox rule diagnostic report before you escalate the issue to Microsoft Support:</span></span>
  
1. <span data-ttu-id="f3cb0-111">Otevřít poštovní schránku v aplikaci Outlook na webu a klepněte na tlačítko **Nastavení** \> **možností** \> **uspořádat e-mail** \> **pravidla složky Doručená pošta**.</span><span class="sxs-lookup"><span data-stu-id="f3cb0-111">Open the mailbox in Outlook on the web, and click **Settings** \> **Options** \> **Organize email** \> **Inbox rules**.</span></span>
    
2. <span data-ttu-id="f3cb0-112">V dolní části stránky klepněte na tlačítko **Pokud nefungují pravidla klepněte na Generovat diagnostickou zprávu**.</span><span class="sxs-lookup"><span data-stu-id="f3cb0-112">At the bottom of the page, click **If your rules are not working click here to generate a diagnostic report**.</span></span>
    

