---
title: 1332 OWA - pravidla složky Doručená pošta nejsou provádění poštovní schránky
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1332
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: c0b221b5335254bd0f1eb4b258efa6946376ca12
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32372553"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Pravidlo pro doručenou poštu nefunguje podle očekávání

Ověřte následující nastavení:

- Zprávy mohou být přesměrovány, předání dál nebo odpovědi automaticky, na základě pravidla složky Doručená pošta pouze jednou. Přesměrování pravidla (pravidla složky Doručená pošta nebo aplikace pravidla toku pošty, označované také jako přenosové pravidlo) můžete přidat maximálně deset předávání příjemci zprávy. Další informace naleznete v tématu [omezení pravidla deníku, dopravy a složky Doručená pošta](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).

- Na alternativní ukládání do deníku poštovní schránky nefungují pravidla složky Doručená pošta. Další informace o alternativní ukládání do deníku poštovní schránky viz [alternativní ukládání do deníku poštovní schránky](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).

Chcete-li vyřešit tyto problémy, viz [KB 2829319](https://support.microsoft.com/kb/2829319).

Pokud nechcete použít předchozí problémy, spusťte diagnostickou zprávu pravidla složky Doručená pošta před eskalovat problém na Microsoft Support:

1. Otevřít poštovní schránku v aplikaci Outlook na webu a klepněte na tlačítko **Nastavení** \> **možností** \> **uspořádat e-mail** \> **pravidla složky Doručená pošta**.

2. V dolní části stránky klepněte na tlačítko **Pokud nefungují pravidla klepněte na Generovat diagnostickou zprávu**.
