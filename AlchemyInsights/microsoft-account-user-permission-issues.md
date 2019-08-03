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
ms.openlocfilehash: 0909edc581c811fdc4683b004e0df0adbac88d1c
ms.sourcegitcommit: 514ced512d0d7fff485b6fbf236cd27d6b4166e0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/26/2019
ms.locfileid: "35249906"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="6d146-102">Řešení problému - uživatel nebyl nalezen v adresáři</span><span class="sxs-lookup"><span data-stu-id="6d146-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="6d146-103">Pokud uživatelé zobrazuje chybová zpráva "uživatel nebyl nalezen" v adresáři.</span><span class="sxs-lookup"><span data-stu-id="6d146-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="6d146-104">Pokuste se znovu Pokud typ problému není uživatele v adresáři.</span><span class="sxs-lookup"><span data-stu-id="6d146-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="6d146-105">Následující kroky můžete dokončit k řešení problému.</span><span class="sxs-lookup"><span data-stu-id="6d146-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="6d146-106">Zkontrolujte účet, který přijaté že e-mailové pozvánce je stejný účet použitý k přihlášení později.</span><span class="sxs-lookup"><span data-stu-id="6d146-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="6d146-107">Ujistěte se, že uživatel používá stejný účet přihlášení k webu a přijměte pozvání.</span><span class="sxs-lookup"><span data-stu-id="6d146-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="6d146-108">Další informace naleznete v [Správa aliasů účtu Microsoft</a> pro správu služeb Office 365 přihlášení](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="6d146-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="6d146-109">Přejděte na jednotlivé servery, ve kterém uživatel dostává chybu.</span><span class="sxs-lookup"><span data-stu-id="6d146-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="6d146-110">Přidat "/ _layouts/15/people.aspx/membershipgroupid=0" (v uvozovkách) na konec adresy URL webu.</span><span class="sxs-lookup"><span data-stu-id="6d146-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="6d146-111">Příklad: https://_lT _"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="6d146-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="6d146-112">Vyberte uživatele ze seznamu.</span><span class="sxs-lookup"><span data-stu-id="6d146-112">Select the user from the list.</span></span>

- <span data-ttu-id="6d146-113">Klepněte na tlačítko **Odebrat uživatelská oprávnění** z pásu karet.</span><span class="sxs-lookup"><span data-stu-id="6d146-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="6d146-114">Přidejte uživatele zpět a znovu odeslat pozvání pro uživatele.</span><span class="sxs-lookup"><span data-stu-id="6d146-114">Add back the User and Resend the invite to the user.</span></span>

