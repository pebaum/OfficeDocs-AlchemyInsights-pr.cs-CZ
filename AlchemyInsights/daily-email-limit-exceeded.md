---
title: Byl překročen denní limit e-mailu. Pracovního postupu je pozastavena.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 802aba696da61be5f0a6c12072842cbc3cd96499
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059632"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a>Byl překročen Limit denní e-mail. Pracovního postupu je pozastavena.

Tato chyba může obdržet v následujících situacích:

- Máte pracovní postup služby SharePoint Online, který používá SharePoint 2010 nebo SharePoint 2013 typ platformy pracovního postupu.
- Pracovní postup je nakonfigurován pro vlastní e-mailové zprávě odeslat více než 200 uživatelů, více než 10 000 příjemců za den, nebo více než 30 zpráv za minutu.
- Při spuštění pracovního postupu není odeslána e-mailové zprávy a zaznamenat následující chování:
    - Pomocí typ platformy SharePoint 2013 pracovního postupu přejděte na stránku **Stav pracovního postupu** . Na stránce Stav pracovního postupu **Vnitřní stav** nastaven na **spuštěno**a zobrazí bublinu informace **nelze odeslat příjemci**.

Chcete-li tento problém vyřešit, nakonfigurujte pracovní postup odeslání e-mailové zprávy bez překročení [limitů Exchange Online odesílatele](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits). Například použití pozastavit v pracovním postupu, odešlete na skupinu služeb Office 365, distribuční skupina nebo skupina zabezpečení povolena poštovní nebo méně než 200 příjemcům najednou odeslat zprávu.


Další informace naleznete v následujícím [článku](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).

## <a name="related-topics"></a>Související témata
- [Vytvoření toku](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint a toku](https://flow.microsoft.com/blog/sharepoint-and-flow/) 