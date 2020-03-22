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
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="a530a-102">Aplikace Outlook se nemůže připojit k veřejným složkám</span><span class="sxs-lookup"><span data-stu-id="a530a-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="a530a-103">Pokud přístup k veřejným složkám některým uživatelům nefunguje, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="a530a-103">If public folder access isn't working for some users, try the following:</span></span>

<span data-ttu-id="a530a-104">Připojte se k prostředí EXO PowerShell a nakonfigurujte parametr DefaultPublicFolderMailbox u problémového uživatelského účtu tak, aby odpovídal parametru pracovního uživatelského účtu.</span><span class="sxs-lookup"><span data-stu-id="a530a-104">Connect to EXO PowerShell and configure the DefaultPublicFolderMailbox parameter on the problem user account to match the parameter on a working user account.</span></span>

<span data-ttu-id="a530a-105">Příklad:</span><span class="sxs-lookup"><span data-stu-id="a530a-105">Example:</span></span>

<span data-ttu-id="a530a-106">Get-Mailbox WorkingUser | ft VýchozíPublicFolderMailbox,EffectivePublicFolderMailbox</span><span class="sxs-lookup"><span data-stu-id="a530a-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="a530a-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<hodnota z předchozího příkazu></span><span class="sxs-lookup"><span data-stu-id="a530a-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="a530a-108">Počkejte alespoň jednu hodinu, než se změna projeví.</span><span class="sxs-lookup"><span data-stu-id="a530a-108">Wait at least one hour for the change to take effect.</span></span>

<span data-ttu-id="a530a-109">Pokud problém přetrvává, postupujte podle [tohoto postupu](https://aka.ms/pfcte) k řešení problémů s přístupem k veřejným složkám pomocí aplikace Outlook.</span><span class="sxs-lookup"><span data-stu-id="a530a-109">If the issue remains, please follow [this procedure](https://aka.ms/pfcte) to troubleshoot public folder access issues using Outlook.</span></span>