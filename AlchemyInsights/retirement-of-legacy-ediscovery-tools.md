---
title: Vyřazení starších nástrojů eDiscovery
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: c4632b52dde579b7d5b2e6e15f1583300a0bd136
ms.sourcegitcommit: a7c17217c170ead24571421baaf5a14f1525b1a6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/20/2020
ms.locfileid: "42157540"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a>Vyřazení starších nástrojů eDiscovery

V důsledku nových a vylepšených funkcí eDiscovery v Centru dodržování předpisů microsoftu 365 budou v nadcházejících měsících vyřazeny následující starší nástroje a příkazy eDiscovery:

- [Na místě eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) a [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) v Centru pro správu Exchange.

- Rutiny PowerShellu Exchange Online, které podporují eDiscovery a blokování na místě. (Tyto rutiny jsou souhrnně označeny jako *-MailboxSearch rutiny.) To zahrnuje následující rutiny:

    - [Hledání nové poštovní schránky](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [Spuštění poštovní schránkyHledat](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [Stop-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [Set-MailboxSearch](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- Rutina [vyhledávací poštovní schránky](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) v powershellu Exchange Online.
- Následující operace v rozhraní API webové služby Exchange:
    - [GetSearchablePoštovní schránky](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [SetHoldOnMailboxes](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [GetHoldOnPoštovní schránky](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [Office 365 Advanced eDiscovery v1.0](https://docs.microsoft.com/en-us/microsoft-365/compliance/office-365-advanced-ediscovery)

**Časová osa odchodu do důchodu**:
- 1. dubna 2020: Nebudete moci vytvářet nová hledání a blokování, ale stále můžete spouštět, upravovat a odstraňovat stávající vyhledávání na vlastní nebezpečí. Podpora společnosti Microsoft již nebude podporovat místní eDiscovery & drží v EAC.

- 1. července 2020: Funkce eDiscovery & funkce na místě v EAC budou umístěny v režimu jen pro čtení. To znamená, že budete moci odebrat pouze existující vyhledávání a blokování.

**Další informace naleznete v tématu**:

 - [Migrace starších vyhledávání eDiscovery a blokování do Centra dodržování předpisů Microsoft 365](https://docs.microsoft.com/en-us/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [Vyřazení starších nástrojů eDiscovery](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [Časté otázky týkající se místního eDiscovery a blokování na místě](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)



