---
title: 2419nelze na povolení auditování
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 3af01c03711eed646f0009afb5bea685bc358196
ms.sourcegitcommit: 87153fec6f6468b57893abf4aac073ba4068e67b
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/19/2019
ms.locfileid: "35065617"
---
# <a name="unable-to-enable-unified-auditing"></a>Nelze povolit auditování unified

Při pokusu o povolení jednotného auditu pro organizaci služeb Office 365, můžete obdržet chybě podobné následující:

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

Chcete-li tento problém vyřešit, postupujte takto:

1. [Připojení k serveru Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).

2. Spusťte následující rutinu:

   ```
   Enable-OrganizationCustomization
   ```

3. Počkejte, až 60 minut pro předchozí nastavení se projeví.

4. V prostředí serveru Exchange Online PowerShell, spusťte následující příkaz:

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

Další informace naleznete v následujících článcích:

- [Připojení k serveru Exchange Online PowerShell pomocí vícenásobné ověření](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [Vypnutí a zapnutí vyhledávání protokolu auditu služeb Office 365](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)
