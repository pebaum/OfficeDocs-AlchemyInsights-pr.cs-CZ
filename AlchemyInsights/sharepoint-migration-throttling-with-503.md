---
title: Omezení migrace sharepointu s 503 chybami
ms.author: pebaum
author: pebaum
ms.date: 8/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000136"
- "2541"
ms.openlocfilehash: 7e12c74d33e3cee7c626ad899a4e7f2f0a409bca
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931651"
---
# <a name="sharepoint-migration-throttling-with-503-errors"></a><span data-ttu-id="9b4c8-102">Omezení migrace sharepointu s 503 chybami</span><span class="sxs-lookup"><span data-stu-id="9b4c8-102">SharePoint migration throttling with 503 errors</span></span>

<span data-ttu-id="9b4c8-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="9b4c8-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="9b4c8-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="9b4c8-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="9b4c8-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="9b4c8-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="9b4c8-109">**503 chyb při migraci na SharePoint Online**</span><span class="sxs-lookup"><span data-stu-id="9b4c8-109">**503 errors when migrating to SharePoint Online**</span></span>

<span data-ttu-id="9b4c8-110">Zdá se, že migrujete na SharePoint Online a přijímáte 503 chyb.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-110">It appears you are migrating to SharePoint Online and receiving 503 errors.</span></span> <span data-ttu-id="9b4c8-111">Postupujte podle následujících kroků, abychom vám mohli pomoci co nejdříve.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-111">Please follow the steps below so we may assist you as soon as possible.</span></span> 

1. <span data-ttu-id="9b4c8-112">Klepněte na tlačítko **Kontaktovat podporu**a potom na **položku Nový požadavek na službu**.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-112">Click **Contact Support**, and then **New Service Request**.</span></span>
2. <span data-ttu-id="9b4c8-113">Název a popis zadejte **omezení migrace služby SharePoint pomocí 503**.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-113">For the title and description, type **SharePoint Migration Throttling with 503**.</span></span>
3. <span data-ttu-id="9b4c8-114">Po odeslání letenky jej aktualizujte následujícími informacemi:</span><span class="sxs-lookup"><span data-stu-id="9b4c8-114">Once the ticket has been submitted, please update it with the following information:</span></span>
    - <span data-ttu-id="9b4c8-115">Kolik zbývá migrace (například kolik TB?).</span><span class="sxs-lookup"><span data-stu-id="9b4c8-115">How much left of migration (for example, how many TBs?).</span></span>
    - <span data-ttu-id="9b4c8-116">Počáteční a koncové datum migrace.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-116">Migration start and end date.</span></span>
    - <span data-ttu-id="9b4c8-117">Popište, odkud migrujete obsah, například SharePoint Server, Box, GDrive, Sdílené složky atd.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-117">Describe where you are migrating your content from, such as SharePoint Server, Box, GDrive, File shares, etc..</span></span>
    - <span data-ttu-id="9b4c8-118">Odhadněte počet chyb omezení (například x omezení za hodinu?) a kdy došlo k omezení.</span><span class="sxs-lookup"><span data-stu-id="9b4c8-118">Estimate the number of throttling errors (for example, x throttle per hour?) and when did the throttling happen.</span></span>
    - <span data-ttu-id="9b4c8-119">Který nástroj pro migraci používáte (například SPMT nebo ShareGate).</span><span class="sxs-lookup"><span data-stu-id="9b4c8-119">Which migration tool you are using (for example, SPMT or ShareGate).</span></span>


