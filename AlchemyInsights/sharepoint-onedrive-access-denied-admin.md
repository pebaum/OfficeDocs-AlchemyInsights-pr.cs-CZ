---
title: Poradce při potížích se zprávami o odepření přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 82e11458529b8a49e583b1a6963a51e2a466bfd6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758382"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="45960-102">Poradce při potížích se zprávami o odepření přístupu v Centru pro správu Sharepointu/OneDrivu</span><span class="sxs-lookup"><span data-stu-id="45960-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="45960-103">Pokud se při pokusu o procházení Centra pro správu služby Sharepoint/OneDrive zobrazuje zpráva o odepření přístupu, ujistěte se, že jste [uživateli přiřadili licenci](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="45960-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span> <span data-ttu-id="45960-104">Pokud má uživatel licenci, měli byste se také ujistit, že je [mu přiřazena role správce,](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) která má přístup ke centrům pro správu.</span><span class="sxs-lookup"><span data-stu-id="45960-104">If the user has a license, you should also make sure they are [assigned an administrator role](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) that can access the admin centers.</span></span>

<span data-ttu-id="45960-105">K tomuto problému může dojít také při odstranění uživatele a znovu vytvořit se stejným hlavním jménem uživatele (UPN).</span><span class="sxs-lookup"><span data-stu-id="45960-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="45960-106">Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID).</span><span class="sxs-lookup"><span data-stu-id="45960-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="45960-107">Když se uživatel pokusí o přístup k kolekci webů nebo k jejich OneDrivu, má nesprávný PUID.</span><span class="sxs-lookup"><span data-stu-id="45960-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="45960-108">Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="45960-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="45960-109">Pokud se uživatelé už přihlásili ke SharePointu a potom jsou přesunuti do jiné oua nové ou a znovu synchronizováni se službou SharePoint, může se u nich vyskytnout tento problém.</span><span class="sxs-lookup"><span data-stu-id="45960-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="45960-110">Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní název uživatele s kroky v článku [Obnovení uživatele v Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="45960-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="45960-111">Poznámka: Pokud centrum pro správu OneDrivu nebo SharePointu není dostupné pro více uživatelů, kteří měli dříve přístup, může se napodobuje problém s dočasnou službou.</span><span class="sxs-lookup"><span data-stu-id="45960-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="45960-112">[Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="45960-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


