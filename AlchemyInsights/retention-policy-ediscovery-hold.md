---
title: 2609-uchovávání-nebo-eDiscovery-hold
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994052"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a><span data-ttu-id="03f6b-102">Nelze odstranit položky ve službě SharePoint Online nebo OneDrive pro podnik</span><span class="sxs-lookup"><span data-stu-id="03f6b-102">Unable to delete items in SharePoint Online or OneDrive for Business</span></span>

<span data-ttu-id="03f6b-103">Je možné, že vy nebo vaši uživatelé nebudete moci odstranit položky ve službě SharePoint Online nebo OneDrive for Business, protože je použita zásada uchovávání informací, retenční štítek nebo blokování eDiscovery u služby SharePoint serveru OneDrive nebo u určité položky.</span><span class="sxs-lookup"><span data-stu-id="03f6b-103">You or your users may be unable to delete items in SharePoint Online or OneDrive for Business because a retention policy, retention label, or eDiscovery hold is applied to a SharePoint of OneDrive site or to a specific item.</span></span> <span data-ttu-id="03f6b-104">To zahrnuje také to, že nelze odstranit dokument, verzi dokumentu, složku, knihovnu dokumentů, seznam, aplikaci, web nebo kolekci webů.</span><span class="sxs-lookup"><span data-stu-id="03f6b-104">This includes being unable to delete a document, a document version, a folder, a document library, a list, an app, a site, or a site collection.</span></span> <span data-ttu-id="03f6b-105">Zde je několik příkladů chybových zpráv, které mohou být přijaty při pokusu o odstranění položky, která je uchovávané:</span><span class="sxs-lookup"><span data-stu-id="03f6b-105">Here are some examples of the error messages you may received if you try to delete an item that is being retained:</span></span>

- <span data-ttu-id="03f6b-106">"Tento web nelze odstranit, protože je zahrnut v zásadách uchovávání informací nebo uchování v systému eDiscovery."</span><span class="sxs-lookup"><span data-stu-id="03f6b-106">"This site cannot be deleted because it is included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="03f6b-107">"Tento server obsahuje zásady kompatibility, které blokují odstranění."</span><span class="sxs-lookup"><span data-stu-id="03f6b-107">"This site has a compliance policy set to block deletion"</span></span>
- <span data-ttu-id="03f6b-108">"Zásada kompatibility aktuálně blokuje odstranění tohoto webu"</span><span class="sxs-lookup"><span data-stu-id="03f6b-108">"A compliance policy is currently blocking this site deletion"</span></span>
- <span data-ttu-id="03f6b-109">Tuto kolekci webů nelze odstranit, protože obsahuje weby, které jsou zahrnuty v zásadách blokování nebo uchovávání informací systému eDiscovery.</span><span class="sxs-lookup"><span data-stu-id="03f6b-109">"This site collection can’t be deleted because it contains sites that are included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="03f6b-110">"Před odstraněním složky musíte odstranit všechny položky v této složce"</span><span class="sxs-lookup"><span data-stu-id="03f6b-110">"You have to delete all the items in this folder before you delete the folder"</span></span>
- <span data-ttu-id="03f6b-111">"Verze této položky nelze odstranit, protože jsou v zásadě blokování nebo jsou zásady uchovávání informací"</span><span class="sxs-lookup"><span data-stu-id="03f6b-111">"Versions of this item cannot be deleted because it is on hold or retention policy"</span></span>
- <span data-ttu-id="03f6b-112">"Při blokování nelze položku odstranit"</span><span class="sxs-lookup"><span data-stu-id="03f6b-112">"Item cannot be deleted while on hold"</span></span>
- <span data-ttu-id="03f6b-113">"Popisek použitý u této položky zabraňuje úpravám nebo odstraňování."</span><span class="sxs-lookup"><span data-stu-id="03f6b-113">"The label that's applied to this item prevents it from being edited or deleted"</span></span>
- <span data-ttu-id="03f6b-114">"Seznam nelze odstranit, pokud je v zásadách blokování nebo uchovávání informací"</span><span class="sxs-lookup"><span data-stu-id="03f6b-114">"List cannot be deleted while on hold or retention policy"</span></span>
- <span data-ttu-id="03f6b-115">"Seznam nelze odstranit, pokud je blokován nebo pokud je na ni aplikovaná zásada uchovávání informací."</span><span class="sxs-lookup"><span data-stu-id="03f6b-115">"The list cannot be deleted if it is blocked or if a retention policy is applied to it"</span></span>

<span data-ttu-id="03f6b-116">Chcete-li odstranit položky v jednom z těchto scénářů, je nutné odebrat zásady uchovávání informací, retenční štítek nebo blokování eDiscovery (nebo musí být web vyloučen z zásady uchovávání informací).</span><span class="sxs-lookup"><span data-stu-id="03f6b-116">To delete items in one of these scenarios, the retention policy, retention label, or eDiscovery hold has to be removed (or a site has to be excluded from a retention policy).</span></span> <span data-ttu-id="03f6b-117">Je třeba zakázat nebo vyloučit příslušné blokování, které způsobuje tento problém.</span><span class="sxs-lookup"><span data-stu-id="03f6b-117">You need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="03f6b-118">Po odebrání zásad nebo blokování uchovávání informací může změna trvat až 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="03f6b-118">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> 

<span data-ttu-id="03f6b-119">Informace o různých funkcích uchování a držení, které lze použít pro weby služby SharePoint a účty OneDrive, naleznete v některém z následujících témat.</span><span class="sxs-lookup"><span data-stu-id="03f6b-119">For information about about the different retention and hold features that can be applied to SharePoint sites and OneDrive accounts, see one of the following topics.</span></span>

- [<span data-ttu-id="03f6b-120">Přehled zásad uchovávání informací</span><span class="sxs-lookup"><span data-stu-id="03f6b-120">Overview of retention policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [<span data-ttu-id="03f6b-121">Přehled retenčních štítků</span><span class="sxs-lookup"><span data-stu-id="03f6b-121">Overview of retention labels</span></span>](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [<span data-ttu-id="03f6b-122">Správa blokování v rozšířeném eDiscovery</span><span class="sxs-lookup"><span data-stu-id="03f6b-122">Manage holds in Advanced eDiscovery</span></span>](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [<span data-ttu-id="03f6b-123">eDiscovery uchovává</span><span class="sxs-lookup"><span data-stu-id="03f6b-123">eDiscovery holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [<span data-ttu-id="03f6b-124">Zásady zavírání a odstraňování starších serverů</span><span class="sxs-lookup"><span data-stu-id="03f6b-124">Legacy site closure and deletion policies</span></span>](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)
