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
ms.openlocfilehash: cd85dd3c0eb14f6e02ac4f912e733468403387aa
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158487"
---
# <a name="restore-a-deleted-public-folder"></a>Obnovení odstraněné veřejné složky

**Obnovení odstraněných položek z veřejné složky**:

- Viz [V Outlooku 2016 nelze obnovit odstraněné položky z nepoštovní veřejné složky](https://aka.ms/pfrec).
 
**Obnovení odstraněné veřejné složky (libovolného typu):** 

- Použijte následující příkaz EXO PowerShell:

    Syntaxe:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Příklad: Následující příkaz obnoví podsložku1 a umístí ji pod položku \Parent1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Další podrobnosti najdete v [tématu Obnovení odstraněné veřejné složky.](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder)
