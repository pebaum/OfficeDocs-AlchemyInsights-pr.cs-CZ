---
title: Problémy s výkonem – SharePoint nebo OneDrive
ms.author: pebaum
author: pebaum
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 2db0a9442b9fdf1752b654f7c188e641e0a274cb
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053794"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="e11ef-102">SharePoint nebo OneDrive – pomalé, nepřístupné nebo nedostupné pro více uživatelů</span><span class="sxs-lookup"><span data-stu-id="e11ef-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="e11ef-103">Pokud není web OneDrive nebo SharePoint k dispozici pro více uživatelů, kteří měli přístup dříve, může se jednat o dočasný problém se službou.</span><span class="sxs-lookup"><span data-stu-id="e11ef-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="e11ef-104">[Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="e11ef-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

<span data-ttu-id="e11ef-105">**Přidání a licence uživatele**</span><span class="sxs-lookup"><span data-stu-id="e11ef-105">**Add and license the user**</span></span>

<span data-ttu-id="e11ef-106">Přesvědčte se, zda jste [licence přiřadili uživatelům sady Office 365 pro podniky](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span><span class="sxs-lookup"><span data-stu-id="e11ef-106">Ensure that you [Assign licenses to users in Office 365 for business](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).</span></span>


<span data-ttu-id="e11ef-107">**Přiřadit oprávnění**</span><span class="sxs-lookup"><span data-stu-id="e11ef-107">**Assign Permissions**</span></span>

<span data-ttu-id="e11ef-108">Pokud byla uživateli přiřazena licence služby SharePoint a stále se zobrazuje zpráva o odepření přístupu, zkontrolujte, zda mají přiřazenu [příslušnou úroveň oprávnění](https://docs.microsoft.com/sharepoint/understanding-permission-levels) .</span><span class="sxs-lookup"><span data-stu-id="e11ef-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/sharepoint/understanding-permission-levels) assigned.</span></span>

<span data-ttu-id="e11ef-109">**Zvažte použití funkce vyžádání přístupu**</span><span class="sxs-lookup"><span data-stu-id="e11ef-109">**Consider using the access request feature**</span></span>

<span data-ttu-id="e11ef-110">[Funkce vyžádání přístupu](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) umožňuje uživatelům požadovat přístup k obsahu, který momentálně nemá oprávnění k zobrazení.</span><span class="sxs-lookup"><span data-stu-id="e11ef-110">The [access request feature](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

<span data-ttu-id="e11ef-111">**Povolit vlastní skript může způsobit problémy s odepřeným přístupem**</span><span class="sxs-lookup"><span data-stu-id="e11ef-111">**Allow custom script may cause access denied issues**</span></span>

<span data-ttu-id="e11ef-112">Existují určité scénáře, ve kterých může funkce *Povolit vlastní skript* představovat odepření přístupu.</span><span class="sxs-lookup"><span data-stu-id="e11ef-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="e11ef-113">Seznam ovlivněných funkcí, důležité informace o zabezpečení a možnost tuto funkci zakázat.</span><span class="sxs-lookup"><span data-stu-id="e11ef-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="e11ef-114">Navštivte prosím [Povolení nebo zákaz vlastního skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="e11ef-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>

