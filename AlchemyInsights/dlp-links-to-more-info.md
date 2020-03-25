---
title: Další informace o problémech s dlp
ms.author: pebaum
author: pebaum
manager: laurawi
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2447"
- "3200001"
ms.openlocfilehash: 6525cee0555f1ae67b7d4e32445b9a1537d4a804
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932687"
---
# <a name="information-about-dlp-issues"></a><span data-ttu-id="58cc9-102">Informace o problémech s dlp</span><span class="sxs-lookup"><span data-stu-id="58cc9-102">Information about DLP issues</span></span>

<span data-ttu-id="58cc9-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="58cc9-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="58cc9-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="58cc9-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="58cc9-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="58cc9-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="58cc9-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="58cc9-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="58cc9-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="58cc9-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="58cc9-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="58cc9-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="58cc9-109">**Informace o zásadách ochrany před únikem informací**</span><span class="sxs-lookup"><span data-stu-id="58cc9-109">**Information on DLP policy**</span></span>

<span data-ttu-id="58cc9-110">Pomocí zásad ochrany před únikem informací můžete identifikovat, monitorovat a automaticky chránit citlivé informace v office 365.</span><span class="sxs-lookup"><span data-stu-id="58cc9-110">With a DLP policy, you can identify, monitor, and automatically protect sensitive information across Office 365.</span></span>

<span data-ttu-id="58cc9-111">Prosím, navštivte tyto odkazy pro více informací:</span><span class="sxs-lookup"><span data-stu-id="58cc9-111">Please visit these links for more information:</span></span>

- [<span data-ttu-id="58cc9-112">Přehled prevence ztráty dat</span><span class="sxs-lookup"><span data-stu-id="58cc9-112">Overview of data loss prevention</span></span>](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies)
- [<span data-ttu-id="58cc9-113">Co typy citlivých informací hledají</span><span class="sxs-lookup"><span data-stu-id="58cc9-113">What the sensitive information types look for</span></span>](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)
- [<span data-ttu-id="58cc9-114">Vytvoření vlastního typu citlivých informací</span><span class="sxs-lookup"><span data-stu-id="58cc9-114">Create a custom sensitive information type</span></span>](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type)
- [<span data-ttu-id="58cc9-115">Odesílání e-mailových oznámení a zobrazování tipů pro zásady</span><span class="sxs-lookup"><span data-stu-id="58cc9-115">Send email notifications and show policy tips</span></span>](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
- [<span data-ttu-id="58cc9-116">Ochrana souborů SharePointu Online pomocí popisků pro uchovávání informací a dlp</span><span class="sxs-lookup"><span data-stu-id="58cc9-116">Protect SharePoint Online files with retention labels and DLP</span></span>](https://docs.microsoft.com/office365/securitycompliance/protect-sharepoint-online-files-with-office-365-labels-and-dlp)
- [<span data-ttu-id="58cc9-117">DLP a Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="58cc9-117">DLP and Microsoft Teams</span></span>](https://docs.microsoft.com/office365/securitycompliance/dlp-microsoft-teams)

<span data-ttu-id="58cc9-118">Chcete-li data otestovat pomocí předdefinovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Klasifikace** > **Typy citlivých informací**.</span><span class="sxs-lookup"><span data-stu-id="58cc9-118">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="58cc9-119">Další informace naleznete v [tématu Test vlastní chod citlivých informací typy](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="58cc9-119">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>