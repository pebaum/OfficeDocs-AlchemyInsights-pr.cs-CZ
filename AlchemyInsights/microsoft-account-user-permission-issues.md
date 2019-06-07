---
title: Vytvořit a používat sdílené poštovní schránky
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 81bf8082198de1c44037291f23c434d06a77f02a
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34762394"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="1ce2f-102">Řešení problému - uživatel nebyl nalezen v adresáři</span><span class="sxs-lookup"><span data-stu-id="1ce2f-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="1ce2f-103">Pokud uživatelé zobrazuje chybová zpráva "uživatel nebyl nalezen" v adresáři.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-103">If users are receiving error message "user can't be found" in the directory.</span></span> <span data-ttu-id="1ce2f-104">Pokuste se znovu Pokud typ problému není uživatele v adresáři.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-104">Please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="1ce2f-105">Následující kroky můžete dokončit k řešení problému.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-105">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="1ce2f-106">Zkontrolujte účet, který přijaté že e-mailové pozvánce je stejný účet použitý k přihlášení později.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-106">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="1ce2f-107">Ujistěte se, že uživatel používá stejný účet přihlášení k webu a přijměte pozvání.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-107">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="1ce2f-108">Další informace naleznete v [Správa aliasů účtu Microsoft</a> pro správu služeb Office 365 přihlášení](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="1ce2f-108">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Office 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="1ce2f-109">Přejděte na jednotlivé servery, ve kterém uživatel dostává chybu.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-109">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="1ce2f-110">Přidat "/ _layouts/15/people.aspx/membershipgroupid=0" (v uvozovkách) na konec adresy URL webu.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-110">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="1ce2f-111">Příklad: https://_lT _"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-111">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="1ce2f-112">Vyberte uživatele ze seznamu.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-112">Select the user from the list.</span></span>

- <span data-ttu-id="1ce2f-113">Klepněte na tlačítko **Odebrat uživatelská oprávnění** z pásu karet.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-113">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="1ce2f-114">Přidejte uživatele zpět a znovu odeslat pozvání pro uživatele.</span><span class="sxs-lookup"><span data-stu-id="1ce2f-114">Add back the User and Resend the invite to the user.</span></span>

