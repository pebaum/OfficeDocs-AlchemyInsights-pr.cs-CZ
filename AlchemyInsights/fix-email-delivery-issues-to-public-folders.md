---
title: Řešení problémů s doručováním e-mailů do veřejných složek s povoleným poštou
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e261fe60843555fa45927b0a6b36e1ccf79fb028
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716345"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Řešení problémů s doručováním e-mailů do veřejných složek s povoleným poštou

Pokud externí odesílatelé nemohou odesílat zprávy do veřejných složek s podporou pošty a odesílatelům se zobrazí chyba: **nelze najít (550 5.4.1),** ověřte, zda je e-mailová doména pro veřejnou složku nakonfigurována jako interní přenosová doména namísto autoritativní domény:

1. Otevřete [Centrum pro správu Exchange (EAC).](https://docs.microsoft.com/Exchange/exchange-admin-center)

2. Přejděte na Přijaté domény **toku** \> **pošty**, vyberte přijatou doménu a klepněte na tlačítko **Upravit**.

3. Pokud je typ domény nastaven na **autoritativní**, změňte na stránce vlastností, která se otevře, změňte hodnotu na **Interní přenos** a klepněte na tlačítko **Uložit**.

Pokud se externím odesílatelům zobrazí **chyba, ke které nemáte oprávnění (550 5.7.13),** spusťte v [prostředí Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) následující příkaz, abyste viděli oprávnění pro anonymní uživatele ve veřejné složce:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Například `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Chcete-li externím uživatelům povolit odesílání e-mailů do této veřejné složky, přidejte uživatelskému uživateli anonymní přístupové právo CreateItems. Například `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.
