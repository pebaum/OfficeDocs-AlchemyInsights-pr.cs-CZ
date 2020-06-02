---
title: 1336 Obnovitelné Položky Složka je plná
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
ms.openlocfilehash: 4f0cba480fcc05114abd8f370b84e9a37e5f2804
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510745"
---
# <a name="the-recoverable-items-folder-is-full"></a>Složka Obnovitelné položky je plná.

U poštovních schránek Exchange Online je výchozí limit úložiště pro složku Obnovitelné položky 30 GB. Limit úložiště pro složku Obnovitelné položky se automaticky zvýší na 100 GB, pokud je poštovní schránka umístěna na blokování z důvodu soudních sporů, blokování eDiscovery nebo je přiřazena k zásadám uchovávání informací.

Když složka Obnovitelné položky dosáhne limitu úložiště, funkce poštovní schránky je ovlivněna následujícími způsoby:

- Uživatel nemůže odstranit položky z poštovní schránky.

- Pomocník pro spravované složky nemůže odstranit položky na základě značky uchovávání informací nebo nastavení spravované složky.

- U poštovních schránek, které mají povoleno obnovení jedné položky nebo jsou blokování, proces ochrany stránky kopírování při zápisu nemůže udržovat verze položek upravených uživatelem.

- U poštovních schránek s povoleným protokolováním auditu poštovní schránky nelze v podsložce Auditovat položky v složce Obnovitelné položky uložit žádné položky protokolu auditu poštovní schránky.

U poštovních schránek, které nejsou přidržené, můžou správci pomocí `Search-Mailbox -SearchDumpsterOnly -DeleteContent` příkazu v Exchange Online PowerShellu odstranit položky ve složce Obnovitelné položky. Další informace najdete v těchto tématech:

- [Hledání a odstraňování zpráv](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [Vyhledávací poštovní schránka](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

U poštovních schránek, které jsou pozastaveny, musí správci odebrat blokování, než budou moci odstranit položky ze složky Obnovitelné položky. Další informace naleznete [v tématu Odstranění položek ve složce Obnovitelné položky v blokování cloudových poštovních schránek](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).

Aby se zabránilo zaplnění složky Obnovitelné položky, mohou správci zvýšit limit úložiště složky Obnovitelné položky pro pozastavené poštovní schránky a nastavit zásady uchovávání informací poštovní schránky, které přesunou položky ze složky Obnovitelné položky do archivní poštovní schránky uživatele. Viz [Zvýšení kvóty obnovitelné položky pro poštovní schránky v blokování](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
