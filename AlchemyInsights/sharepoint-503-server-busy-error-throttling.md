---
title: Omezení SharePointu Online
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 2aca55ac2fefbb2035140a759a77730dc905a4e9
ms.sourcegitcommit: 926e4ab6aa64ddc7a244de633421eb2b817541f2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42958711"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="ae011-102">Omezení SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="ae011-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="ae011-103">**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)</span><span class="sxs-lookup"><span data-stu-id="ae011-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="ae011-104">**Chyba serveru 503 je zaneprázdněna**</span><span class="sxs-lookup"><span data-stu-id="ae011-104">**503 server is busy error**</span></span>

<span data-ttu-id="ae011-105">Uživatelé mohou při pokusu o přechod na weby SharePointu nebo OneDrivu obdržet chybu zaneprázdněného serverem 503.</span><span class="sxs-lookup"><span data-stu-id="ae011-105">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="ae011-106">Tato chyba může být způsobena omezením v rámci služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="ae011-106">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="ae011-107">SharePoint Online používá omezení k udržení optimálního výkonu a spolehlivosti služby SharePointu Online.</span><span class="sxs-lookup"><span data-stu-id="ae011-107">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="ae011-108">Omezení omezuje počet akcí uživatele nebo souběžných volání (podle skriptu nebo kódu), aby se zabránilo nadměrnému využívání prostředků.</span><span class="sxs-lookup"><span data-stu-id="ae011-108">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="ae011-109">Další informace o omezení najdete [v tématu Vyhněte se omezení nebo zablokování v SharePointu Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="ae011-109">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="ae011-110">Pokud se domníváte, že tato chyba nesouvisí s omezením, můžete zkontrolovat, zda v tenantovi dochází k aktivní údržbě, a to tak, že přejdete do [Centra zpráv](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="ae011-110">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="ae011-111">Nakonec se ujistěte, že jste navštívili stránku [Stav služby a](https://portal.office.com/adminportal/home#/servicehealth) zkontrolovali případné informační zpravodaje nebo incidenty.</span><span class="sxs-lookup"><span data-stu-id="ae011-111">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

