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
# <a name="restore-a-deleted-public-folder"></a>Obnovení odstraněné veřejné složky

**Obnovení odstraněných položek z veřejné složky**:

- Viz [V Outlooku 2016 nelze obnovit odstraněné položky z nepoštovní veřejné složky](https://aka.ms/pfrec).
 
**Obnovení odstraněné veřejné složky (libovolného typu):** 

- Použijte následující příkaz EXO PowerShell:

    Syntaxe:

    >$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ? {$_. Název -eq\<" name_of_deleted_public_Folder"}; Set-PublicFolder $pf.identity \<-Path cesta, kde bude složka obnovena>

    Příklad: Následující příkaz obnoví podsložku1 a umístí ji pod položku \Parent1:

    >$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ? {$_. Název -eq "Podsložka1"}; Set-PublicFolder $pf.identity -Cesta \Parent1

Další podrobnosti najdete v [tématu Obnovení odstraněné veřejné složky.](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder)
