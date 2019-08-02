---
title: E-mailu pracovního postupu nebyla odeslána.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059597"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="80007-102">E-mailu pracovního postupu nebyla odeslána.</span><span class="sxs-lookup"><span data-stu-id="80007-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="80007-103">E-mailu z pracovní postupy nejsou odeslány všem uživatelům nebo pouze pro určité uživatele nebo zobrazí že chybová **e-mailovou zprávu nelze odeslat. Ujistěte se, e-mailu je platný příjemce**.</span><span class="sxs-lookup"><span data-stu-id="80007-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

<span data-ttu-id="80007-104">Zkontrolujte, zda uživatel existuje ve skupině oprávnění **Všem uživatelům** (seznam informací o uživatelích) pro danou kolekci webů.</span><span class="sxs-lookup"><span data-stu-id="80007-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="80007-105">Ukázka přímé URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="80007-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

- <span data-ttu-id="80007-106">Pokud uživatel neexistuje, zkontrolujte, zda že uživatel je přihlášen do stránky.</span><span class="sxs-lookup"><span data-stu-id="80007-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
- <span data-ttu-id="80007-107">Pokud je externí uživatel, ujistěte se, že jejich pozvání byla přijata.</span><span class="sxs-lookup"><span data-stu-id="80007-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
- <span data-ttu-id="80007-108">Pokud uživatel neexistuje ve skupině oprávnění, zkontrolujte, zda že e-mailová adresa je správná.</span><span class="sxs-lookup"><span data-stu-id="80007-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
- <span data-ttu-id="80007-109">Pokud zde není nastavena e-mailová adresa uživatele, vytvořte ukázkové oznámení pro uživatele vynutí synchronizaci s uživatelským účtem z uživatelské profily služby SharePoint do této kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="80007-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="80007-110">E-mailu z pracovních postupů jsou odesílány správci kolekce webů, ale nikoli pro ostatní uživatele a zobrazí chyba \*\*Zakázáno HTTP <spam> <spam> \*\* <spam> <spam>.</span><span class="sxs-lookup"><span data-stu-id="80007-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

<span data-ttu-id="80007-111">V části [Přístup odepřen při odeslaných e-mailů do skupiny](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="80007-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

<span data-ttu-id="80007-112">Ověřte také, zda není aktivní funkce kolekce webů **režim uzamčení oprávnění uživatele omezený přístup** .</span><span class="sxs-lookup"><span data-stu-id="80007-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>

## <a name="related-topics"></a><span data-ttu-id="80007-113">Související témata</span><span class="sxs-lookup"><span data-stu-id="80007-113">Related topics</span></span>
- [<span data-ttu-id="80007-114">Vytvoření toku</span><span class="sxs-lookup"><span data-stu-id="80007-114">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="80007-115">SharePoint a toku</span><span class="sxs-lookup"><span data-stu-id="80007-115">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


