---
title: Omezení služby SharePoint Online
ms.author: kirks
author: Techwriter40
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: b157ce22962ac1616d6e9b3a5475edaec7fed9f7
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34761252"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="6158c-102">Omezení služby SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6158c-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="6158c-103">Uživatelům se může zobrazit 503 server je zaneprázdněn Chyba při pokusu o přechod na weby služby SharePoint nebo OneDrive.</span><span class="sxs-lookup"><span data-stu-id="6158c-103">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="6158c-104">Tato chyba může být způsobeno omezení v rámci služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6158c-104">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="6158c-105">SharePoint Online používá omezení k udržení optimálního výkonu a spolehlivosti služby SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="6158c-105">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="6158c-106">Omezení počet akcí uživatele nebo souběžných volání (pomocí skriptu nebo kód) zabránit nadměrné prostředky.</span><span class="sxs-lookup"><span data-stu-id="6158c-106">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="6158c-107">Pokud můžete získat omezena, 99 % času je z důvodu vlastního kódu.</span><span class="sxs-lookup"><span data-stu-id="6158c-107">If you do get throttled, 99% of the time it is because of custom code.</span></span>

<span data-ttu-id="6158c-108">Další informace o omezení naleznete v tématu [Avoid získání omezena nebo blokovány v Online služby SharePoint](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="6158c-108">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="6158c-109">Pokud se domníváte, že tato chyba nemá vliv na omezení, můžete zkontrolovat, zda je aktivní údržby, které se vyskytují u vašeho klienta tak, že přejdete do [Centra zpráv](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="6158c-109">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="6158c-110">Nakonec se ujistěte, že navštívíte stránku [Zdravotní služby](https://portal.office.com/adminportal/home#/servicehealth) ke kontrole všech informačních zpravodajů/incidentů, ke kterým může docházet.</span><span class="sxs-lookup"><span data-stu-id="6158c-110">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

