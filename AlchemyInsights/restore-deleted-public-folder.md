---
title: Obnovení odstraněné veřejné složky
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
- "3488"
ms.openlocfilehash: 7b04612daca61650d162c1dde240e25c1b185b04
ms.sourcegitcommit: 8ba12eff67e405f5922ea4cc35155e3036447859
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/15/2020
ms.locfileid: "42063616"
---
# <a name="restore-a-deleted-public-folder"></a><span data-ttu-id="da66e-102">Obnovení odstraněné veřejné složky</span><span class="sxs-lookup"><span data-stu-id="da66e-102">Restore a deleted public folder</span></span>

<span data-ttu-id="da66e-103">**Obnovení odstraněných položek z veřejné složky**:</span><span class="sxs-lookup"><span data-stu-id="da66e-103">**To restore deleted items from a public folder**:</span></span>

- <span data-ttu-id="da66e-104">Viz [V Outlooku 2016 nelze obnovit odstraněné položky z nepoštovní veřejné složky](https://aka.ms/pfrec).</span><span class="sxs-lookup"><span data-stu-id="da66e-104">See [You can't recover deleted items from a non-mail public folder in Outlook 2016](https://aka.ms/pfrec).</span></span>
 
<span data-ttu-id="da66e-105">**Obnovení odstraněné veřejné složky (libovolného typu):**</span><span class="sxs-lookup"><span data-stu-id="da66e-105">**To restore a deleted public folder (of any type)**:</span></span> 

- <span data-ttu-id="da66e-106">Použijte následující příkaz EXO PowerShell:</span><span class="sxs-lookup"><span data-stu-id="da66e-106">Please use following EXO PowerShell command:</span></span>

    <span data-ttu-id="da66e-107">Syntaxe:</span><span class="sxs-lookup"><span data-stu-id="da66e-107">Syntax:</span></span>

    ><span data-ttu-id="da66e-108">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ? {$_. Název -eq\<" name_of_deleted_public_Folder"}; Set-PublicFolder $pf.identity \<-Path cesta, kde bude složka obnovena></span><span class="sxs-lookup"><span data-stu-id="da66e-108">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored></span></span>

    <span data-ttu-id="da66e-109">Příklad: Následující příkaz obnoví podsložku1 a umístí ji pod položku \Parent1:</span><span class="sxs-lookup"><span data-stu-id="da66e-109">Example: The following command will restore Subfolder1 and place it under \Parent1:</span></span>

    ><span data-ttu-id="da66e-110">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ? {$_. Název -eq "Podsložka1"}; Set-PublicFolder $pf.identity -Cesta \Parent1</span><span class="sxs-lookup"><span data-stu-id="da66e-110">$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1</span></span>

<span data-ttu-id="da66e-111">Další podrobnosti najdete v [tématu Obnovení odstraněné veřejné složky.](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder)</span><span class="sxs-lookup"><span data-stu-id="da66e-111">See [Restore a deleted public folder](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) for more details.</span></span>
