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
ms.openlocfilehash: 261fe1b1bc815dd4ad568051cfefad1e214b957e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530859"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="88b14-102">Pracovního e-mailu není odeslán do knihovny nebo seznamu SharePoint</span><span class="sxs-lookup"><span data-stu-id="88b14-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="88b14-103">E-mailu z pracovní postupy nejsou odeslány všem uživatelům nebo pouze pro určité uživatele nebo zobrazí že chybová **e-mailovou zprávu nelze odeslat. Ujistěte se, e-mailu je platný příjemce**.</span><span class="sxs-lookup"><span data-stu-id="88b14-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="88b14-104">Zkontrolujte, zda uživatel existuje ve skupině oprávnění **Všem uživatelům** (seznam informací o uživatelích) pro danou kolekci webů.</span><span class="sxs-lookup"><span data-stu-id="88b14-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="88b14-105">Ukázka přímé URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="88b14-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="88b14-106">Pokud uživatel neexistuje, zkontrolujte, zda že uživatel je přihlášen do stránky.</span><span class="sxs-lookup"><span data-stu-id="88b14-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="88b14-107">Pokud je externí uživatel, ujistěte se, že jejich pozvání byla přijata.</span><span class="sxs-lookup"><span data-stu-id="88b14-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="88b14-108">Pokud uživatel neexistuje ve skupině oprávnění, zkontrolujte, zda že e-mailová adresa je správná.</span><span class="sxs-lookup"><span data-stu-id="88b14-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="88b14-109">Pokud zde není nastavena e-mailová adresa uživatele, vytvořte ukázkové oznámení pro uživatele vynutí synchronizaci s uživatelským účtem z uživatelské profily služby SharePoint do této kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="88b14-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="88b14-110">E-mailu z pracovních postupů jsou odesílány správci kolekce webů, ale nikoli pro ostatní uživatele a zobrazí chyba **HTTP Zakázáno <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span><span class="sxs-lookup"><span data-stu-id="88b14-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="88b14-111">V části [Přístup odepřen při odeslání e-mailu skupině SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="88b14-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="88b14-112">Ověřte také, zda není aktivní funkce kolekce webů **režim uzamčení oprávnění uživatele omezený přístup** .</span><span class="sxs-lookup"><span data-stu-id="88b14-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="88b14-113">Související témata</span><span class="sxs-lookup"><span data-stu-id="88b14-113">Related topics</span></span>
<span data-ttu-id="88b14-114">Chcete vyzkoušet Microsoft Flow v Online služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="88b14-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="88b14-115">Vytvoření toku</span><span class="sxs-lookup"><span data-stu-id="88b14-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="88b14-116">SharePoint a toku</span><span class="sxs-lookup"><span data-stu-id="88b14-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


