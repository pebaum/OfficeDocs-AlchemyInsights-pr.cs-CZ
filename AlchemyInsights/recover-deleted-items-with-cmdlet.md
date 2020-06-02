---
title: Obnovení odstraněných položek pomocí rutiny
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800008"
- "5718"
ms.openlocfilehash: 86744d92a44096991079d1da3bdf4e95e58c55b7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/26/2020
ms.locfileid: "44492958"
---
# <a name="recover-deleted-items-with-cmdlet"></a><span data-ttu-id="f461b-102">Obnovení odstraněných položek pomocí rutiny</span><span class="sxs-lookup"><span data-stu-id="f461b-102">Recover deleted items with cmdlet</span></span>

- <span data-ttu-id="f461b-103">Pomocí rutiny [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) zobrazte odstraněné položky v poštovních schránkách.</span><span class="sxs-lookup"><span data-stu-id="f461b-103">Use the [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) cmdlet to view deleted items in mailboxes.</span></span> <span data-ttu-id="f461b-104">Po nalezení odstraněných položek, použijte [obnovit a obnovititemy rutiny](https://docs.microsoft.com/powershell/module/exchange/Restore-RecoverableItems?view=exchange-ps) k jejich obnovení.</span><span class="sxs-lookup"><span data-stu-id="f461b-104">After you find the deleted items, you use the [Restore-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/Restore-RecoverableItems?view=exchange-ps) cmdlet to restore them.</span></span>

- <span data-ttu-id="f461b-105">Viz úplné podrobnosti v [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="f461b-105">See full details in [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps).</span></span>

- <span data-ttu-id="f461b-106">Před spuštěním této rutiny je nutné přiřadit roli exportu importu poštovních schránek.</span><span class="sxs-lookup"><span data-stu-id="f461b-106">You need to be assigned the Mailbox Import Export role before you can run this cmdlet.</span></span> <span data-ttu-id="f461b-107">Další informace naleznete v [tématu Get-RecoverableItems.](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps)</span><span class="sxs-lookup"><span data-stu-id="f461b-107">Please see [Get-RecoverableItems](https://docs.microsoft.com/powershell/module/exchange/get-recoverableitems?view=exchange-ps) for more information.</span></span>
