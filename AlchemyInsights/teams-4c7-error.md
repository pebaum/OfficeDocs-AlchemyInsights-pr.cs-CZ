---
title: Týmy 4c7 Error
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3472"
- "9001211"
ms.openlocfilehash: 0945a341c6456ee4178c0485f3bfb9232fa78a11
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796024"
---
# <a name="4c7-error-in-microsoft-teams"></a><span data-ttu-id="80430-102">Chyba 4c7 v týmu Microsoft</span><span class="sxs-lookup"><span data-stu-id="80430-102">4c7 error in Microsoft Teams</span></span>

<span data-ttu-id="80430-103">K této chybě dochází, protože týmy Microsoft vyžadují ověřování pomocí formulářů.</span><span class="sxs-lookup"><span data-stu-id="80430-103">This error occurs because Microsoft Teams requires Forms Authentication.</span></span> <span data-ttu-id="80430-104">Pokud nasadíte službu AD FS (Active Directory Federation Services), není pro síť intranet ve výchozím nastavení povoleno ověřování pomocí formulářů.</span><span class="sxs-lookup"><span data-stu-id="80430-104">When you deploy Active Directory Federation Services (AD FS), Forms Authentication is not enabled for the intranet by default.</span></span> <span data-ttu-id="80430-105">Pokud se integrované ověřování systému Windows nezdaří, zobrazí se výzva k přihlášení pomocí formulářové autentizace.</span><span class="sxs-lookup"><span data-stu-id="80430-105">If Windows Integrated Authentication fails, you are prompted to sign in by using Forms Authentication.</span></span>

<span data-ttu-id="80430-106">Chcete-li tento problém vyřešit, povolte ověřování formulářů pomocí modulu snap-in konzoly MMC (Microsoft Management Console) služby AD FS v počítači, který má místní kopii služby Active Directory.</span><span class="sxs-lookup"><span data-stu-id="80430-106">To resolve this issue, enable Forms Authentication by using the AD FS Microsoft Management Console (MMC) snap-in on the computer that has the local copy of Active Directory.</span></span> <span data-ttu-id="80430-107">Uděláte to takto:</span><span class="sxs-lookup"><span data-stu-id="80430-107">To do this, follow these steps:</span></span> 

1. <span data-ttu-id="80430-108">V navigačním podokně přejděte na **zásady ověřování**.</span><span class="sxs-lookup"><span data-stu-id="80430-108">In the navigation pane, browse to **Authentication Policies**.</span></span>
2. <span data-ttu-id="80430-109">V části **Akce** v podokně podrobností vyberte možnost **Upravit globální primární ověřování**.</span><span class="sxs-lookup"><span data-stu-id="80430-109">Under **Actions** in the details pane, select **Edit Global Primary Authentication**.</span></span>
3. <span data-ttu-id="80430-110">Na kartě **intranet** vyberte možnost **ověřování pomocí formulářů**.</span><span class="sxs-lookup"><span data-stu-id="80430-110">On the **Intranet** tab, select **Forms Authentication**.</span></span>
4. <span data-ttu-id="80430-111">Klepněte na **tlačítko OK** (nebo **použijte**).</span><span class="sxs-lookup"><span data-stu-id="80430-111">Select **OK** (or **Apply**).</span></span>