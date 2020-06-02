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
ms.openlocfilehash: e96904e2f0da2fe1fafb3f8722465eaf22681b71
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507471"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="4c89f-102">DLP nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="4c89f-102">DLP not working as expected</span></span>

<span data-ttu-id="4c89f-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="4c89f-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

 <span data-ttu-id="4c89f-104">**Nastavení DLP**</span><span class="sxs-lookup"><span data-stu-id="4c89f-104">**Setting up DLP**</span></span>

<span data-ttu-id="4c89f-105">Máte problémy s **ochranou před únikem dat (DLP)** v Office 365 nefunguje podle očekávání?</span><span class="sxs-lookup"><span data-stu-id="4c89f-105">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="4c89f-106">Pokud ano, ujistěte se, že **vaše zásady ochrany před únikem informací** je správně nastavena a že vaše data obsahují, co **zásady ochrany před únikem informací** hledá při jejich vyhodnocování.</span><span class="sxs-lookup"><span data-stu-id="4c89f-106">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="4c89f-107">Zásady ochrany před únikem informací umožňují identifikovat a chránit citlivé informace ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="4c89f-107">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="4c89f-108">Chcete-li nastavit zásady ochrany před únikem informací, použijte informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="4c89f-108">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="4c89f-109">**Co zásady ochrany před únikem let hledají**</span><span class="sxs-lookup"><span data-stu-id="4c89f-109">**What DLP policies look for**</span></span>
  
<span data-ttu-id="4c89f-110">Při použití **předdefinované typy citlivých informací** v centrech zabezpečení a dodržování předpisů zásady ochrany před únikem informací hledají při zjišťování těchto citlivých typů konkrétní vzory a prvky.</span><span class="sxs-lookup"><span data-stu-id="4c89f-110">When using the **built-in sensitive information types** in the Security and Compliance centers, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="4c89f-111">**Vestavěné typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="4c89f-111">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="4c89f-112">Informace o předdefinované typy a co hledá zásady ochrany před únikem informací při zjišťování citlivého typu, naleznete v [tématu: Co vyhledáte typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span><span class="sxs-lookup"><span data-stu-id="4c89f-112">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span></span>

- <span data-ttu-id="4c89f-113">**Vlastní typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="4c89f-113">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="4c89f-114">Pokud se pokoušíte vytvořit vlastní typy citlivých informací, použijte následující článek pro informace o tom, jak vytvořit vlastní citlivý typ: [Vytvoření vlastního typu citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="4c89f-114">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="4c89f-115">**Testování zásad ochrany před únikem let dlp**</span><span class="sxs-lookup"><span data-stu-id="4c89f-115">**Test a DLP policy**</span></span>

<span data-ttu-id="4c89f-116">Chcete-li data otestovat pomocí integrovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Typy**  >  **citlivých informací**klasifikace .</span><span class="sxs-lookup"><span data-stu-id="4c89f-116">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="4c89f-117">Další informace naleznete v [tématu Testování vlastních typů citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="4c89f-117">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="4c89f-118">**Sestavy**</span><span class="sxs-lookup"><span data-stu-id="4c89f-118">**Reports**</span></span>
  
- <span data-ttu-id="4c89f-119">Získejte citlivé poznatky o datech pomocí [sestav ochrany před únikem informací.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="4c89f-119">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="4c89f-120">Podívejte se na konkrétní podrobnosti o události pomocí [hlášení incidentů](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="4c89f-120">See specific details of the event with an [Incident Report](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports).</span></span>
