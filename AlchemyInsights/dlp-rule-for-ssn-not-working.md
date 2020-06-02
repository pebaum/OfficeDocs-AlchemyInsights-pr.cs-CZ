---
title: Pravidlo ochrany před únikem let do provozu pro ssn nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: 35859bce89ef1ae9b6a9e706fc316b0ee6cd27d1
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507363"
---
# <a name="dlp-issues-with-social-security-numbers"></a><span data-ttu-id="bb853-102">Problémy s DLP s čísly sociálního zabezpečení</span><span class="sxs-lookup"><span data-stu-id="bb853-102">DLP issues with Social Security Numbers</span></span>

<span data-ttu-id="bb853-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="bb853-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="bb853-104">**Problémy s dlp se sítěmi SSN**</span><span class="sxs-lookup"><span data-stu-id="bb853-104">**DLP issues with SSNs**</span></span>

<span data-ttu-id="bb853-105">Máte problémy s **ochranou před ztrátou dat (DLP)** nefunguje pro obsah obsahující **číslo sociálního zabezpečení (SSN)** při použití typu citlivých informací v Microsoft 365?</span><span class="sxs-lookup"><span data-stu-id="bb853-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Microsoft 365?</span></span> <span data-ttu-id="bb853-106">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací hledá.</span><span class="sxs-lookup"><span data-stu-id="bb853-106">If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="bb853-107">Například pro zásady SSN nakonfigurované s úrovní spolehlivosti 85 %, následující jsou vyhodnoceny a musí být zjištěny pro pravidlo aktivovat:</span><span class="sxs-lookup"><span data-stu-id="bb853-107">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="bb853-108">**[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-80)** 9 číslic, které mohou být ve formátu nebo neformátovaný vzor</span><span class="sxs-lookup"><span data-stu-id="bb853-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span>

- <span data-ttu-id="bb853-109">**[Vzor:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Čtyři funkce hledají SSNs ve čtyřech různých vzorech:</span><span class="sxs-lookup"><span data-stu-id="bb853-109">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span>

  - <span data-ttu-id="bb853-110">Func_ssn najde SSNs se silným formátováním před 2011, které jsou formátovány pomlčkami nebo mezerami (ddd-ddddd NEBO ddd ddd dddddd)</span><span class="sxs-lookup"><span data-stu-id="bb853-110">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="bb853-111">Func_unformatted_ssn najde SSNs s před-2011 silné formátování, které jsou neformátované jako devět po sobě jdoucích číslic (dddddddddddddd)</span><span class="sxs-lookup"><span data-stu-id="bb853-111">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>

  - <span data-ttu-id="bb853-112">Func_randomized_formatted_ssn vyhledá po roce 2011 sítě SSN formátované pomlčkami nebo mezerami (ddd-dddd NEBO ddd ddd ddd dddddd)</span><span class="sxs-lookup"><span data-stu-id="bb853-112">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="bb853-113">Func_randomized_unformatted_ssn vyhledá po roce 2011 názvy SSN, které nejsou formátovány jako devět po sobě jdoucích číslic (ddddddddddddd).</span><span class="sxs-lookup"><span data-stu-id="bb853-113">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>

- <span data-ttu-id="bb853-114">**[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-79)** Ne, žádný kontrolní součet neexistuje.</span><span class="sxs-lookup"><span data-stu-id="bb853-114">**[Checksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-79)** No, there is no Checksum</span></span>

- <span data-ttu-id="bb853-115">**[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-80)** Zásady ochrany před únikem informací si 85 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="bb853-115">**[Definition:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="bb853-116">[Funkce Func_ssn](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-80) vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="bb853-116">The [function Func_ssn](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-80) finds content that matches the pattern.</span></span>

  - <span data-ttu-id="bb853-117">Bylo nalezeno klíčové slovo z [Keyword_ssn.](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#keyword_ssn)</span><span class="sxs-lookup"><span data-stu-id="bb853-117">A keyword from [Keyword_ssn](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#keyword_ssn) is found.</span></span> <span data-ttu-id="bb853-118">Příklady klíčových slov zahrnují: *Sociální zabezpečení, Sociální zabezpečení#, Soc Sec , SSN* .</span><span class="sxs-lookup"><span data-stu-id="bb853-118">Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  .</span></span> <span data-ttu-id="bb853-119">Například následující ukázka by aktivovat pro zásady DLP SSN: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="bb853-119">For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
  
<span data-ttu-id="bb853-120">Další informace o tom, co je potřeba pro detekci sítí SSN pro váš obsah, naleznete v následující části v tomto článku: [Co typy citlivých informací hledat SSN](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="bb853-120">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="bb853-121">Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="bb853-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span></span>
  