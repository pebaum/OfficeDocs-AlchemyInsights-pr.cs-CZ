---
title: Omezení SharePointu Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.openlocfilehash: 9af4f09d50992c04a1f3d5a164093049a3ec3517
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931435"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="fd13f-102">Omezení SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="fd13f-102">SharePoint Online throttling</span></span>

<span data-ttu-id="fd13f-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="fd13f-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="fd13f-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="fd13f-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="fd13f-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="fd13f-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="fd13f-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="fd13f-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="fd13f-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="fd13f-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="fd13f-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="fd13f-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="fd13f-109">**Omezení SharePointu Online**</span><span class="sxs-lookup"><span data-stu-id="fd13f-109">**SharePoint Online throttling**</span></span>

<span data-ttu-id="fd13f-110">SharePoint Online používá omezení k udržení optimálního výkonu a spolehlivosti služby SharePointu Online.</span><span class="sxs-lookup"><span data-stu-id="fd13f-110">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="fd13f-111">Omezení omezuje počet akcí uživatele nebo souběžných volání (podle skriptu nebo kódu), aby se zabránilo nadměrnému využívání prostředků.</span><span class="sxs-lookup"><span data-stu-id="fd13f-111">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> <span data-ttu-id="fd13f-112">Pro více informací navštivte níže uvedené odkazy.</span><span class="sxs-lookup"><span data-stu-id="fd13f-112">For more information, please visit the links below.</span></span>

- [<span data-ttu-id="fd13f-113">Vyhněte se omezení nebo zablokování v SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="fd13f-113">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="fd13f-114">Migrace dat a omezení spo</span><span class="sxs-lookup"><span data-stu-id="fd13f-114">Data Migration and SPO Throttling </span></span>](https://blogs.technet.microsoft.com/sposupport/2017/08/12/data-migration-and-spo-service-throttling/)

- [<span data-ttu-id="fd13f-115">Rychlost migrace SharePointu Online a OneDrivu</span><span class="sxs-lookup"><span data-stu-id="fd13f-115">SharePoint Online and OneDrive Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

 - [<span data-ttu-id="fd13f-116">Zpracování omezení SharePointu Online pomocí exponenciálního vypnutí</span><span class="sxs-lookup"><span data-stu-id="fd13f-116">Handle SharePoint Online throttling by using exponential back off</span></span>](https://docs.microsoft.com/sharepoint/dev/solution-guidance/handle-sharepoint-online-throttling-by-using-exponential-back-off)

- [<span data-ttu-id="fd13f-117">Plánování kapacity a testování zatížení SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="fd13f-117">Capacity planning and load testing SharePoint Online</span></span>](https://docs.microsoft.com/office365/enterprise/capacity-planning-and-load-testing-sharepoint-online)

