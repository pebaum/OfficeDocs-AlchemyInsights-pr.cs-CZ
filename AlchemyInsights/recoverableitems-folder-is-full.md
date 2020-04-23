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
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="9da11-102">Složka Obnovitelné položky je plná.</span><span class="sxs-lookup"><span data-stu-id="9da11-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="9da11-103">U poštovních schránek Exchange Online je výchozí limit úložiště pro složku Obnovitelné položky 30 GB.</span><span class="sxs-lookup"><span data-stu-id="9da11-103">For Exchange Online mailboxes, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="9da11-104">Limit úložiště pro složku Obnovitelné položky se automaticky zvýší na 100 GB, pokud je poštovní schránka umístěna do blokování z důvodu soudních sporů, blokování eDiscovery nebo je přiřazena k zásadám uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="9da11-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to a retention policy.</span></span>

<span data-ttu-id="9da11-105">Když složka Obnovitelné položky dosáhne limitu úložiště, funkce poštovní schránky jsou ovlivněny následujícími způsoby:</span><span class="sxs-lookup"><span data-stu-id="9da11-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>

- <span data-ttu-id="9da11-106">Uživatel nemůže odstranit položky z poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="9da11-106">The user can't delete items from the mailbox.</span></span>

- <span data-ttu-id="9da11-107">Pomocník pro správu složek nemůže odstranit položky na základě nastavení značky uchování nebo spravovaných složek.</span><span class="sxs-lookup"><span data-stu-id="9da11-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>

- <span data-ttu-id="9da11-108">U poštovních schránek, které mají povolenou nebo jsou pozastaveny obnovení jedné položky, nemůže proces ochrany stránky při zápisu udržovat verze položek upravovaných uživatelem.</span><span class="sxs-lookup"><span data-stu-id="9da11-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>

- <span data-ttu-id="9da11-109">U poštovních schránek, které mají povoleno protokolování auditu poštovní schránky, nelze do podsložky Audity ve složce Obnovitelné položky uložit žádné položky protokolu auditování poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="9da11-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>

<span data-ttu-id="9da11-110">U poštovních schránek, které nejsou `Search-Mailbox -SearchDumpsterOnly -DeleteContent` pozastavené, můžou správci pomocí příkazu v prostředí Exchange Online PowerShell odstranit položky ve složce Obnovitelné položky.</span><span class="sxs-lookup"><span data-stu-id="9da11-110">For mailboxes that aren't on hold, admins can use the `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="9da11-111">Další informace najdete v těchto tématech:</span><span class="sxs-lookup"><span data-stu-id="9da11-111">For more information, see the following topics:</span></span>

- [<span data-ttu-id="9da11-112">Hledání a odstraňování zpráv</span><span class="sxs-lookup"><span data-stu-id="9da11-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)

- [<span data-ttu-id="9da11-113">Hledat-Poštovní schránka</span><span class="sxs-lookup"><span data-stu-id="9da11-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

<span data-ttu-id="9da11-114">U poštovních schránek, které jsou v blokování, musí správci před odstraněním položek ze složky Obnovitelné položky blokování odebrat.</span><span class="sxs-lookup"><span data-stu-id="9da11-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="9da11-115">Další informace naleznete [v tématu Odstranění položek ve složce Obnovitelné položky v přijím na eblacích poštovních schránek](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="9da11-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>

<span data-ttu-id="9da11-116">Chcete-li zabránit tomu, aby se složka Obnovitelné položky stala plnou, mohou správci zvýšit limit úložiště složky Obnovitelné položky pro poštovní schránky, která je v režimu blokování, a nastavit zásady uchovávání informací poštovní schránky, které přesouvají položky ze složky Obnovitelné položky do archivní poštovní schránky uživatele.</span><span class="sxs-lookup"><span data-stu-id="9da11-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="9da11-117">Viz [Zvýšení kvóty obnovitelné položky pro poštovní schránky v blokování](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="9da11-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
