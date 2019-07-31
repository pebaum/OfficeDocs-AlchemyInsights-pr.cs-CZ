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
ms.openlocfilehash: 1ea457bd69e7d545cf761a0be849695738b19d8b
ms.sourcegitcommit: d6ea6f4456a582559f27b34c0b9455a86a8e61f1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/31/2019
ms.locfileid: "35941061"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="1b4e9-102">DLP nefunguje podle očekávání</span><span class="sxs-lookup"><span data-stu-id="1b4e9-102">DLP not working as expected</span></span>

<span data-ttu-id="1b4e9-103">Došlo k potížím s **Daty ztráty prevence (DLP)** ve službách Office 365 nepracuje podle očekávání?</span><span class="sxs-lookup"><span data-stu-id="1b4e9-103">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="1b4e9-104">Pokud ano, ujistěte se, že vaše **zásady DLP** je správně nastaven a že data obsahují jaké **zásady DLP** hledá po jeho vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="1b4e9-104">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
 <span data-ttu-id="1b4e9-105">**Nastavení technologie DLP**</span><span class="sxs-lookup"><span data-stu-id="1b4e9-105">**Setting up DLP**</span></span>
  
<span data-ttu-id="1b4e9-106">DLP zásady umožňuje identifikovat a chránit citlivé informace ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="1b4e9-106">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="1b4e9-107">Chcete-li nastavit zásady DLP, informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="1b4e9-107">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="1b4e9-108">**Vyhledejte zásady DLP**</span><span class="sxs-lookup"><span data-stu-id="1b4e9-108">**What DLP policies look for**</span></span>
  
<span data-ttu-id="1b4e9-109">Při použití **typů předdefinovaných citlivé informace** v Centru zabezpečení Office 365 a soulad, DLP zásady vyhledejte konkrétní vzory a prvky při zjištění těchto citlivých typů.</span><span class="sxs-lookup"><span data-stu-id="1b4e9-109">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="1b4e9-110">**Typy vestavěných citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="1b4e9-110">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="1b4e9-111">Informace o předdefinované typy citlivé a co DLP zásady hledá při zjištění citlivý typ, viz: [typy citlivé informace hledat](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="1b4e9-111">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="1b4e9-112">**Typy vlastních důvěrných informací**</span><span class="sxs-lookup"><span data-stu-id="1b4e9-112">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="1b4e9-113">Pokud se pokoušíte vytvořit typy vlastní důvěrné informace, použijte v následujícím článku informace o tom, jak vytvořit vlastní typ citlivé: [vytvořit typ vlastní důvěrné informace](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="1b4e9-113">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="1b4e9-114">**Testování zásad DLP**</span><span class="sxs-lookup"><span data-stu-id="1b4e9-114">**Test a DLP policy**</span></span>

<span data-ttu-id="1b4e9-115">Chcete-li testovat data typu vestavěné nebo vlastní důvěrné informace, použijte možnost **Typ testu** podle **klasifikace** > **typy citlivých informací**.</span><span class="sxs-lookup"><span data-stu-id="1b4e9-115">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="1b4e9-116">Další informace naleznete v tématu [typy testu vlastní důvěrné informace](https://docs.microsoft.com/en-us/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="1b4e9-116">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/en-us/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="1b4e9-117">**Sestavy**</span><span class="sxs-lookup"><span data-stu-id="1b4e9-117">**Reports**</span></span>
  
- <span data-ttu-id="1b4e9-118">Získat poznatky o citlivá data s [zprávy DLP.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="1b4e9-118">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="1b4e9-119">Zobrazit konkrétní podrobnosti o [Incidentu sestavy](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports)události.</span><span class="sxs-lookup"><span data-stu-id="1b4e9-119">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
