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
ms.openlocfilehash: 739e9d91f90e4c0374814d199e4372eb5625553a
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158593"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Pro dávku migrace veřejných složek se stavem CompletedWithErrors

K dokončení dávky použijte následující kroky a přeskočení velkých/chybových položek: 
1. Schválit přeskočené položky v migrační dávce:

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. Pomocí následujícího příkazu můžete schválit přeskočené položky v požadavcích na migraci, které jsou "Synchronizované", ale nejsou dokončeny:

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. Migrační dávka a požadavky by měly pokračovat a dokončeny během několika minut.

