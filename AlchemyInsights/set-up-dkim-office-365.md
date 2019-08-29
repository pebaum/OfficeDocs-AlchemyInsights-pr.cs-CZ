---
title: Nastavení DKIM ve službách Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: dd908db6a4bc1739b3c1cff059387034d67e093d
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666257"
---
# <a name="setup-dkim-in-office-365"></a>Nastavení DKIM ve službách Office 365

Úplné pokyny pro konfiguraci DKIM pro vlastní domény ve službách Office 365 jsou [zde](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).

1. Pro **každou** vlastní doménu je nutné vytvořit **dva** záznamy DKIM CNAME na hostitelské služby DNS vaší domény (obvykle registrátora domény). Například contoso.com a fourthcoffee.com vyžadují čtyři záznamy DKIM CNAME: dvě pro contoso.com a dvě pro fourthcoffee.com.

   Záznamy DKIM CNAME pro **každou** vlastní doménu pomocí následujících formátů:

   - **Název hostitele**:`selector1._domainkey.<CustomDomain>`

     **Body na adresu nebo hodnotu**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   - **Název hostitele**:`selector2._domainkey.<CustomDomain>`

     **Body na adresu nebo hodnotu**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`

     **TTL**: 3600

   \<DomainGUID\> je text vlevo od `.mail.protection.outlook.com` ve vlastní záznam MX pro vlastní domény (například `contoso-com` pro doménu contoso.com). \<InitialDomain\> je doména, který jste použili při registraci služeb Office 365 (například contoso.onmicrosoft.com).

2. Po vytvoření záznamů CNAME pro vaší vlastní domény postupujte podle následujících pokynů:

   na. [Přihlaste se k Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomocí svého účtu pracovní nebo školní účet.

   b. V levém horním rohu vyberte ikonu spouštěče aplikací a zvolte **Správce**.

   c. V levém navigačním **Admin** rozbalte a vyberte **Exchange**.

   d. Přejít na **ochranu** > **DKIM**.

   e. Vyberte doménu a pak zvolte **Povolit** **přihlašovací**zprávy pro tuto doménu s DKIM podpisy. Tento krok opakujte pro každou vlastní doménu.
