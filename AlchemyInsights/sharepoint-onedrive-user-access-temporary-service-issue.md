---
title: Problémy s výkonem- SharePoint nebo OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 2dc0cd5f1641298853443d364eb9434ec1d9cd5a
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511141"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="a3c22-102">SharePoint nebo OneDrive Pomalé, Nepřístupné nebo nedostupné pro více uživatelů</span><span class="sxs-lookup"><span data-stu-id="a3c22-102">SharePoint or OneDrive Slow, Inaccessible or Unavailable for Multiple Users</span></span>

<span data-ttu-id="a3c22-103">Pokud web OneDrivu nebo SharePointu není dostupný pro více uživatelů, kteří k nim dříve měli přístup, může se nacpoutit na dočasný problém se službou.</span><span class="sxs-lookup"><span data-stu-id="a3c22-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> <span data-ttu-id="a3c22-104">[Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="a3c22-104">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

<span data-ttu-id="a3c22-105">**Přidání a licencování uživatele**</span><span class="sxs-lookup"><span data-stu-id="a3c22-105">**Add and license the user**</span></span>

<span data-ttu-id="a3c22-106">Ujistěte se, že [přiřazujete licence uživatelům v Microsoftu 365 pro firmy](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span><span class="sxs-lookup"><span data-stu-id="a3c22-106">Ensure that you [Assign licenses to users in Microsoft 365 for business](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span></span>


<span data-ttu-id="a3c22-107">**Přiřazení oprávnění**</span><span class="sxs-lookup"><span data-stu-id="a3c22-107">**Assign Permissions**</span></span>

<span data-ttu-id="a3c22-108">Pokud uživateli byla přiřazena licence služby Sharepoint a stále dostává zprávu o odepření přístupu, ujistěte se, že je mu přiřazena [příslušná úroveň oprávnění.](https://docs.microsoft.com/sharepoint/understanding-permission-levels)</span><span class="sxs-lookup"><span data-stu-id="a3c22-108">If the user has been assigned a Sharepoint license and is still receiving an access denied message, please ensure they have the [appropriate permission level](https://docs.microsoft.com/sharepoint/understanding-permission-levels) assigned.</span></span>

<span data-ttu-id="a3c22-109">**Zvažte použití funkce žádosti o přístup**</span><span class="sxs-lookup"><span data-stu-id="a3c22-109">**Consider using the access request feature**</span></span>

<span data-ttu-id="a3c22-110">[Funkce žádosti o přístup](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) umožňuje uživatelům požádat o přístup k obsahu, ke kterému aktuálně nemají oprávnění.</span><span class="sxs-lookup"><span data-stu-id="a3c22-110">The [access request feature](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) allows people to request access to content that they do not currently have permission to see.</span></span>

<span data-ttu-id="a3c22-111">**Povolit vlastní skript může způsobit problémy s přístupem.**</span><span class="sxs-lookup"><span data-stu-id="a3c22-111">**Allow custom script may cause access denied issues**</span></span>

<span data-ttu-id="a3c22-112">Existují určité scénáře, kde *povolit vlastní skript* funkce může být prezentace přístup odepřen.</span><span class="sxs-lookup"><span data-stu-id="a3c22-112">There are certain scenarios where the *Allow custom script* feature may be presenting an access denied.</span></span> <span data-ttu-id="a3c22-113">Seznam ovlivněných funkcí, důležité informace o zabezpečení a možnost zakázat tuto funkci.</span><span class="sxs-lookup"><span data-stu-id="a3c22-113">For a list of features affected, security considerations and the ability to disable the feature.</span></span> <span data-ttu-id="a3c22-114">Navštivte [stránku Povolit nebo zabránit vlastnímu skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="a3c22-114">Please visit [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>

