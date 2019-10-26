---
title: Nástroj pro export eDiscovery
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 8/3/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 5a54344d43d16c77d440768aa1c87489edf10ca0
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36736318"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>Nelze nainstalovat nebo spustit nástroj pro export systému eDiscovery?

Pokud nemůžete nainstalovat nebo spustit nástroj Office 365 eDiscovery export pro stahování výsledků hledání, zkontrolujte následující skutečnosti:
  
- Počítač, který používáte, splňuje tyto požadavky:

  - 32-nebo 64-bitové verze systému Windows 7 a novější verze

  - Rozhraní Microsoft .NET Framework 4,7

  - Podporovaný prohlížeč:

  - Hrana společnosti Microsoft

    Nebo

  - Internet Explorer 10 a novější verze

    Jiné prohlížeče, například Google Chrome a Mozilla Firefox, nejsou podporovány.

- Vaše organizace se může připojit ke koncovému bodu v Azure, což je ** \*. blob.Core.Windows.NET** (zástupný znak představuje jedinečný identifikátor pro vaši úlohu exportu).

- Máte přiřazenu roli exportu v centru pro dodržování zabezpečení &amp; Office 365. Ve výchozím nastavení je tato role přiřazena pouze ke skupině rolí správce eDiscovery. Viz [přiřazení oprávnění eDiscovery](https://docs.microsoft.com/office365/securitycompliance/assign-ediscovery-permissions).

Další informace viz [Export výsledků hledání obsahu](https://docs.microsoft.com/office365/securitycompliance/export-search-results).
  