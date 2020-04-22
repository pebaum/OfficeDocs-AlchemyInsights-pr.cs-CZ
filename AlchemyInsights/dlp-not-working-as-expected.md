---
title: DLP nefunguje podle očekávání
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: efb4a19f345fe6b8a1e8bb72abeba4a923c05777
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704406"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="92a94-102">DLP nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="92a94-102">DLP not working as expected</span></span>

<span data-ttu-id="92a94-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="92a94-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

 <span data-ttu-id="92a94-104">**Nastavení ochrany před únikem a ochrany před únikem**</span><span class="sxs-lookup"><span data-stu-id="92a94-104">**Setting up DLP**</span></span>

<span data-ttu-id="92a94-105">Máte problémy s **prevencí před ztrátou dat (DLP)** v Office 365 nefunguje podle očekávání?</span><span class="sxs-lookup"><span data-stu-id="92a94-105">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="92a94-106">Pokud ano, ujistěte se, že **vaše zásady ochrany před únikem informací** jsou správně nastaveny a že data obsahují to, co **zásady ochrany před únikem informací** hledají při vyhodnocování.</span><span class="sxs-lookup"><span data-stu-id="92a94-106">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="92a94-107">Zásady ochrany před únikem informací umožňují identifikovat a chránit citlivé informace ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="92a94-107">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="92a94-108">Chcete-li nastavit zásady ochrany před únikem informací, použijte informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="92a94-108">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="92a94-109">**Co zásady ochrany před únikem a ochrany údajů**</span><span class="sxs-lookup"><span data-stu-id="92a94-109">**What DLP policies look for**</span></span>
  
<span data-ttu-id="92a94-110">Při použití **předdefinovaných typů citlivých informací** v centrech zabezpečení a dodržování předpisů, zásady ochrany před únikem informací hledají konkrétní vzory a prvky při zjišťování těchto citlivých typů.</span><span class="sxs-lookup"><span data-stu-id="92a94-110">When using the **built-in sensitive information types** in the Security and Compliance centers, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="92a94-111">**Předdefinované typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="92a94-111">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="92a94-112">Informace o předdefinovaných typech Sensitive a o tom, co zásady ochrany před únikem informací hledají při zjišťování typu Sensitive, naleznete v [tématu What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="92a94-112">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="92a94-113">**Vlastní typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="92a94-113">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="92a94-114">Pokud se pokoušíte vytvořit vlastní typy citlivých informací, použijte následující článek, kde naleznete informace o vytvoření vlastního citlivého typu: [Vytvoření vlastního typu citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="92a94-114">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="92a94-115">**Testování zásad ochrany před únikem a ochrany údajů**</span><span class="sxs-lookup"><span data-stu-id="92a94-115">**Test a DLP policy**</span></span>

<span data-ttu-id="92a94-116">Chcete-li data otestovat pomocí předdefinovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Klasifikace** > **Typy citlivých informací**.</span><span class="sxs-lookup"><span data-stu-id="92a94-116">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="92a94-117">Další informace naleznete v [tématu Test vlastní chod citlivých informací typy](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="92a94-117">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="92a94-118">**Sestavy**</span><span class="sxs-lookup"><span data-stu-id="92a94-118">**Reports**</span></span>
  
- <span data-ttu-id="92a94-119">Získejte přehledy citlivých dat pomocí [přehledů ochrany před únikem informací.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="92a94-119">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="92a94-120">Podívejte se na konkrétní podrobnosti události pomocí [zprávy o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="92a94-120">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
