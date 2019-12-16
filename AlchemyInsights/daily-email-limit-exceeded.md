---
title: Byl překročen denní limit e-mailů. Pracovní postup je pozastaven.
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 3cad5d8305da0a5db9a85888793350a062e6aed6
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053110"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a>Limit denního e-mailu překročen. Pracovní postup je pozastaven.

Tato chyba může být přijata v následujících situacích:

- Ve službě SharePoint Online máte pracovní postup, který používá typ platformy SharePoint 2010 nebo SharePoint 2013 Workflow.
- Pracovní postup je konfigurován tak, aby odeslal vlastní e-mailovou zprávu více než 200 uživatelům najednou, více než 10 000 příjemců za den nebo více než 30 zpráv za minutu.
- Po spuštění pracovního postupu se e-mailová zpráva neodešle a všimnete si následujícího chování:
    - U pracovního postupu s použitím typu platformy SharePoint 2013 přejdete na stránku **stav pracovního postupu** . Na stránce Stav pracovního postupu je nastaven **vnitřní stav** na **spuštěno**a informační bublina se nezobrazí **k odeslání příjemci**.

Chcete-li tento problém obejít, nakonfigurujte pracovní postup tak, aby odesílal e-mailové zprávy, aniž by překročila [omezení odesílatele serveru Exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits). Můžete například použít pauzu v pracovním postupu, odeslat e-mail skupině Office 365, distribuční skupině nebo skupině zabezpečení s povolenou poštou nebo odeslat zprávu méně než 200 příjemcům najednou.


Další informace naleznete v následujícím [článku](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).

## <a name="related-topics"></a>Související témata
- [Vytvořit tok](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [Služba SharePoint a tok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 