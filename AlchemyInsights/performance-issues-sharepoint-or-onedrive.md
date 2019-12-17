---
title: Problémy s výkonem – SharePoint nebo OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1133"
- "2397"
- "2418"
- "5200018"
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: aecbf4043c6456ece73f7deed6b068040f0691a2
ms.sourcegitcommit: 0fb89d8106fe409ab1b78e50f5357ffc2252f7c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/17/2019
ms.locfileid: "40068388"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a><span data-ttu-id="cc8de-102">Služba SharePoint nebo OneDrive je pomalá, nedostupná nebo nedostupná pro více uživatelů</span><span class="sxs-lookup"><span data-stu-id="cc8de-102">SharePoint or OneDrive slow, inaccessible, or unavailable for multiple users</span></span>

<span data-ttu-id="cc8de-103">Služba SharePoint nebo OneDrive může být pomalá, nedostupná nebo nedostupná nebo může zobrazit službu nedostupnou nebo 503 chyb, a to z několika důvodů:</span><span class="sxs-lookup"><span data-stu-id="cc8de-103">SharePoint or OneDrive may be slow, inaccessible, or unavailable, or may display service unavailable or 503 errors, for several reasons:</span></span>
  
- <span data-ttu-id="cc8de-104">Pokud je web služby SharePoint nebo OneDrive pomalý nebo zpožděn pro více uživatelů, může se jednat o dočasný problém se službou, kde se uživatelům při přístupu k webům SharePoint nebo k obsahu OneDrive vyskytnou občasné prodlevy nebo chyby navigace.</span><span class="sxs-lookup"><span data-stu-id="cc8de-104">If your SharePoint or OneDrive site is slow or delayed for multiple users, there may be a temporary service issue where users experience intermittent delays or navigation errors when accessing SharePoint sites or OneDrive content.</span></span> <span data-ttu-id="cc8de-105">Zkontrolujte [řídicí panel stavu služby](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) a zjistěte, zda je v organizaci ohrožena.</span><span class="sxs-lookup"><span data-stu-id="cc8de-105">Check the [Service health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>
  
- <span data-ttu-id="cc8de-106">Při pokusu o přechod na weby služby SharePoint nebo OneDrive se uživatelům může zobrazit chybová zpráva o tom, že *server 503 je zaneprázdněn* .</span><span class="sxs-lookup"><span data-stu-id="cc8de-106">Users may receive a *503 server is busy* error when attempting to navigate to SharePoint or OneDrive sites.</span></span> <span data-ttu-id="cc8de-107">Tato chyba může být způsobena omezením v rámci služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cc8de-107">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="cc8de-108">Služba SharePoint Online používá omezení k udržování optimálního výkonu a spolehlivosti služby SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="cc8de-108">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="cc8de-109">Omezení omezuje počet uživatelských akcí nebo souběžných volání (podle skriptu nebo kódu), aby zabránil přetížení prostředků.</span><span class="sxs-lookup"><span data-stu-id="cc8de-109">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="cc8de-110">Další informace týkající se omezení naleznete [v tématu služby SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online), které není třeba omezením nebo zablokováno.</span><span class="sxs-lookup"><span data-stu-id="cc8de-110">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

- <span data-ttu-id="cc8de-111">Pokud dochází k pomalému výkonu na **klasickém** nebo **moderním** webu nebo stránce služby SharePoint, použijte k analýze stránek [Nástroj pro diagnostiku stránek](https://aka.ms/perftool) .</span><span class="sxs-lookup"><span data-stu-id="cc8de-111">If you experience slow performance with a **classic** or **modern** SharePoint site or page, utilize the [Page Diagnostic tool](https://aka.ms/perftool) to analyze the pages.</span></span>
  
- <span data-ttu-id="cc8de-112">Pokud stále dochází k obecnému pomalému výkonu, prostudujte si zdroje v dolní části tohoto článku: [Úvod k optimalizaci výkonu služby SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334)</span><span class="sxs-lookup"><span data-stu-id="cc8de-112">If you still experience general slow performance, please review the resources at the bottom of this article: [Introduction to performance tuning for SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334)</span></span>
  