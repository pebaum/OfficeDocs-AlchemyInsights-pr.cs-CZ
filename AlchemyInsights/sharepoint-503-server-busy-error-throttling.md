---
title: Omezení online služby SharePoint
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 5fdbb315698a58145e5437b0a7b127ce0062a76f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048609"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="52abb-102">Omezení online služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="52abb-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="52abb-103">Při pokusu o přechod na weby služby SharePoint nebo OneDrive se uživatelům může zobrazit server 503 s chybou.</span><span class="sxs-lookup"><span data-stu-id="52abb-103">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="52abb-104">Tato chyba může být způsobena omezením v rámci služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="52abb-104">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="52abb-105">Služba SharePoint Online používá omezení k udržování optimálního výkonu a spolehlivosti služby SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="52abb-105">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="52abb-106">Omezení omezuje počet uživatelských akcí nebo souběžných volání (podle skriptu nebo kódu), aby zabránil přetížení prostředků.</span><span class="sxs-lookup"><span data-stu-id="52abb-106">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="52abb-107">Pokud se vám dostane omezení, 99% času z důvodu vlastního kódu.</span><span class="sxs-lookup"><span data-stu-id="52abb-107">If you do get throttled, 99% of the time it is because of custom code.</span></span>

<span data-ttu-id="52abb-108">Další informace týkající se omezení naleznete [v tématu služby SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online), které není třeba omezením nebo zablokováno.</span><span class="sxs-lookup"><span data-stu-id="52abb-108">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="52abb-109">Pokud se domníváte, že tato chyba nesouvisí s omezením, můžete zkontrolovat, zda se v nájemci vyskytne aktivní údržba, a to přechodem do [centra zpráv](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="52abb-109">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="52abb-110">Nakonec se ujistěte, že navštívíte stránku [stav služby](https://portal.office.com/adminportal/home#/servicehealth) , abyste mohli zjistit, ke kterým událostem dochází.</span><span class="sxs-lookup"><span data-stu-id="52abb-110">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

