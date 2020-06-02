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
ms.openlocfilehash: 0acaed476dbd06bc933bf466f9bf6116413a44bb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509377"
---
# <a name="setup-dkim"></a>Nastavení DKIM

Kompletní pokyny pro konfiguraci DKIM pro vlastní domény v Microsoft 365 jsou [zde](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).

1. Pro **každou** vlastní doménu je třeba vytvořit **dva** záznamy DKIM CNAME v hostitelské službě DNS vaší domény (obvykle registrátor domény). Například contoso.com a fourthcoffee.com vyžadují čtyři záznamy DKIM CNAME: dva pro contoso.com a dva pro fourthcoffee.com.

   Záznamy DKIM CNAME pro **každou** vlastní doménu používají následující formáty:

   - **Název hostitele**:`selector1._domainkey.<CustomDomain>`

     **Body na adresu nebo hodnotu**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   - **Název hostitele**:`selector2._domainkey.<CustomDomain>`

     **Body na adresu nebo hodnotu**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   \<DomainGUID\>je text nalevo `.mail.protection.outlook.com` od přizpůsobeného záznamu MX pro vlastní doménu (například `contoso-com` pro doménu contoso.com). \<InitialDomain\>je doména, kterou jste použili při registraci do microsoftu 365 (například contoso.onmicrosoft.com).

2. Po vytvoření záznamů CNAME pro vlastní domény vyplňte následující pokyny:

   a. [přihlaste se k Microsoftu 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomocí svého pracovního nebo školního účtu.

   b. V levém horním rohu vyberte ikonu spouštěče aplikací a zvolte **Správce**.

   c. V levém dolním navigačním panelu **rozbalte Položku Správce** a zvolte **Exchange**.

   D. Přejděte na **Protection**  >  **DKIM**.

   E. Vyberte doménu a pak zvolte **Povolit** **pro podepisování zpráv pro tuto doménu s podpisy DKIM**. Tento krok opakujte pro každou vlastní doménu.
