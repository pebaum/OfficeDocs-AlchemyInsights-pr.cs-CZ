---
title: Odstraňuje problémy doručení e-mailu do poštovní veřejných složek
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e24a4db2deb3f691209a1634d932ed277a79c868
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35387698"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Odstraňuje problémy doručení e-mailu do poštovní veřejných složek

Pokud externích odesílatelů nelze odeslat zprávy do veřejné složky poštovní a odesílatelé zobrazí chybová zpráva: **nebyl nalezen (550 5.4.1)**, ověřte e-mailovou doménu pro veřejné složky je nakonfigurován jako domény vnitřní relay namísto autoritativní domény:

1. Otevřete [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Přejít na **toku pošty** \> **přijaté domény**přijaté domény vyberte a klepněte na tlačítko **Upravit**.

3. Ve vlastnostech stránky otevře, pokud typ domény je nastavena na **autoritativní**, změňte hodnotu na **vnitřní relay** a klepněte na tlačítko **Uložit**.

Pokud externí odesílatelé obdržet chyba **že nemáte oprávnění (550 5.7.13)**, spusťte následující příkaz v [Prostředí Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) Chcete-li zobrazit oprávnění pro anonymní uživatele ve veřejné složce:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Například `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Pokud chcete povolit externí uživatelé odeslat e-mail této veřejné složky, přidejte přístup CreateItems právo na anonymní uživatele. Například `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.
