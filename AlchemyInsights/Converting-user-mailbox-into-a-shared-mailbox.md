---
title: Převod poštovní schránky uživatele na sdílené poštovní schránky?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496392"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a>Převést poštovní schránky uživatele na sdílené poštovní schránky

Pokud uživatel nemá licenci pro Exchange, lze převést pouze poštovní schránky uživatele na sdílené poštovní schránky. Po převedení poštovní schránky bude pokračovat Chcete-li zobrazit v seznamu aktivních uživatelů, protože tento seznam obsahuje sdílené poštovní schránky. Nicméně převedené poštovní schránky se také zobrazí v seznamu sdílené poštovní schránky. 
  
Pokud se pokusíte převést poštovní schránky v konzole pro správu serveru Exchange a převod se nezdaří, vymažte mezipaměť prohlížeče a soubory cookie a akci opakujte. Pokud stále nefunguje, zkuste převést poštovní schránky v prostředí Exchange Management Shell spusťte následující příkaz:
  
```
Set-Mailbox -Type Shared
```

Další informace o převodu poštovní schránka je k dispozici v [Převést poštovní schránky uživatele na sdílené poštovní schránky](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).
  
