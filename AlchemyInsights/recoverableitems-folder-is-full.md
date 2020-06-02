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
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="905d9-102">Složka Obnovitelné položky je plná.</span><span class="sxs-lookup"><span data-stu-id="905d9-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="905d9-103">U poštovních schránek Exchange Online je výchozí limit úložiště pro složku Obnovitelné položky 30 GB.</span><span class="sxs-lookup"><span data-stu-id="905d9-103">For Exchange Online mailboxes, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="905d9-104">Limit úložiště pro složku Obnovitelné položky se automaticky zvýší na 100 GB, pokud je poštovní schránka umístěna na blokování z důvodu soudních sporů, blokování eDiscovery nebo je přiřazena k zásadám uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="905d9-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to a retention policy.</span></span>

<span data-ttu-id="905d9-105">Když složka Obnovitelné položky dosáhne limitu úložiště, funkce poštovní schránky je ovlivněna následujícími způsoby:</span><span class="sxs-lookup"><span data-stu-id="905d9-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>

- <span data-ttu-id="905d9-106">Uživatel nemůže odstranit položky z poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="905d9-106">The user can't delete items from the mailbox.</span></span>

- <span data-ttu-id="905d9-107">Pomocník pro spravované složky nemůže odstranit položky na základě značky uchovávání informací nebo nastavení spravované složky.</span><span class="sxs-lookup"><span data-stu-id="905d9-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>

- <span data-ttu-id="905d9-108">U poštovních schránek, které mají povoleno obnovení jedné položky nebo jsou blokování, proces ochrany stránky kopírování při zápisu nemůže udržovat verze položek upravených uživatelem.</span><span class="sxs-lookup"><span data-stu-id="905d9-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>

- <span data-ttu-id="905d9-109">U poštovních schránek s povoleným protokolováním auditu poštovní schránky nelze v podsložce Auditovat položky v složce Obnovitelné položky uložit žádné položky protokolu auditu poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="905d9-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>

<span data-ttu-id="905d9-110">U poštovních schránek, které nejsou přidržené, můžou správci pomocí `Search-Mailbox -SearchDumpsterOnly -DeleteContent` příkazu v Exchange Online PowerShellu odstranit položky ve složce Obnovitelné položky.</span><span class="sxs-lookup"><span data-stu-id="905d9-110">For mailboxes that aren't on hold, admins can use the `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="905d9-111">Další informace najdete v těchto tématech:</span><span class="sxs-lookup"><span data-stu-id="905d9-111">For more information, see the following topics:</span></span>

- [<span data-ttu-id="905d9-112">Hledání a odstraňování zpráv</span><span class="sxs-lookup"><span data-stu-id="905d9-112">Search for and delete messages</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [<span data-ttu-id="905d9-113">Vyhledávací poštovní schránka</span><span class="sxs-lookup"><span data-stu-id="905d9-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

<span data-ttu-id="905d9-114">U poštovních schránek, které jsou pozastaveny, musí správci odebrat blokování, než budou moci odstranit položky ze složky Obnovitelné položky.</span><span class="sxs-lookup"><span data-stu-id="905d9-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="905d9-115">Další informace naleznete [v tématu Odstranění položek ve složce Obnovitelné položky v blokování cloudových poštovních schránek](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="905d9-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>

<span data-ttu-id="905d9-116">Aby se zabránilo zaplnění složky Obnovitelné položky, mohou správci zvýšit limit úložiště složky Obnovitelné položky pro pozastavené poštovní schránky a nastavit zásady uchovávání informací poštovní schránky, které přesunou položky ze složky Obnovitelné položky do archivní poštovní schránky uživatele.</span><span class="sxs-lookup"><span data-stu-id="905d9-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="905d9-117">Viz [Zvýšení kvóty obnovitelné položky pro poštovní schránky v blokování](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="905d9-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
