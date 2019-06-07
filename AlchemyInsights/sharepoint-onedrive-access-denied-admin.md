---
title: Poradce při potížích s zprávy o odepření přístupu
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: c204f1889e03886fdfd3d1c760a4a2beb82b0836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760334"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="9d807-102">Odstranit chyby odepření přístupu v Centru pro správu služby Sharepoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="9d807-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="9d807-103">Pokud se zobrazuje zpráva o odepření při pokusu o procházení k Centru správy služby Sharepoint nebo OneDrive přístupu, zkontrolujte, že je [přiřazení licence uživateli](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="9d807-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span> <span data-ttu-id="9d807-104">Pokud uživatel má licenci, jste měli také ujistěte se, že je [přiřazen roli správce](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) , můžete získat přístup k admin Center.</span><span class="sxs-lookup"><span data-stu-id="9d807-104">If the user has a license, you should also make sure they are [assigned an administrator role](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) that can access the admin centers.</span></span>

<span data-ttu-id="9d807-105">Tomuto problému může dojít také v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN).</span><span class="sxs-lookup"><span data-stu-id="9d807-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="9d807-106">Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport).</span><span class="sxs-lookup"><span data-stu-id="9d807-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="9d807-107">Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID.</span><span class="sxs-lookup"><span data-stu-id="9d807-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="9d807-108">Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU).</span><span class="sxs-lookup"><span data-stu-id="9d807-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="9d807-109">Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.</span><span class="sxs-lookup"><span data-stu-id="9d807-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="9d807-110">Chcete-li tento problém vyřešit, obnovte původní název UPN pomocí kroků popsaných v následujícím článku [obnovení uživatele ve službách Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="9d807-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="9d807-111">Poznámka: Pokud OneDrive nebo SharePoint Admin center není k dispozici pro více uživatelů, kteří dříve měl přístup, může existovat problém dočasnou službu.</span><span class="sxs-lookup"><span data-stu-id="9d807-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="9d807-112">[Kontrola řídicí panel stavu služeb](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="9d807-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


