---
title: Nástroj pro export eDiscovery
ms.author: pebaum
author: pebaum
manager: mnirkhe
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
ms.openlocfilehash: 6352603a391ddcb44d2728c7587bf15a6cd97ebb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507163"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>Nelze nainstalovat nebo spustit nástroj eDiscovery Export Tool?

Pokud nemůžete nainstalovat nebo spustit nástroj eDiscovery Export Tool ke stažení výsledků hledání, zkontrolujte následující věci:
  
- Počítač, který používáte, splňuje tyto předpoklady:

  - 32bitové nebo 64bitové verze Windows 7 a novějších verzí

  - Microsoft .NET Framework 4.7

  - Podporovaný prohlížeč:

  - Microsoft Edge

    Nebo

  - Internet Explorer 10 a novější verze

    Ostatní prohlížeče, jako je Google Chrome a Mozilla Firefox, nejsou podporovány.

- Vaše organizace se může připojit ke koncovému bodu v Azure, což je ** \* .blob.core.windows.net** (zástupný znak představuje jedinečný identifikátor pro vaši úlohu exportu).

- Máte přiřazenou roli Export v Centru dodržování předpisů zabezpečení Microsoft 365. &amp; Ve výchozím nastavení je tato role přiřazena pouze skupině rolí správce eDiscovery. Viz [Přiřazení oprávnění eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions).

Další informace naleznete v tématu [Exportovat výsledky hledání obsahu](https://docs.microsoft.com/microsoft-365/compliance/export-search-results).
  