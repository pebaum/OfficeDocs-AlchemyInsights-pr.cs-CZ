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
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="1d603-102">Aplikace Outlook se nemůže připojit k veřejným složkám</span><span class="sxs-lookup"><span data-stu-id="1d603-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="1d603-103">Pokud přístup k veřejným složkám nepracuje pro několik uživatelů, vyzkoušejte následující kroky:</span><span class="sxs-lookup"><span data-stu-id="1d603-103">If public folder access isn't working for few users, try the following:</span></span>

<span data-ttu-id="1d603-104">Připojte se k EXO PowerShell a konfigurujte výchozí složku DefaultPublicFolderMailbox na problémověm uživatelském účtu tak, aby odpovídal jednomu pracovnímu účtu uživatele.</span><span class="sxs-lookup"><span data-stu-id="1d603-104">Connect to EXO PowerShell, and configure the DefaultPublicFolderMailbox on the problem user account to match one on a working user account.</span></span>

<span data-ttu-id="1d603-105">Příklad:</span><span class="sxs-lookup"><span data-stu-id="1d603-105">Example:</span></span>

<span data-ttu-id="1d603-106">WorkingUser pro získání poštovní schránky | FT DefaultPublicFolderMailbox, Efektvepublicfoldermailbox</span><span class="sxs-lookup"><span data-stu-id="1d603-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="1d603-107">Set-Mailbox Problémuer-DefaultPublicFolderMailbox \<hodnota z předchozího příkazu></span><span class="sxs-lookup"><span data-stu-id="1d603-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="1d603-108">Počkejte alespoň jednu hodinu, než se změna projeví.</span><span class="sxs-lookup"><span data-stu-id="1d603-108">Wait at least one hour for the change to take effect.</span></span>