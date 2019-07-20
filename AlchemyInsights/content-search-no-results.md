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
ms.openlocfilehash: 9f2c0273762f1a4a2b905487f461dc1d05db9209
ms.sourcegitcommit: 8f97342d8b46ab05f1e89018473caad9d35431df
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/19/2019
ms.locfileid: "35800250"
---
# <a name="no-results-from-content-searchexports"></a>Žádné výsledky z obsahu hledání vývozu a

Problémy s obsahu hledání vývozu a ne vrátí všechna data mohou být určité shody zabezpečení filtr, který byl nastavení konkrétní Admin a není sdělování všech Admins.

Tento problém vyřešíte, zkontrolujte, pokud jsou všechny filtry zabezpečení shody, který může být příčinou to:
1. Připojte se k zabezpečení a Powershell centra kompatibility
2. Spusťte tyto commandlets:
<br>$org = "yourdomain.com"
<br>Get-ComplianceSecurityFilter-$org organizace