---
title: Poradce při potížích s problémem – uživatel nebyl v adresáři nalezen
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 3b863c5e9962dd29ca2ed41d113041d74830f615
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43702731"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a><span data-ttu-id="9e39b-102">Poradce při potížích s problémem – uživatel nebyl v adresáři nalezen</span><span class="sxs-lookup"><span data-stu-id="9e39b-102">Troubleshoot issue - User not found in directory</span></span>

<span data-ttu-id="9e39b-103">Pokud se uživatelům v adresáři zobrazuje chybová zpráva "uživatel nebyl nalezen", opakujte akci, pokud je typ problému Uživatel není v adresáři.</span><span class="sxs-lookup"><span data-stu-id="9e39b-103">If users are receiving error message "user can't be found" in the directory, please try again where the Issue Type is User not in directory.</span></span>

<span data-ttu-id="9e39b-104">Následující kroky lze provést k řešení problému.</span><span class="sxs-lookup"><span data-stu-id="9e39b-104">The following steps can be completed to troubleshoot the issue.</span></span>

- <span data-ttu-id="9e39b-105">Ujistěte se, že účet, který přijal e-mailovou pozvánku, je stejný účet, který se používá k pozdějšímu přihlášení.</span><span class="sxs-lookup"><span data-stu-id="9e39b-105">Ensure the account that accepted the email invitation is the same account that is being used to sign in later.</span></span> <span data-ttu-id="9e39b-106">Ujistěte se, že uživatel používá stejný účet k přijetí pozvánky a přihlášení k webu.</span><span class="sxs-lookup"><span data-stu-id="9e39b-106">Make sure the user is using the same account to accept the invite and sign into the site.</span></span> 

<span data-ttu-id="9e39b-107">Další informace najdete v tématu [Správa</a> aliasů pro svůj účet Microsoft ke správě přihlášení k Microsoftu 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span><span class="sxs-lookup"><span data-stu-id="9e39b-107">For more info, see [How to manage aliases for your Microsoft account</a> to manage the Microsoft 365 login](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases).</span></span> 

- <span data-ttu-id="9e39b-108">Přejděte na všechny stránky, ve kterých se uživateli zobrazuje chyba.</span><span class="sxs-lookup"><span data-stu-id="9e39b-108">Browse to each site(s) in which the user is receiving the error.</span></span> 

<span data-ttu-id="9e39b-109">Přidejte "/_layouts/15/people.aspx/membershipgroupid=0" (v rámci dvojitých uvozovek) na konec adresy URL webu.</span><span class="sxs-lookup"><span data-stu-id="9e39b-109">Add "/_layouts/15/people.aspx/membershipgroupid=0" (within the double-quotes) to the end of the site URL.</span></span> 

<span data-ttu-id="9e39b-110">Příklad: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span><span class="sxs-lookup"><span data-stu-id="9e39b-110">Example: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.</span></span>

- <span data-ttu-id="9e39b-111">Vyberte uživatele ze seznamu.</span><span class="sxs-lookup"><span data-stu-id="9e39b-111">Select the user from the list.</span></span>

- <span data-ttu-id="9e39b-112">Klikněte na **Odebrat uživatelská oprávnění** z pásu karet.</span><span class="sxs-lookup"><span data-stu-id="9e39b-112">Click **Remove User Permissions** from the Ribbon.</span></span> 
-  <span data-ttu-id="9e39b-113">Přidejte zpět uživatele a znovu odešlete pozvánku uživateli.</span><span class="sxs-lookup"><span data-stu-id="9e39b-113">Add back the User and Resend the invite to the user.</span></span>

