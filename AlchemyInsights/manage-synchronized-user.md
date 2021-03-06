---
title: Spravovat synchronizované uživatele
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 84e337a7224fdd3c3ab7ad0f61240692fe007d5a
ms.sourcegitcommit: 82af227ac6d075e748e27c4ce6bdcf56628559cb
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/28/2020
ms.locfileid: "44407343"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Nelze nastavit primární e-mailovou adresu, změnit atributy uživatele nebo odebrat nebo odstranit synchronizovaného uživatele.

Pokud je synchronizace adresářů povolena pro vaše prostředí, některé atributy uživatelů nebo objektů nelze změnit pomocí Centra pro správu Microsoft 365.

Chcete-li plně spravovat synchronizované uživatele a všechny jejich atributy, použijte místní uživatele a konzolu pro správu adresářů active directory (adsiedit.msc).  

Případně můžete změnit jednotlivé uživatele nebo atributy pro synchronizované uživatele pomocí prostředí PowerShell, jak je znázorněno v těchto běžných příkladech: 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
