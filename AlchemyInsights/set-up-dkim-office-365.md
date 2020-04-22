---
title: Nastavení DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: d23a816d4eef065f800eaee60829d57dc1e7177f
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/21/2020
ms.locfileid: "43645665"
---
# <a name="setup-dkim"></a>Nastavení DKIM

Úplné pokyny pro konfiguraci DKIM pro vlastní domény v Microsoft 365 jsou [zde](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

1. Pro **každou** vlastní doménu je třeba vytvořit **dva** záznamy DKIM CNAME v hostitelské službě DNS vaší domény (obvykle registrátor domény). Například contoso.com a fourthcoffee.com vyžadují čtyři záznamy DKIM CNAME: dva pro contoso.com a dva pro fourthcoffee.com.

   Záznamy DKIM CNAME pro **každou** vlastní doménu používají následující formáty:

   - **Název hostitele**:`selector1._domainkey.<CustomDomain>`

     **Body na adresu nebo hodnotu**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   - **Název hostitele**:`selector2._domainkey.<CustomDomain>`

     **Body na adresu nebo hodnotu**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   \<DomainGUID\> je text nalevo od `.mail.protection.outlook.com` v přizpůsobeném záznamu MX `contoso-com` pro vlastní doménu (například pro doménu contoso.com). \<InitialDomain\> je doména, kterou jste použili při registraci do Microsoftu 365 (například contoso.onmicrosoft.com).

2. Po vytvoření záznamů CNAME pro vlastní domény postupujte podle následujících pokynů:

   A. [Přihlaste se k Microsoftu 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomocí pracovního nebo školního účtu.

   B. V levém horním rohu vyberte ikonu spouštěče aplikací a zvolte **Správce**.

   C. V levém dolním navigačním panelu rozbalte **položku Správce** a zvolte **Exchange**.

   D. Přejděte na **ochranu** > **DKIM**.

   E. Vyberte doménu a pak zvolte **Povolit** pro **podepisování zpráv pro tuto doménu s podpisy DKIM**. Tento krok opakujte pro každou vlastní doménu.
