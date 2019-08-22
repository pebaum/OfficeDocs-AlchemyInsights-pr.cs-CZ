---
title: Žádné výsledky vyhledávání obsahu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000661"
- "2527"
ms.openlocfilehash: 09cdbc3cb0465e0e0bc08872c49e283081ad3e92
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36516772"
---
# <a name="no-results-from-content-searchexports"></a><span data-ttu-id="6a6ae-102">Žádné výsledky z obsahu hledání vývozu a</span><span class="sxs-lookup"><span data-stu-id="6a6ae-102">No results from Content Search/Exports</span></span>

<span data-ttu-id="6a6ae-103">Problémy s obsahu hledání vývozu a ne vrátí všechna data mohou být určité shody zabezpečení filtr, který byl nastavení konkrétní Admin a není sdělování všech Admins.</span><span class="sxs-lookup"><span data-stu-id="6a6ae-103">Issues with Content Search/Exports not returning any data may be due to certain Compliance Security Filter that was setup by a specific Admin and not communicating it to all Admins.</span></span>

<span data-ttu-id="6a6ae-104">Tento problém vyřešíte, zkontrolujte, pokud jsou všechny filtry zabezpečení shody, který může být příčinou to:</span><span class="sxs-lookup"><span data-stu-id="6a6ae-104">To resolve this, check to see if there are any Compliance Security Filters that may be causing this:</span></span>
1. <span data-ttu-id="6a6ae-105">Připojte se k zabezpečení a Powershell centra kompatibility</span><span class="sxs-lookup"><span data-stu-id="6a6ae-105">Connect to Security and Compliance Center Powershell</span></span>
2. <span data-ttu-id="6a6ae-106">Spusťte tyto commandlets:</span><span class="sxs-lookup"><span data-stu-id="6a6ae-106">Run the following commandlets:</span></span>
<br><span data-ttu-id="6a6ae-107">$org = "yourdomain.com"</span><span class="sxs-lookup"><span data-stu-id="6a6ae-107">$org = “yourdomain.com”</span></span>
<br><span data-ttu-id="6a6ae-108">Get-ComplianceSecurityFilter-$org organizace</span><span class="sxs-lookup"><span data-stu-id="6a6ae-108">Get-ComplianceSecurityFilter -Organization $org</span></span>