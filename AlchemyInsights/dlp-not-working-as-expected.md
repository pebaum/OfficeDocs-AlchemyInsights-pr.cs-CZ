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
ms.openlocfilehash: 574a8a43d8264e98c6af2bfeb1bb472475e6e334
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977431"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="4c5f7-102">DLP nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="4c5f7-102">DLP not working as expected</span></span>

<span data-ttu-id="4c5f7-103">**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)</span><span class="sxs-lookup"><span data-stu-id="4c5f7-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

 <span data-ttu-id="4c5f7-104">**Nastavení ochrany před únikem a ochrany před únikem**</span><span class="sxs-lookup"><span data-stu-id="4c5f7-104">**Setting up DLP**</span></span>

<span data-ttu-id="4c5f7-105">Máte problémy s **prevencí před ztrátou dat (DLP)** v Office 365 nefunguje podle očekávání?</span><span class="sxs-lookup"><span data-stu-id="4c5f7-105">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="4c5f7-106">Pokud ano, ujistěte se, že **vaše zásady ochrany před únikem informací** jsou správně nastaveny a že data obsahují to, co **zásady ochrany před únikem informací** hledají při vyhodnocování.</span><span class="sxs-lookup"><span data-stu-id="4c5f7-106">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="4c5f7-107">Zásady ochrany před únikem informací umožňují identifikovat a chránit citlivé informace ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="4c5f7-107">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="4c5f7-108">Chcete-li nastavit zásady ochrany před únikem informací, použijte informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="4c5f7-108">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="4c5f7-109">**Co zásady ochrany před únikem a ochrany údajů**</span><span class="sxs-lookup"><span data-stu-id="4c5f7-109">**What DLP policies look for**</span></span>
  
<span data-ttu-id="4c5f7-110">Při použití **předdefinovaných typů citlivých informací** v Centru zabezpečení a dodržování předpisů Office 365 hledají zásady ochrany před únikem informací konkrétní vzory a prvky při zjišťování těchto citlivých typů.</span><span class="sxs-lookup"><span data-stu-id="4c5f7-110">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="4c5f7-111">**Předdefinované typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="4c5f7-111">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="4c5f7-112">Informace o předdefinovaných typech Sensitive a o tom, co zásady ochrany před únikem informací hledají při zjišťování typu Sensitive, naleznete v [tématu What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="4c5f7-112">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="4c5f7-113">**Vlastní typy citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="4c5f7-113">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="4c5f7-114">Pokud se pokoušíte vytvořit vlastní typy citlivých informací, použijte následující článek, kde naleznete informace o vytvoření vlastního citlivého typu: [Vytvoření vlastního typu citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="4c5f7-114">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="4c5f7-115">**Testování zásad ochrany před únikem a ochrany údajů**</span><span class="sxs-lookup"><span data-stu-id="4c5f7-115">**Test a DLP policy**</span></span>

<span data-ttu-id="4c5f7-116">Chcete-li data otestovat pomocí předdefinovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Klasifikace** > **Typy citlivých informací**.</span><span class="sxs-lookup"><span data-stu-id="4c5f7-116">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="4c5f7-117">Další informace naleznete v [tématu Test vlastní chod citlivých informací typy](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="4c5f7-117">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="4c5f7-118">**Sestavy**</span><span class="sxs-lookup"><span data-stu-id="4c5f7-118">**Reports**</span></span>
  
- <span data-ttu-id="4c5f7-119">Získejte přehledy citlivých dat pomocí [přehledů ochrany před únikem informací.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="4c5f7-119">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="4c5f7-120">Podívejte se na konkrétní podrobnosti události pomocí [zprávy o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="4c5f7-120">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
