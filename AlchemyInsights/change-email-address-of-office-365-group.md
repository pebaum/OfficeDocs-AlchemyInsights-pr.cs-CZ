---
title: Změna e-mailové adresy skupiny Microsoft 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 0a07e6279f533a4c26a4e90c10651421a5df8860
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/27/2020
ms.locfileid: "44282712"
---
# <a name="change-email-address-of-an-microsoft-365-group"></a>Změna e-mailové adresy skupiny Microsoft 365

E-mailovou adresu skupiny Microsoft 365 můžete změnit pomocí Centra pro správu. Stačí vybrat skupinu a vybrat @edit e-mailovou adresu.

Pomocí následujícího příkazu EXO PowerShell můžete také změnit primární adresu SMTP skupiny Microsoft 365:

Set-UnifiedGroup <Group Name> -PrimárníAdresa SMTP<new SMTP Address>

Příklad:

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
