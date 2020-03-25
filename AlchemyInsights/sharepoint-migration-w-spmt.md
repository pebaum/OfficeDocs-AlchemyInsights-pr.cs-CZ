---
title: Migrace služby SharePoint pomocí spmt
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "2594"
ms.openlocfilehash: e7719d1fc6dda0d5bd340775219401dade2933fe
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931543"
---
# <a name="sharepoint-migration-with-spmt"></a><span data-ttu-id="acac4-102">Migrace služby SharePoint pomocí spmt</span><span class="sxs-lookup"><span data-stu-id="acac4-102">SharePoint Migration with SPMT</span></span>

<span data-ttu-id="acac4-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="acac4-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="acac4-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="acac4-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="acac4-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="acac4-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="acac4-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="acac4-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="acac4-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="acac4-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="acac4-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="acac4-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="acac4-109">**Nástroj pro migraci služby SharePoint**</span><span class="sxs-lookup"><span data-stu-id="acac4-109">**SharePoint Migration Tool**</span></span>

<span data-ttu-id="acac4-110">Nástroj pro migraci služby SharePoint, který je navržen pro migraci od nejmenší sady souborů až po rozsáhlou migraci podniků, vám umožní přenášet informace do cloudu a využívat nejnovější spolupráci, inteligenci a řešení zabezpečení s Office 365.</span><span class="sxs-lookup"><span data-stu-id="acac4-110">Designed to be used for migrations ranging from the smallest set of files to a large scale enterprise migration, the SharePoint Migration Tool will allow you to transfer your information to the cloud and take advantage of the newest collaboration, intelligence, and security solutions with Office 365.</span></span>

- [<span data-ttu-id="acac4-111">Stažení a instalace Nástroje pro migraci sharepointu</span><span class="sxs-lookup"><span data-stu-id="acac4-111">Download and install the SharePoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)
- [<span data-ttu-id="acac4-112">Řešení běžných problémů a chyb SPMT</span><span class="sxs-lookup"><span data-stu-id="acac4-112">Troubleshooting common SPMT issues and errors</span></span>](https://docs.microsoft.com/sharepointmigration/troubleshooting-common-spmt-issues)
- [<span data-ttu-id="acac4-113">Poradce při potížích s instalací spmt</span><span class="sxs-lookup"><span data-stu-id="acac4-113">Troubleshooting SPMT installation issues</span></span>](https://docs.microsoft.com/sharepointmigration/spmt-install-issues#troubleshooting-spmt-installation-issues)
