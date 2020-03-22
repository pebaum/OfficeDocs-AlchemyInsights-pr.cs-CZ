---
title: Nelze získat přístup k veřejným složkám.
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
ms.openlocfilehash: a579b89b68bfb8432adfe64b155803eda2c3b086
ms.sourcegitcommit: a3b42ee05224846327d353b48a8c67dab724f6eb
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/21/2020
ms.locfileid: "42891742"
---
# <a name="outlook-cannot-connect-to-public-folders"></a>Aplikace Outlook se nemůže připojit k veřejným složkám

Pokud přístup k veřejným složkám některým uživatelům nefunguje, vyzkoušejte následující postup:

Připojte se k prostředí EXO PowerShell a nakonfigurujte parametr DefaultPublicFolderMailbox u problémového uživatelského účtu tak, aby odpovídal parametru pracovního uživatelského účtu.

Příklad:

Get-Mailbox WorkingUser | ft VýchozíPublicFolderMailbox,EffectivePublicFolderMailbox

Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<hodnota z předchozího příkazu>

Počkejte alespoň jednu hodinu, než se změna projeví.

Pokud problém přetrvává, postupujte podle [tohoto postupu](https://aka.ms/pfcte) k řešení problémů s přístupem k veřejným složkám pomocí aplikace Outlook.