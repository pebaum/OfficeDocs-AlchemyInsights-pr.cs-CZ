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
ms.openlocfilehash: 49c510668f4c73a71495b89ee9f810d4e7244da3
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270665"
---
# <a name="workflow-email-is-not-being-sent"></a><span data-ttu-id="afce8-102">E-mailu pracovního postupu nebyla odeslána.</span><span class="sxs-lookup"><span data-stu-id="afce8-102">Workflow email is not being sent</span></span>

1. <span data-ttu-id="afce8-103">E-mailu z pracovní postupy nejsou odeslány všem uživatelům nebo pouze pro určité uživatele nebo zobrazí že chybová **e-mailovou zprávu nelze odeslat. Ujistěte se, e-mailu je platný příjemce**.</span><span class="sxs-lookup"><span data-stu-id="afce8-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="afce8-104">Zkontrolujte, zda uživatel existuje ve skupině oprávnění **Všem uživatelům** (seznam informací o uživatelích) pro danou kolekci webů.</span><span class="sxs-lookup"><span data-stu-id="afce8-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="afce8-105">Ukázka přímé URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="afce8-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="afce8-106">Pokud uživatel neexistuje, zkontrolujte, zda že uživatel je přihlášen do stránky.</span><span class="sxs-lookup"><span data-stu-id="afce8-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="afce8-107">Pokud je externí uživatel, ujistěte se, že jejich pozvání byla přijata.</span><span class="sxs-lookup"><span data-stu-id="afce8-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="afce8-108">Pokud uživatel neexistuje ve skupině oprávnění, zkontrolujte, zda že e-mailová adresa je správná.</span><span class="sxs-lookup"><span data-stu-id="afce8-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="afce8-109">Pokud zde není nastavena e-mailová adresa uživatele, vytvořte ukázkové oznámení pro uživatele vynutí synchronizaci s uživatelským účtem z uživatelské profily služby SharePoint do této kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="afce8-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="afce8-110">E-mailu z pracovních postupů jsou odesílány správci kolekce webů, ale nikoli pro ostatní uživatele a zobrazí chyba \*\*Zakázáno HTTP <spam> <spam> \*\* <spam> <spam>.</span><span class="sxs-lookup"><span data-stu-id="afce8-110">Email from Workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <spam><spam>https://URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**<spam><spam>.</span></span>
 

    <span data-ttu-id="afce8-111">V části [Přístup odepřen při odeslaných e-mailů do skupiny](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="afce8-111">See [Access Denied when sent email to groups](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="afce8-112">Ověřte také, zda není aktivní funkce kolekce webů **režim uzamčení oprávnění uživatele omezený přístup** .</span><span class="sxs-lookup"><span data-stu-id="afce8-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="afce8-113">Související témata</span><span class="sxs-lookup"><span data-stu-id="afce8-113">Related topics</span></span>
<span data-ttu-id="afce8-114">Chcete vyzkoušet Microsoft Flow v Online služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="afce8-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="afce8-115">Vytvoření toku</span><span class="sxs-lookup"><span data-stu-id="afce8-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="afce8-116">SharePoint a toku</span><span class="sxs-lookup"><span data-stu-id="afce8-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 

