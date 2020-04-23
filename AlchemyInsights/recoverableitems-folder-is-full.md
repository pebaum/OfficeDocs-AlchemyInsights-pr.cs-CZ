---
title: 1336 RecoverableItems složka je plná
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: fb10b792981040bdcf4661b8aff30733c2438212
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720245"
---
# <a name="the-recoverable-items-folder-is-full"></a>Složka Obnovitelné položky je plná.

U poštovních schránek Exchange Online je výchozí limit úložiště pro složku Obnovitelné položky 30 GB. Limit úložiště pro složku Obnovitelné položky se automaticky zvýší na 100 GB, pokud je poštovní schránka umístěna do blokování z důvodu soudních sporů, blokování eDiscovery nebo je přiřazena k zásadám uchovávání informací.

Když složka Obnovitelné položky dosáhne limitu úložiště, funkce poštovní schránky jsou ovlivněny následujícími způsoby:

- Uživatel nemůže odstranit položky z poštovní schránky.

- Pomocník pro správu složek nemůže odstranit položky na základě nastavení značky uchování nebo spravovaných složek.

- U poštovních schránek, které mají povolenou nebo jsou pozastaveny obnovení jedné položky, nemůže proces ochrany stránky při zápisu udržovat verze položek upravovaných uživatelem.

- U poštovních schránek, které mají povoleno protokolování auditu poštovní schránky, nelze do podsložky Audity ve složce Obnovitelné položky uložit žádné položky protokolu auditování poštovní schránky.

U poštovních schránek, které nejsou `Search-Mailbox -SearchDumpsterOnly -DeleteContent` pozastavené, můžou správci pomocí příkazu v prostředí Exchange Online PowerShell odstranit položky ve složce Obnovitelné položky. Další informace najdete v těchto tématech:

- [Hledání a odstraňování zpráv](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [Hledat-Poštovní schránka](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

U poštovních schránek, které jsou v blokování, musí správci před odstraněním položek ze složky Obnovitelné položky blokování odebrat. Další informace naleznete [v tématu Odstranění položek ve složce Obnovitelné položky v přijím na eblacích poštovních schránek](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Chcete-li zabránit tomu, aby se složka Obnovitelné položky stala plnou, mohou správci zvýšit limit úložiště složky Obnovitelné položky pro poštovní schránky, která je v režimu blokování, a nastavit zásady uchovávání informací poštovní schránky, které přesouvají položky ze složky Obnovitelné položky do archivní poštovní schránky uživatele. Viz [Zvýšení kvóty obnovitelné položky pro poštovní schránky v blokování](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
