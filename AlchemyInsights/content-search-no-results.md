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
# <a name="no-results-from-content-searchexports"></a>Žádné výsledky z obsahu hledání vývozu a

Problémy s obsahu hledání vývozu a ne vrátí všechna data mohou být určité shody zabezpečení filtr, který byl nastavení konkrétní Admin a není sdělování všech Admins.

Tento problém vyřešíte, zkontrolujte, pokud jsou všechny filtry zabezpečení shody, který může být příčinou to:
1. Připojte se k zabezpečení a Powershell centra kompatibility
2. Spusťte tyto commandlets:
<br>$org = "yourdomain.com"
<br>Get-ComplianceSecurityFilter-$org organizace