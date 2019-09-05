---
title: Seznámení s webem služby SharePoint Online
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 4c0220dd2535a1ef41aeef99e2bfc3fe28bac03a
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36751665"
---
# <a name="workflows-in-sharepoint"></a>Pracovní postupy ve službě SharePoint

Pokud pracovní postupy služby SharePoint neodesílají e-maily, je možné, že vaše organizace narazila na omezení odesílatele serveru Exchange Online.

Chybová zpráva "pracovní postup je pozastaven" se může zobrazit, pokud máte některou z následujících položek:

- Ve službě SharePoint Online máte pracovní postup, který používá typ platformy SharePoint 2010 nebo SharePoint 2013 Workflow.

- Pracovní postup je konfigurován tak, aby odeslal vlastní e-mailovou zprávu více než 200 uživatelům najednou, více než 10 000 příjemců za den nebo více než 30 zpráv za minutu.

Pokud pracovní postup spustíte, nebude e-mailová zpráva odeslána a zobrazí se chybová zpráva, je v poli vnitřní stav nastavena na pozastaveno nebo není možné odeslat zprávu příjemci.

Další informace naleznete v následujícím [článku](https://docs.microsoft.com/sharepoint/support/workflows/configured-workflow-fails-running).

