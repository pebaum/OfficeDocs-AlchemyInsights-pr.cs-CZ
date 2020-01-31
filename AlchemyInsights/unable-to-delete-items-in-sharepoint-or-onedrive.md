---
title: Nelze odstranit položky v SharePointu nebo OneDrivu.
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: abfcb91c6040aeed759d697ca63546ccea8ede97
ms.sourcegitcommit: c5e800313a6f211386a384716e5fa18e7fcc8c1c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/28/2020
ms.locfileid: "41571235"
---
# <a name="unable-to-delete-items"></a>Nelze odstranit položky.

Zásady uchovávání informací mohou způsobit toto, je třeba zakázat nebo vyloučit příslušné blokování, které je příčinou tohoto problému. Po odebrání zásad uchovávání informací nebo blokování může trvat až 24 hodin, než se změna projeví. Ujistěte se, že není nastavení [zásad uchovávání informací](https://docs.microsoft.com/office365/securitycompliance/retention-policies) pro položku.

Web pravděpodobně překročil limit úložiště, zvýšil [kvótu webu](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) a odstranil položku.

Ujistěte se, že položka není rezervována jinému [uživateli.](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de)

Správci mohou nakonec používat [sharepointové vzory a postupy](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP), která obsahuje knihovnu příkazů prostředí PowerShell, které umožňují provádět složité akce správy, jako je vynucení odstranění tvrdohlavých položek.
- [Odebrání souboru PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Odebrání složky PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Odebrat položku seznamu PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Odebrat seznam PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Odebrat pole PNP (sloupec)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)