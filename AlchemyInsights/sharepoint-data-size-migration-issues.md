---
title: Problémy při migraci dat do SharePointu Online
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "1885"
ms.openlocfilehash: b53a98480bab48497274c7358f7e606caa477f5a
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931687"
---
# <a name="issues-while-migrating-data-to-sharepoint-online"></a><span data-ttu-id="b7427-102">Problémy při migraci dat do SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="b7427-102">Issues while migrating data to SharePoint Online</span></span>

<span data-ttu-id="b7427-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="b7427-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="b7427-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="b7427-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="b7427-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="b7427-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="b7427-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="b7427-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="b7427-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="b7427-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="b7427-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="b7427-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="b7427-109">**Migrace více než 100 TB dat**</span><span class="sxs-lookup"><span data-stu-id="b7427-109">**Migrating over 100TB of data**</span></span>

<span data-ttu-id="b7427-110">Zdá se, že migrujete přes 100 TB dat do SharePointu Online.</span><span class="sxs-lookup"><span data-stu-id="b7427-110">It appears you are migrating over 100TB of data to SharePoint Online.</span></span> <span data-ttu-id="b7427-111">Postupujte podle následujících kroků, abychom vám mohli pomoci co nejdříve.</span><span class="sxs-lookup"><span data-stu-id="b7427-111">Please follow the steps below so we may assist you as soon as possible.</span></span> 

1. <span data-ttu-id="b7427-112">Vyberte **nový požadavek na službu**a potom **nový požadavek na službu**.</span><span class="sxs-lookup"><span data-stu-id="b7427-112">Select **New Service Request**, and then **New Service Request**.</span></span> 
2. <span data-ttu-id="b7427-113">Ponechte název a popis jako **migrace sharepointového zařízení přes 100 TB**.</span><span class="sxs-lookup"><span data-stu-id="b7427-113">Leave the title and description as **SharePoint migration over 100TB**.</span></span>
3. <span data-ttu-id="b7427-114">Po odeslání letenky jej aktualizujte následujícími informacemi:</span><span class="sxs-lookup"><span data-stu-id="b7427-114">Once the ticket has been submitted, please update it with the following information:</span></span> 

    - <span data-ttu-id="b7427-115">Odhadovaná velikost migrace.</span><span class="sxs-lookup"><span data-stu-id="b7427-115">Estimated size of your migration.</span></span>
    - <span data-ttu-id="b7427-116">Odhad, kdy chcete zahájit a dokončit migraci.</span><span class="sxs-lookup"><span data-stu-id="b7427-116">An estimate of when you would like to start and complete your migration.</span></span>
    - <span data-ttu-id="b7427-117">Popište, odkud migrujete obsah, například SharePoint Server, Box, GDrive, Sdílené složky atd.</span><span class="sxs-lookup"><span data-stu-id="b7427-117">Describe where you are migrating your content from, such as SharePoint Server, Box, GDrive, File shares, etc..</span></span>


  

