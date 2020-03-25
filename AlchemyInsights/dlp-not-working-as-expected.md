---
title: DLP nefunguje podle očekávání
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: a56e18ddadef3a2f9056978b8542c1dba8f29665
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932615"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="effe5-102">DLP nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="effe5-102">DLP not working as expected</span></span>

<span data-ttu-id="effe5-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="effe5-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="effe5-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="effe5-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="effe5-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="effe5-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="effe5-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="effe5-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="effe5-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="effe5-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="effe5-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="effe5-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

 <span data-ttu-id="effe5-109">**Nastavení ochrany před únikem a ochrany před únikem**</span><span class="sxs-lookup"><span data-stu-id="effe5-109">**Setting up DLP**</span></span>

<span data-ttu-id="effe5-110">Máte problémy s **prevencí před ztrátou dat (DLP)** v Office 365 nefunguje podle očekávání?</span><span class="sxs-lookup"><span data-stu-id="effe5-110">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="effe5-111">Pokud ano, ujistěte se, že **vaše zásady ochrany před únikem informací** jsou správně nastaveny a že data obsahují to, co **zásady ochrany před únikem informací** hledají při vyhodnocování.</span><span class="sxs-lookup"><span data-stu-id="effe5-111">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="effe5-112">Zásady ochrany před únikem informací umožňují identifikovat a chránit citlivé informace ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="effe5-112">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="effe5-113">Chcete-li nastavit zásady ochrany před únikem informací, použijte informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="effe5-113">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="effe5-114">**Co zásady ochrany před únikem a ochrany údajů**</span><span class="sxs-lookup"><span data-stu-id="effe5-114">**What DLP policies look for**</span></span>
  
<span data-ttu-id="effe5-115">Při použití **předdefinovaných typů citlivých informací** v Centru zabezpečení a dodržování předpisů Office 365 hledají zásady ochrany před únikem informací konkrétní vzory a prvky při zjišťování těchto citlivých typů.</span><span class="sxs-lookup"><span data-stu-id="effe5-115">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="effe5-116">**Předdefinované typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="effe5-116">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="effe5-117">Informace o předdefinovaných typech Sensitive a o tom, co zásady ochrany před únikem informací hledají při zjišťování typu Sensitive, naleznete v [tématu What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="effe5-117">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="effe5-118">**Vlastní typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="effe5-118">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="effe5-119">Pokud se pokoušíte vytvořit vlastní typy citlivých informací, použijte následující článek, kde naleznete informace o vytvoření vlastního citlivého typu: [Vytvoření vlastního typu citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="effe5-119">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="effe5-120">**Testování zásad ochrany před únikem a ochrany údajů**</span><span class="sxs-lookup"><span data-stu-id="effe5-120">**Test a DLP policy**</span></span>

<span data-ttu-id="effe5-121">Chcete-li data otestovat pomocí předdefinovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Klasifikace** > **Typy citlivých informací**.</span><span class="sxs-lookup"><span data-stu-id="effe5-121">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="effe5-122">Další informace naleznete v [tématu Test vlastní chod citlivých informací typy](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="effe5-122">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="effe5-123">**Sestavy**</span><span class="sxs-lookup"><span data-stu-id="effe5-123">**Reports**</span></span>
  
- <span data-ttu-id="effe5-124">Získejte přehledy citlivých dat pomocí [přehledů ochrany před únikem informací.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="effe5-124">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="effe5-125">Podívejte se na konkrétní podrobnosti události pomocí [zprávy o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="effe5-125">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
