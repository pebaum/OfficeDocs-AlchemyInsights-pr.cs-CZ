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
ms.openlocfilehash: af9a0bd8ff4294575ac68f37d4997bb50b132ce7
ms.sourcegitcommit: 9ab422063e5a474c92ed956d42d222b90336fecb
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2020
ms.locfileid: "42600355"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a>Vyřazení starších nástrojů eDiscovery

V důsledku nové a vylepšené funkce eDiscovery v Centru dodržování předpisů Microsoftu 365 budou v nadcházejících měsících vyřazeny následující starší nástroje a příkazy eDiscovery:

- [Místní eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) a [místní blokování v](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) Centru pro správu Exchange.

- Rutiny prostředí Exchange Online PowerShell, které podporují místní eDiscovery a místní blokování. (Tyto rutiny jsou souhrnně identifikovány jako rutiny *-MailboxSearch.) To zahrnuje následující rutiny:

    - [Nové poštovní schránkyHledání](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [Hledání start-poštovní schránky](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [Stop-MailboxHledání](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [Set-MailboxHledání](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- Rutina [Vyhledávací poštovní schránka](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) v prostředí Exchange Online PowerShell.
- Následující operace v rozhraní API webových služeb exchange:
    - [GetSearchablePoštovní schránky](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [Schránky SetHoldOnMailboxes](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [Schránky GetHoldOnMailboxes](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [Office 365 Advanced eDiscovery v1.0](https://docs.microsoft.com/microsoft-365/compliance/office-365-advanced-ediscovery)

**Časová osa odchodu do důchodu**:
- 1. dubna 2020: Nebudete moci vytvářet nová hledání a blokování, ale stále můžete spouštět, upravovat a odstraňovat stávající hledání na vlastní nebezpečí. Podpora společnosti Microsoft již nebude podporovat místní zjišťování eDiscovery & blokování v EAC.

- 1. července 2020: Funkce Na místě, & eDiscovery, bude v EAC umístěna do režimu jen pro čtení. To znamená, že budete moci odebrat pouze existující vyhledávání a blokování.

**Další informace naleznete v tématu**:

 - [Migrace starších vyhledávání eDiscovery a jejich držení do Centra dodržování předpisů Microsoftu 365](https://docs.microsoft.com/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [Vyřazení starších nástrojů eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [Časté otázky týkající se místního zjišťování eDiscovery a místních blokování](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)



