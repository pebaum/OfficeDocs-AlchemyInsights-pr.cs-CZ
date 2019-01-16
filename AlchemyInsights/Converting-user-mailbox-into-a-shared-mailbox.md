---
title: Převod poštovní schránky uživatele na sdílené poštovní schránky?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: 22ad1b3fb818b40bcd77974031735f931e986968
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281979"
---
Pokud uživatel nemá licenci pro Exchange, lze převést pouze poštovní schránky uživatele na sdílené poštovní schránky. Po převedení poštovní schránky bude pokračovat Chcete-li zobrazit v seznamu aktivních uživatelů, protože tento seznam obsahuje sdílené poštovní schránky. Nicméně převedené poštovní schránky se také zobrazí v seznamu sdílené poštovní schránky. 
  
Pokud se pokusíte převést poštovní schránky v konzole pro správu serveru Exchange a převod se nezdaří, vymažte mezipaměť prohlížeče a soubory cookie a akci opakujte. Pokud stále nefunguje, zkuste převést poštovní schránky v prostředí Exchange Management Shell spusťte následující příkaz:
  
```
Set-Mailbox -Type Shared
```

Další informace o převodu poštovní schránka je k dispozici v [Převést poštovní schránky uživatele na sdílené poštovní schránky](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
