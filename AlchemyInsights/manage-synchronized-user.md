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
ms.openlocfilehash: 5a383bdd17c5fa055c35a923ca36e0e0f6d429e4
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35380498"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a>Nepodařilo se nastavit primární e-mailovou adresu nebo změnit atributy uživatele

Pokud je povolena synchronizace adresářů prostředí nelze některé atributy pro objekt uživatele nebo změnit pomocí středisku pro správce.
Ke správě plně synchronizované uživatele a jejich atributy, pomocí vaší místní služby active directory uživatelé a skupiny konzoly Správa (adsiedit.msc).  

Můžete také změnit jednotlivé uživatele nebo pro synchronizované uživatele pomocí prostředí powershell jako zobrazené v těchto příkladech společné atributy: 
- Sada MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com
- Sada MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com" - DisplayName "Zkoušky uživatelské" - Příjmení "Uživatel"-"Správce" hlava-oddělení "HR"
- "User@yourdomain.onmicrosoft.com odebrat MsolUser - UserPrincipalName