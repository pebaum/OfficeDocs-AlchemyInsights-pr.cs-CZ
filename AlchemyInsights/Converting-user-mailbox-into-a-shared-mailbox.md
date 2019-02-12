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
ms.openlocfilehash: 4da54121763fd33aa111f3bb3c26963cd271dc51
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29906725"
---
Pokud uživatel nemá licenci pro Exchange, lze převést pouze poštovní schránky uživatele na sdílené poštovní schránky. Po převedení poštovní schránky bude pokračovat Chcete-li zobrazit v seznamu aktivních uživatelů, protože tento seznam obsahuje sdílené poštovní schránky. Nicméně převedené poštovní schránky se také zobrazí v seznamu sdílené poštovní schránky. 
  
Pokud se pokusíte převést poštovní schránky v konzole pro správu serveru Exchange a převod se nezdaří, vymažte mezipaměť prohlížeče a soubory cookie a akci opakujte. Pokud stále nefunguje, zkuste převést poštovní schránky v prostředí Exchange Management Shell spusťte následující příkaz:
  
```
Set-Mailbox -Type Shared
```

Další informace o převodu poštovní schránka je k dispozici v [Převést poštovní schránky uživatele na sdílené poštovní schránky](https://support.office.com/client/2e122487-e1f5-4f26-ba41-5689249d93ba).
  
