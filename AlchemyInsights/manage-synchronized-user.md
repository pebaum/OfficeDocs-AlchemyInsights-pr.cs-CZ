---
title: Spravovat uživatele synchronizovány
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
ms.openlocfilehash: a943c59d67c512e6326856dacd0053db121f6aa3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36541977"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a>Nepodařilo se nastavit primární e-mailovou adresu nebo změnit atributy uživatele

Pokud je synchronizace adresářů povoleno prostředí, nelze některé atributy pro objekt uživatele nebo změnit pomocí středisku pro správce služeb Microsoft 365.

Ke správě plně synchronizované uživatele a jejich atributy, pomocí vaší místní služby active directory uživatelé a skupiny konzoly Správa (adsiedit.msc).  

Můžete také změnit jednotlivé uživatele nebo pro synchronizované uživatele pomocí prostředí powershell jako zobrazené v těchto příkladech společné atributy: 
- Sada MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com
- Sada MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com" - DisplayName "Zkoušky uživatelské" - Příjmení "Uživatel"-"Správce" hlava-oddělení "HR"
- "User@yourdomain.onmicrosoft.com odebrat MsolUser - UserPrincipalName