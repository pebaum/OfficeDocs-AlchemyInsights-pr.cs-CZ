---
title: E-mail pracovního postupu se neodesílá
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 391d3a2dcc2676a405065115f375c802d2492119
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766126"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="6cfbe-102">E-mail pracovního postupu se neodesílá pro sharepointový seznam nebo knihovnu.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="6cfbe-103">E-maily z pracovních postupů nejsou odesílány všem uživatelům nebo pouze konkrétním uživatelům nebo se zobrazí chyba **E-mailovou zprávu nelze odeslat. Zkontrolujte, zda má e-mail platného příjemce**.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="6cfbe-104">Zkontrolujte, zda uživatel pro tuto kolekci webů existuje ve skupině Oprávnění **Všichni lidé** (seznam informací o uživateli).</span><span class="sxs-lookup"><span data-stu-id="6cfbe-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="6cfbe-105">Ukázka přímé<tenant>adresy<sitename>URL: https:// .sharepoint.com/sites/ /_layouts/15/people.aspx? ČlenstvíGroupId=0</span><span class="sxs-lookup"><span data-stu-id="6cfbe-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="6cfbe-106">Pokud uživatel neexistuje, ujistěte se, že je uživatel přihlášen ke stránce.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="6cfbe-107">Pokud se jedná o externího uživatele, ujistěte se, že jeho pozvání bylo přijato.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="6cfbe-108">Pokud uživatel existuje ve skupině oprávnění, ujistěte se, že e-mailová adresa je správná.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="6cfbe-109">Pokud zde není nastavena e-mailová adresa uživatelů, vytvořte pro tohoto uživatele ukázkovou výstrahu, která vynutí synchronizaci tohoto uživatelského účtu z uživatelských profilů služby SharePoint do této kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="6cfbe-110">E-maily z pracovních postupů jsou odesílány správcům kolekce webů, ale ne ostatním uživatelům a zobrazí se chyba **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="6cfbe-111">Viz [Přístup byl odepřen při odeslání e-mailu skupině SharePointu](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="6cfbe-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="6cfbe-112">Ověřte také, zda funkce kolekce webů **režimu uzamčení uživatelských oprávnění s omezeným přístupem** není aktivní.</span><span class="sxs-lookup"><span data-stu-id="6cfbe-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="6cfbe-113">Související témata</span><span class="sxs-lookup"><span data-stu-id="6cfbe-113">Related topics</span></span>
<span data-ttu-id="6cfbe-114">Chcete vyzkoušet Microsoft Flow na SharePointu Online?</span><span class="sxs-lookup"><span data-stu-id="6cfbe-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="6cfbe-115">Vytvořit tok</span><span class="sxs-lookup"><span data-stu-id="6cfbe-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="6cfbe-116">SharePoint a tok</span><span class="sxs-lookup"><span data-stu-id="6cfbe-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


