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
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Pro dávku migrace veřejných složek se stavem CompletedWithErrors

K dokončení dávky použijte následující kroky a přeskočení velkých/chybových položek: 
1. Schválit přeskočené položky v migrační dávce:

    Dávkový název \<set-migrationbatch> -ApproveSkippedItems 
2. Pomocí následujícího příkazu můžete schválit přeskočené položky v požadavcích na migraci, které jsou "Synchronizované", ale nejsou dokončeny:

    $pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i v $pf) {if ($i.LargeItemsEncountered -gt 0 -nebo $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]:UtcNow)}}
3. Migrační dávka a požadavky by měly pokračovat a dokončeny během několika minut.

