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
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="19aa5-102">Vyřazení starších nástrojů eDiscovery</span><span class="sxs-lookup"><span data-stu-id="19aa5-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="19aa5-103">V důsledku nových a vylepšených funkcí eDiscovery v Centru dodržování předpisů microsoftu 365 budou v nadcházejících měsících vyřazeny následující starší nástroje a příkazy eDiscovery:</span><span class="sxs-lookup"><span data-stu-id="19aa5-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="19aa5-104">[Na místě eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) a [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) v Centru pro správu Exchange.</span><span class="sxs-lookup"><span data-stu-id="19aa5-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="19aa5-105">Rutiny PowerShellu Exchange Online, které podporují eDiscovery a blokování na místě.</span><span class="sxs-lookup"><span data-stu-id="19aa5-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="19aa5-106">(Tyto rutiny jsou souhrnně označeny jako \*-MailboxSearch rutiny.) To zahrnuje následující rutiny:</span><span class="sxs-lookup"><span data-stu-id="19aa5-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="19aa5-107">Hledání nové poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="19aa5-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="19aa5-108">Spuštění poštovní schránkyHledat</span><span class="sxs-lookup"><span data-stu-id="19aa5-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="19aa5-109">Stop-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="19aa5-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="19aa5-110">Set-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="19aa5-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="19aa5-111">Rutina [vyhledávací poštovní schránky](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) v powershellu Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="19aa5-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="19aa5-112">Následující operace v rozhraní API webové služby Exchange:</span><span class="sxs-lookup"><span data-stu-id="19aa5-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="19aa5-113">GetSearchablePoštovní schránky</span><span class="sxs-lookup"><span data-stu-id="19aa5-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="19aa5-114">SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="19aa5-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="19aa5-115">GetHoldOnPoštovní schránky</span><span class="sxs-lookup"><span data-stu-id="19aa5-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="19aa5-116">Office 365 Advanced eDiscovery v1.0</span><span class="sxs-lookup"><span data-stu-id="19aa5-116">Office 365 Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="19aa5-117">**Časová osa odchodu do důchodu**:</span><span class="sxs-lookup"><span data-stu-id="19aa5-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="19aa5-118">1. dubna 2020: Nebudete moci vytvářet nová hledání a blokování, ale stále můžete spouštět, upravovat a odstraňovat stávající vyhledávání na vlastní nebezpečí.</span><span class="sxs-lookup"><span data-stu-id="19aa5-118">April 1, 2020: You won't be able to create new searches and holds, but you can still run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="19aa5-119">Podpora společnosti Microsoft již nebude podporovat místní eDiscovery & drží v EAC.</span><span class="sxs-lookup"><span data-stu-id="19aa5-119">Microsoft Support will no longer support In-Place eDiscovery & Holds in the EAC.</span></span>

- <span data-ttu-id="19aa5-120">1. července 2020: Funkce eDiscovery & funkce na místě v EAC budou umístěny v režimu jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="19aa5-120">July 1, 2020: The In-Place eDiscovery & Holds functionality in the EAC will be placed in a read-only mode.</span></span> <span data-ttu-id="19aa5-121">To znamená, že budete moci odebrat pouze existující vyhledávání a blokování.</span><span class="sxs-lookup"><span data-stu-id="19aa5-121">This means you'll only be able to remove existing searches and holds.</span></span>

<span data-ttu-id="19aa5-122">**Další informace naleznete v tématu**:</span><span class="sxs-lookup"><span data-stu-id="19aa5-122">**For more information, see**:</span></span>

 - [<span data-ttu-id="19aa5-123">Migrace starších vyhledávání eDiscovery a blokování do Centra dodržování předpisů Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="19aa5-123">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="19aa5-124">Vyřazení starších nástrojů eDiscovery</span><span class="sxs-lookup"><span data-stu-id="19aa5-124">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="19aa5-125">Časté otázky týkající se místního eDiscovery a blokování na místě</span><span class="sxs-lookup"><span data-stu-id="19aa5-125">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/en-us/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)



