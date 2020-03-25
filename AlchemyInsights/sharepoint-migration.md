---
title: Migrace možností do SharePointu Online
ms.author: pebaum
author: v-miegge
manager: v-cojank
ms.date: 11/04/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: c8c339c9-2e50-4daa-aa91-3eb5053e2bc6
ms.openlocfilehash: 830b39c51658cbc02f4be81acdfdf3b164a8df70
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932723"
---
# <a name="migrate-options-to-sharepoint-online"></a><span data-ttu-id="e795b-102">Migrace možností do SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="e795b-102">Migrate options to SharePoint Online</span></span>

<span data-ttu-id="e795b-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="e795b-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="e795b-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="e795b-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="e795b-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="e795b-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="e795b-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="e795b-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="e795b-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="e795b-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="e795b-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="e795b-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="e795b-109">**Možnosti migrace**</span><span class="sxs-lookup"><span data-stu-id="e795b-109">**Migration options**</span></span>

<span data-ttu-id="e795b-110">V závislosti na velikosti a množství souborů, které potřebujete přesunout, jsou k dispozici různé možnosti migrace obsahu do SharePointu Online, ale podívejte se na seznam [možností,](https://docs.microsoft.com/sharepointmigration/migrate-to-sharepoint-online)které jsou k dispozici zde .</span><span class="sxs-lookup"><span data-stu-id="e795b-110">There are different options available to migrate content to SharePoint Online, depending on the size and quantity of files you need to move, please see a list of options [located here](https://docs.microsoft.com/sharepointmigration/migrate-to-sharepoint-online).</span></span>

<span data-ttu-id="e795b-111">Další informace o migraci obsahu naleznete na níže uvedených odkazech.</span><span class="sxs-lookup"><span data-stu-id="e795b-111">For more information on content migration, please visit the links below.</span></span>

- [<span data-ttu-id="e795b-112">Nástroj pro migraci služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="e795b-112">Sharepoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)

- [<span data-ttu-id="e795b-113">Začínáme se Správcem migrace</span><span class="sxs-lookup"><span data-stu-id="e795b-113">Get started with the Migration Manager</span></span>](https://docs.microsoft.com/sharepointmigration/mm-get-started)

- [<span data-ttu-id="e795b-114">Rychlost migrace Sharepointu Online a ODB</span><span class="sxs-lookup"><span data-stu-id="e795b-114">Sharepoint Online and ODB Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

- [<span data-ttu-id="e795b-115">Vyhněte se omezení nebo zablokování v SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="e795b-115">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="e795b-116">Nástroj pro hodnocení migrace služby SharePoint (SMAT)</span><span class="sxs-lookup"><span data-stu-id="e795b-116">SharePoint Migration Assessment Tool (SMAT)</span></span>](https://www.microsoft.com/download/details.aspx?id=53598&amp;751be11f-ede8-5a0c-058c-2ee190a24fa6=True)

<span data-ttu-id="e795b-117">**Poznámka:** V současné době nástroj migrace sharepointového nástroje podporuje jenom migrace ze SharePointu 2010 a 2013.</span><span class="sxs-lookup"><span data-stu-id="e795b-117">**Note**: Currently the SharePoint Migration tool only support migrations from SharePoint 2010  and 2013.</span></span> <span data-ttu-id="e795b-118">Verze 2016 nebo 2019 nejsou v současné době podporovány.</span><span class="sxs-lookup"><span data-stu-id="e795b-118">Version 2016 or 2019 are not supported at this time.</span></span>
