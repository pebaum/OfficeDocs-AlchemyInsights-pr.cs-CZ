---
title: Používání DLP v pravidlech přenosu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5153"
ms.openlocfilehash: 124b031e2e029b745c66a71f681f57134739eafe
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915091"
---
# <a name="using-dlp-in-transport-rules"></a>Používání DLP v pravidlech přenosu

Pokud chcete do existujícího přenosu integrovat ochranu před únikem informací (DLP), v nastavení pravidla přenosu použijte podmínku „**Pokud zpráva obsahuje… citlivé informace**“.

**Podrobnosti viz:**

- Typy citlivých informací integrované DLP v pravidlech přenosu: [Integrace pravidel pro citlivé informace](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/integrate-sensitive-information-rules).

Pravidlo také můžete otestovat pomocí testovacího režimu, a to s testem zásad, nebo bez něj.  Než nově vytvořené pravidlo otestujete, musíte počkat 30 minut.

- Viz článek [Testování pravidel toku pošty / přenosu](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/test-mail-flow-rules).

**Poznámka**: Pokud se pro pravidla přenosu v EAC pokoušíte zavést novou zásadu DLP, použijte místo toho [Zásady DLC v Centru zabezpečení a dodržování předpisů](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies?view=o365-worldwide).
