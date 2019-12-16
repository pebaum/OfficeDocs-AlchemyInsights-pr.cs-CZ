---
title: E-mail pracovního postupu není odeslán.
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: 76b64323c9d34d49e9c6bd77c2cc7eff6d7c5402
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049366"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a><span data-ttu-id="59ecf-102">E-mail pracovního postupu není odeslán pro seznam nebo knihovnu SharePoint.</span><span class="sxs-lookup"><span data-stu-id="59ecf-102">Workflow email is not being sent for a SharePoint list or library</span></span>

1. <span data-ttu-id="59ecf-103">E-maily z pracovních postupů nejsou odesílány všem uživatelům nebo pouze určitým uživatelům nebo se zobrazí chyba, **kterou e-mailovou zprávu nelze odeslat. Zkontrolujte, zda e-mail obsahuje platného příjemce**.</span><span class="sxs-lookup"><span data-stu-id="59ecf-103">Email from workflows are not sent to all users or only specific users, or you see the error **The e-mail message cannot be sent. Make sure the e-mail has a valid recipient**.</span></span>

    <span data-ttu-id="59ecf-104">Zkontrolujte, zda uživatel existuje ve skupině oprávnění pro **všechny osoby** (seznam informací o uživatelích) pro danou kolekci webů.</span><span class="sxs-lookup"><span data-stu-id="59ecf-104">Check if the user exist in the **All People** permissions group (user information list) for that site collection.</span></span>  <span data-ttu-id="59ecf-105">Ukázka přímé adresy URL:<tenant>https://.<sitename>SharePoint.com/sites//_layouts/15/People.aspx? MembershipGroupId = 0</span><span class="sxs-lookup"><span data-stu-id="59ecf-105">Sample direct URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx?MembershipGroupId=0</span></span>

    - <span data-ttu-id="59ecf-106">Pokud uživatel neexistuje, ujistěte se, že je uživatel přihlášen na stránku.</span><span class="sxs-lookup"><span data-stu-id="59ecf-106">If the user does not exist, make sure the user is signed into the page.</span></span> 
    - <span data-ttu-id="59ecf-107">Pokud se jedná o externího uživatele, ujistěte se, že pozvání bylo přijato.</span><span class="sxs-lookup"><span data-stu-id="59ecf-107">If it is an external user, make sure that their invitation has been accepted.</span></span>
    - <span data-ttu-id="59ecf-108">Pokud uživatel existuje ve skupině oprávnění, zkontrolujte správnost e-mailové adresy.</span><span class="sxs-lookup"><span data-stu-id="59ecf-108">If the user does exist in the permissions group, make sure the email address is correct.</span></span>
    - <span data-ttu-id="59ecf-109">Pokud zde není nastavena e-mailová adresa uživatele, vytvořte vzorovou výstrahu pro tohoto uživatele, který vynutí synchronizaci tohoto uživatelského účtu z uživatelských profilů služby SharePoint do této kolekce webů.</span><span class="sxs-lookup"><span data-stu-id="59ecf-109">If the users email address is not set here, then create a sample alert for that user which forces the sync of that user account from User Profiles of SharePoint to this site collection.</span></span>
 
2. <span data-ttu-id="59ecf-110">E-maily z pracovních postupů jsou odesílány správcům kolekcí webů, ale nikoli jiným uživatelům a zobrazí se chyba **http zakázána pro <span>https:</span>//URL/_vti_bin/Client.XVC.SP.Utilities.Utility.SendEmail**.</span><span class="sxs-lookup"><span data-stu-id="59ecf-110">Email from workflows are sent to the site collection administrators but not to other users and see the error **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.</span></span>
 

    <span data-ttu-id="59ecf-111">Informace [o odepření přístupu při odeslání e-mailu skupině SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span><span class="sxs-lookup"><span data-stu-id="59ecf-111">See [Access Denied when you send an email to a SharePoint group](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).</span></span>

    <span data-ttu-id="59ecf-112">Ověřte také, zda není aktivní funkce kolekce webů v **režimu uzamčení omezeného přístupu** .</span><span class="sxs-lookup"><span data-stu-id="59ecf-112">Also, verify that the **Limited-access user permission lockdown mode** site collection feature is not active.</span></span>


## <a name="related-topics"></a><span data-ttu-id="59ecf-113">Související témata</span><span class="sxs-lookup"><span data-stu-id="59ecf-113">Related topics</span></span>
<span data-ttu-id="59ecf-114">Chcete vyzkoušet program Microsoft Flow ve službě SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="59ecf-114">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="59ecf-115">Vytvořit tok</span><span class="sxs-lookup"><span data-stu-id="59ecf-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="59ecf-116">Služba SharePoint a tok</span><span class="sxs-lookup"><span data-stu-id="59ecf-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


