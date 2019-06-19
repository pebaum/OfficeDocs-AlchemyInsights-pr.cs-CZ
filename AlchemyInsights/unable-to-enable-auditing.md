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
# <a name="unable-to-enable-unified-auditing"></a><span data-ttu-id="82365-102">Nelze povolit auditování unified</span><span class="sxs-lookup"><span data-stu-id="82365-102">Unable to enable unified auditing</span></span>

<span data-ttu-id="82365-103">Při pokusu o povolení jednotného auditu pro organizaci služeb Office 365, můžete obdržet chybě podobné následující:</span><span class="sxs-lookup"><span data-stu-id="82365-103">When you try to enable unified auditing for your Office 365 organization, you may receive an error similar the following:</span></span>

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

<span data-ttu-id="82365-104">Chcete-li tento problém vyřešit, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="82365-104">To resolve this issue, follow these steps:</span></span>

1. <span data-ttu-id="82365-105">[Připojení k serveru Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span><span class="sxs-lookup"><span data-stu-id="82365-105">[Connect to Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="82365-106">Spusťte následující rutinu:</span><span class="sxs-lookup"><span data-stu-id="82365-106">Run the following cmdlet:</span></span>

   ```
   Enable-OrganizationCustomization
   ```

3. <span data-ttu-id="82365-107">Počkejte, až 60 minut pro předchozí nastavení se projeví.</span><span class="sxs-lookup"><span data-stu-id="82365-107">Wait for 60 minutes for the previous setting to take effect.</span></span>

4. <span data-ttu-id="82365-108">V prostředí serveru Exchange Online PowerShell, spusťte následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="82365-108">Run the following command in Exchange Online PowerShell:</span></span>

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

<span data-ttu-id="82365-109">Další informace naleznete v následujících článcích:</span><span class="sxs-lookup"><span data-stu-id="82365-109">For additional information, see the following articles:</span></span>

- [<span data-ttu-id="82365-110">Připojení k serveru Exchange Online PowerShell pomocí vícenásobné ověření</span><span class="sxs-lookup"><span data-stu-id="82365-110">Connect to Exchange Online PowerShell using multi-factor authentication</span></span>](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [<span data-ttu-id="82365-111">Vypnutí a zapnutí vyhledávání protokolu auditu služeb Office 365</span><span class="sxs-lookup"><span data-stu-id="82365-111">Turn Office 365 audit log search on or off</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)
