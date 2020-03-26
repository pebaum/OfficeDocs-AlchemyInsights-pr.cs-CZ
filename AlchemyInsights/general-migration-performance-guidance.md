---
title: Obecné rady týkající se výkonu migrace
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
- "3179"
ms.openlocfilehash: 10a0069c41d2e5128b2592425d815364a83b730f
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932472"
---
# <a name="general-migration-performance-guidance"></a><span data-ttu-id="94fde-102">Obecné rady týkající se výkonu migrace</span><span class="sxs-lookup"><span data-stu-id="94fde-102">General migration performance guidance</span></span>

<span data-ttu-id="94fde-103">**Důležité:** Řada zákazníků SharePointu Online a OneDrivu spouští důležité podnikové aplikace s využitím služby, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="94fde-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="94fde-104">Patří mezi ně migrace obsahu, ochrana před únikem informací (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="94fde-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="94fde-105">Během této mimořádné doby realizujeme opatření s cílem zajistit, aby služby SharePointu Online a OneDrivu byly vysoce dostupné a spolehlivé pro vaše uživatele, kteří na této službě v rámci scénářů vzdálené práce závisejí víc než dřív.</span><span class="sxs-lookup"><span data-stu-id="94fde-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="94fde-106">Pro zajištění tohoto cíle jsme v pracovních dnech v pracovní době implementovali přísnější limity omezování pro aplikace na pozadí (migrace, ochrana před únikem informací a řešení zálohování).</span><span class="sxs-lookup"><span data-stu-id="94fde-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="94fde-107">Měli byste očekávat, že tyto aplikace budou mít během této doby velmi omezenou propustnost.</span><span class="sxs-lookup"><span data-stu-id="94fde-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="94fde-108">Ale během večerních a víkendových hodin příslušné oblasti bude služba připravená zpracovat výrazně vyšší objem žádostí od aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="94fde-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="94fde-109">**Rady týkající se výkonu migrace**</span><span class="sxs-lookup"><span data-stu-id="94fde-109">**Migration performance guidance**</span></span>

<span data-ttu-id="94fde-110">Na výkon migrace může mít vliv síťová infrastruktura, velikost souborů, čas migrace a omezování.</span><span class="sxs-lookup"><span data-stu-id="94fde-110">Migration performance can be impacted by network infrastructure, file size, migration time, and throttling.</span></span> <span data-ttu-id="94fde-111">Pochopení těchto možností vám pomůže naplánovat vaši migraci a zajistit její maximální efektivitu.</span><span class="sxs-lookup"><span data-stu-id="94fde-111">Understanding these will help you plan and maximize the efficiency of your migration.</span></span>

- [<span data-ttu-id="94fde-112">Obecné rady týkající se výkonu migrace</span><span class="sxs-lookup"><span data-stu-id="94fde-112">General migration performance guidance</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)
