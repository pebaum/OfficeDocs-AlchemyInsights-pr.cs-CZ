---
title: Pro dávku migrace veřejných složek se stavem CompletedWithErrors
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3532"
ms.openlocfilehash: 4243cdf0170fed1eadac6560d2a04e1a861c63e5
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/15/2020
ms.locfileid: "42043575"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="ffe0a-102">Pro dávku migrace veřejných složek se stavem CompletedWithErrors</span><span class="sxs-lookup"><span data-stu-id="ffe0a-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="ffe0a-103">K dokončení dávky použijte následující kroky a přeskočení velkých/chybových položek:</span><span class="sxs-lookup"><span data-stu-id="ffe0a-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="ffe0a-104">Schválit přeskočené položky v migrační dávce:</span><span class="sxs-lookup"><span data-stu-id="ffe0a-104">Approve the skipped items on migration batch:</span></span>

    <span data-ttu-id="ffe0a-105">Dávkový název \<set-migrationbatch> -ApproveSkippedItems</span><span class="sxs-lookup"><span data-stu-id="ffe0a-105">Set-MigrationBatch \<batchname> -ApproveSkippedItems</span></span> 
2. <span data-ttu-id="ffe0a-106">Pomocí následujícího příkazu můžete schválit přeskočené položky v požadavcích na migraci, které jsou "Synchronizované", ale nejsou dokončeny:</span><span class="sxs-lookup"><span data-stu-id="ffe0a-106">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    <span data-ttu-id="ffe0a-107">$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i v $pf) {if ($i.LargeItemsEncountered -gt 0 -nebo $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]:UtcNow)}}</span><span class="sxs-lookup"><span data-stu-id="ffe0a-107">$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}</span></span>
3. <span data-ttu-id="ffe0a-108">Migrační dávka a požadavky by měly pokračovat a dokončeny během několika minut.</span><span class="sxs-lookup"><span data-stu-id="ffe0a-108">The migration batch and requests should resume and complete in a few minutes.</span></span>

