---
title: Odstraňování problémů se zprávami o odepření přístupu
ms.author: pebaum
author: pebaum
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 57919e6dbd81a5bf3b17fb067485e8eec23b7d4c
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051418"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="913d3-102">Odstraňování problémů se zprávami o odepření přístupu v centru pro správu SharePoint/OneDrive</span><span class="sxs-lookup"><span data-stu-id="913d3-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="913d3-103">Pokud se při pokusu o přechod do centra pro správu služby SharePoint/OneDrive zobrazuje zpráva o odepření přístupu, ujistěte se, že jste [uživateli přiřadili licenci](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="913d3-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span> <span data-ttu-id="913d3-104">Pokud má uživatel licenci, měli byste také zajistit, aby jim byla [přidělena role správce](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) , která má přístup k centrům správy.</span><span class="sxs-lookup"><span data-stu-id="913d3-104">If the user has a license, you should also make sure they are [assigned an administrator role](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) that can access the admin centers.</span></span>

<span data-ttu-id="913d3-105">K tomuto problému může dojít také v případě, že je uživatel odstraněn a znovu vytvořen se stejným hlavním uživatelským jménem (UPN).</span><span class="sxs-lookup"><span data-stu-id="913d3-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="913d3-106">Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID).</span><span class="sxs-lookup"><span data-stu-id="913d3-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="913d3-107">Když se uživatel pokusí o přístup k kolekci webů nebo k jejich objektu OneDrive, má uživatel nesprávný identifikátor PUID.</span><span class="sxs-lookup"><span data-stu-id="913d3-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="913d3-108">Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory.</span><span class="sxs-lookup"><span data-stu-id="913d3-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="913d3-109">Pokud se uživatelé již přihlásili ke službě SharePoint a pak jsou přesunuté do jiné organizační jednotky a znovu synchronizovány se službou SharePoint, mohou k tomuto problému dojít.</span><span class="sxs-lookup"><span data-stu-id="913d3-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="913d3-110">Chcete-li tento problém vyřešit, obnovte původní název UPN podle kroků v článku, [obnovte uživatele v sadě Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="913d3-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>

<span data-ttu-id="913d3-111">Poznámka: Pokud není centrum OneDrive nebo SharePoint Admin Center k dispozici pro více uživatelů, kteří měli přístup dříve, může se jednat o dočasný problém se službou.</span><span class="sxs-lookup"><span data-stu-id="913d3-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="913d3-112">[Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="913d3-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


