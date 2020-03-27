---
title: Výkon migrace SharePointu
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "2700"
ms.openlocfilehash: 812444589d5a5bf766bbc6f466077d4ca829d79f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932004"
---
# <a name="sharepoint-migration-performance"></a><span data-ttu-id="b6ae2-102">Výkon migrace SharePointu</span><span class="sxs-lookup"><span data-stu-id="b6ae2-102">SharePoint migration performance</span></span>

<span data-ttu-id="b6ae2-103">**Důležité:** řada zákazníků SharePointu Online a OneDrivu spouští důležité podnikové aplikace s využitím služby, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="b6ae2-104">Patří mezi ně migrace obsahu, ochrana před únikem informací (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="b6ae2-105">Během této mimořádné doby realizujeme opatření s cílem zajistit, aby služby SharePointu Online a OneDrivu byly vysoce dostupné a spolehlivé pro vaše uživatele, kteří na této službě v rámci scénářů vzdálené práce závisejí víc než dřív.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="b6ae2-106">Pro zajištění tohoto cíle jsme v pracovních dnech v pracovní době implementovali přísnější limity omezování pro aplikace na pozadí (migrace, ochrana před únikem informací a řešení zálohování).</span><span class="sxs-lookup"><span data-stu-id="b6ae2-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="b6ae2-107">Měli byste očekávat, že tyto aplikace budou mít během této doby velmi omezenou propustnost.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="b6ae2-108">Ale během večerních a víkendových hodin příslušné oblasti bude služba připravená zpracovat výrazně vyšší objem žádostí od aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="b6ae2-109">**Výkon migrace**</span><span class="sxs-lookup"><span data-stu-id="b6ae2-109">**Migration performance**</span></span>

<span data-ttu-id="b6ae2-110">Na výkon migrace může mít vliv síťová infrastruktura, velikost souborů, čas migrace a omezování.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-110">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling.</span></span> <span data-ttu-id="b6ae2-111">Pochopení těchto možností vám pomůže naplánovat vaši migraci a zajistit její maximální efektivitu.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-111">Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

<span data-ttu-id="b6ae2-112">Pokud chcete získat další informace, podívejte se na níže uvedené odkazy.</span><span class="sxs-lookup"><span data-stu-id="b6ae2-112">For more information, please visit the links below.</span></span>

- [<span data-ttu-id="b6ae2-113">Rychlost migrace SharePointu Online a ODB</span><span class="sxs-lookup"><span data-stu-id="b6ae2-113">Sharepoint Online and ODB Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

- [<span data-ttu-id="b6ae2-114">Vyhnutí se omezení nebo zablokování v SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="b6ae2-114">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="b6ae2-115">Stažení a instalace nástroje pro migraci SharePointu</span><span class="sxs-lookup"><span data-stu-id="b6ae2-115">Download and install the SharePoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)
