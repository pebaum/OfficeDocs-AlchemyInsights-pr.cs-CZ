---
title: 618 Zásady sdílení kalendáře
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/26/2020
ms.locfileid: "44372992"
---
# <a name="policy-error-when-sharing-a-calendar"></a>Chyba zásad při sdílení kalendáře

1. Proveďte jednu z následujících akcí podle vaší situace:
    - Připojte se k Exchange Online pomocí vzdáleného prostředí PowerShell. Další informace naleznete [v tématu Připojení k Exchange Online pomocí vzdáleného prostředí PowerShell](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).
    - Na místním serveru otevřete prostředí Exchange Management Shell.
2. Určete zásady sdílení, které jsou přiřazeny uživateli. Chcete-li to provést, spusťte následující příkaz a poznamenejte si vrácenou zásadu:

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. Aktualizujte zásady sdílení pro uživatele. Uděláte to takto:
    - Otevřete Centrum pro správu Exchange.
    - Klikněte na **Organizace**a potom poklikejte na zásadu přiřazenou uživateli v části **Individuální sdílení**. Toto je zásada, která byla vrácena v kroku 2.
    - Na stránce Pravidlo sdílení vyberte úroveň sdílení kalendáře, kterou chcete povolit, v části **Určit informace, které chcete sdílet**; klepněte na **tlačítko Uložit**.

Další informace naleznete v [tématu: "Zásady neumožňují udělení oprávnění na této úrovni jednomu nebo více příjemcům" při pokusu uživatele o sdílení kalendáře](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).
