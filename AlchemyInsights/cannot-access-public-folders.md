---
title: Nelze získat přístup k veřejným složkám
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
- "3462"
ms.openlocfilehash: a9305b175e1ca0b992c014a73705447d67e037bc
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959488"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Aplikace Outlook se nemůže připojit k veřejným složkám

Pokud přístup k veřejným složkám nepracuje pro několik uživatelů, vyzkoušejte následující kroky:

Připojte se k EXO PowerShell a konfigurujte výchozí složku DefaultPublicFolderMailbox na problémověm uživatelském účtu tak, aby odpovídal jednomu pracovnímu účtu uživatele.

Příklad:

WorkingUser pro získání poštovní schránky | FT DefaultPublicFolderMailbox, Efektvepublicfoldermailbox

Set-Mailbox Problémuer-DefaultPublicFolderMailbox \<hodnota z předchozího příkazu>

Počkejte alespoň jednu hodinu, než se změna projeví.