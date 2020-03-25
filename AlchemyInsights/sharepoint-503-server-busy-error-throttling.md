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
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931219"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="0de64-102">Omezení SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="0de64-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="0de64-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="0de64-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="0de64-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="0de64-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="0de64-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="0de64-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="0de64-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="0de64-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="0de64-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="0de64-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="0de64-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="0de64-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="0de64-109">**Chyba serveru 503 je zaneprázdněna**</span><span class="sxs-lookup"><span data-stu-id="0de64-109">**503 server is busy error**</span></span>

<span data-ttu-id="0de64-110">Uživatelé mohou při pokusu o přechod na weby SharePointu nebo OneDrivu obdržet chybu zaneprázdněného serverem 503.</span><span class="sxs-lookup"><span data-stu-id="0de64-110">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="0de64-111">Tato chyba může být způsobena omezením v rámci služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="0de64-111">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="0de64-112">SharePoint Online používá omezení k udržení optimálního výkonu a spolehlivosti služby SharePointu Online.</span><span class="sxs-lookup"><span data-stu-id="0de64-112">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="0de64-113">Omezení omezuje počet akcí uživatele nebo souběžných volání (podle skriptu nebo kódu), aby se zabránilo nadměrnému využívání prostředků.</span><span class="sxs-lookup"><span data-stu-id="0de64-113">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="0de64-114">Další informace o omezení najdete [v tématu Vyhněte se omezení nebo zablokování v SharePointu Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="0de64-114">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="0de64-115">Pokud se domníváte, že tato chyba nesouvisí s omezením, můžete zkontrolovat, zda v tenantovi dochází k aktivní údržbě, a to tak, že přejdete do [Centra zpráv](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="0de64-115">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="0de64-116">Nakonec se ujistěte, že jste navštívili stránku [Stav služby a](https://portal.office.com/adminportal/home#/servicehealth) zkontrolovali případné informační zpravodaje nebo incidenty.</span><span class="sxs-lookup"><span data-stu-id="0de64-116">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>

