---
title: Řešení problému - uživatel nebyl nalezen v adresáři
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 537b27d06acd17cbb3fe99bcb89e153099e92bb4
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36544856"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="b3acf-102">Řešení problému - uživatel nebyl nalezen v adresáři</span><span class="sxs-lookup"><span data-stu-id="b3acf-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="b3acf-103">Pokud uživatelé zobrazuje chybová zpráva "uživatel nebyl nalezen" v adresáři.</span><span class="sxs-lookup"><span data-stu-id="b3acf-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="b3acf-104">Pokuste se znovu Pokud typ problému není uživatele v adresáři.</span><span class="sxs-lookup"><span data-stu-id="b3acf-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="b3acf-105">Následující kroky můžete dokončit k řešení problému.</span><span class="sxs-lookup"><span data-stu-id="b3acf-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="b3acf-106">Zkontrolujte účet, který přijaté že e-mailové pozvánce je stejný účet použitý k přihlášení později.</span><span class="sxs-lookup"><span data-stu-id="b3acf-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="b3acf-107">Ujistěte se, že uživatel používá stejný účet přihlášení k webu a přijměte pozvání.</span><span class="sxs-lookup"><span data-stu-id="b3acf-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="b3acf-108">Další informace naleznete v [Správa aliasů účtu Microsoft</a> pro správu služeb Office 365 přihlášení](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="b3acf-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="b3acf-109">Přejděte na jednotlivé servery, ve kterém uživatel dostává chybu.</span><span class="sxs-lookup"><span data-stu-id="b3acf-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="b3acf-110">Přidat "/ _layouts/15/people.aspx/membershipgroupid=0" (v uvozovkách) na konec adresy URL webu.</span><span class="sxs-lookup"><span data-stu-id="b3acf-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="b3acf-111">Příklad: https://_lT _"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="b3acf-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="b3acf-112">Vyberte uživatele ze seznamu.</span><span class="sxs-lookup"><span data-stu-id="b3acf-112">Select the user from the list.</span></span>

- <span data-ttu-id="b3acf-113">Klepněte na tlačítko **Odebrat uživatelská oprávnění** z pásu karet.</span><span class="sxs-lookup"><span data-stu-id="b3acf-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="b3acf-114">Přidejte uživatele zpět a znovu odeslat pozvání pro uživatele.</span><span class="sxs-lookup"><span data-stu-id="b3acf-114">Add back the User and Resend the invite to the user.</span></span>

