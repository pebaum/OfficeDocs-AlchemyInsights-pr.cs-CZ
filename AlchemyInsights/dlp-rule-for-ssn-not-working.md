---
title: Pravidlo dlp pro nefunguje SSN
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
ms.openlocfilehash: cfe884a207490a19325ce059652de158c16dc801
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704078"
---
# <a name="dlp-issues-with-social-security-numbers"></a><span data-ttu-id="b0c26-102">DLP problémy s čísly sociálního zabezpečení</span><span class="sxs-lookup"><span data-stu-id="b0c26-102">DLP issues with Social Security Numbers</span></span>

<span data-ttu-id="b0c26-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="b0c26-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="b0c26-104">**Problémy s dip s ssns**</span><span class="sxs-lookup"><span data-stu-id="b0c26-104">**DLP issues with SSNs**</span></span>

<span data-ttu-id="b0c26-105">Máte problémy s **funkcí Zabránění ztrátám dat (DLP),** která nefunguje pro obsah obsahující **číslo sociálního zabezpečení (SSN)** při použití typu citlivých informací v Office 365?</span><span class="sxs-lookup"><span data-stu-id="b0c26-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Office 365?</span></span> <span data-ttu-id="b0c26-106">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co hledá zásady ochrany před únikem informací.</span><span class="sxs-lookup"><span data-stu-id="b0c26-106">If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="b0c26-107">Například pro zásady SSN nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být rozpoznány, aby se pravidlo aktivovala:</span><span class="sxs-lookup"><span data-stu-id="b0c26-107">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="b0c26-108">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 číslic, které mohou být ve formátu nebo neformátovaném vzoru</span><span class="sxs-lookup"><span data-stu-id="b0c26-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span>

- <span data-ttu-id="b0c26-109">**[Vzor:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Čtyři funkce hledají ssn ve čtyřech různých vzorech:</span><span class="sxs-lookup"><span data-stu-id="b0c26-109">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span>

  - <span data-ttu-id="b0c26-110">Func_ssn najde SSN s před2011 silné formátování, které jsou formátovány s pomlčkami nebo mezery (ddd-ddddnebo ddd ddd dddd)</span><span class="sxs-lookup"><span data-stu-id="b0c26-110">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="b0c26-111">Func_unformatted_ssn najde ssn s před2011 silné formátování, které jsou neformátované jako devět po sobě jdoucích číslic (ddddddddd).</span><span class="sxs-lookup"><span data-stu-id="b0c26-111">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>

  - <span data-ttu-id="b0c26-112">Func_randomized_formatted_ssn najde ssn po roce 2011, které jsou formátovány pomlčkami nebo mezerami (ddd-dddd NEBO ddd dddd)</span><span class="sxs-lookup"><span data-stu-id="b0c26-112">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="b0c26-113">Func_randomized_unformatted_ssn vyhledá ssn po roce 2011, které nejsou formátovány jako devět po sobě jdoucích číslic (dddddddddd).</span><span class="sxs-lookup"><span data-stu-id="b0c26-113">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>

- <span data-ttu-id="b0c26-114">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Ne, není žádný kontrolní součet.</span><span class="sxs-lookup"><span data-stu-id="b0c26-114">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, there is no Checksum</span></span>

- <span data-ttu-id="b0c26-115">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Zásady ochrany před únikem informací jsou z 85 % přesvědčeny, že tento typ citlivých informací zjistil, pokud v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="b0c26-115">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="b0c26-116">[Funkce Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="b0c26-116">The [function Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) finds content that matches the pattern.</span></span>

  - <span data-ttu-id="b0c26-117">Bylo nalezeno klíčové slovo z [Keyword_ssn.](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn)</span><span class="sxs-lookup"><span data-stu-id="b0c26-117">A keyword from [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) is found.</span></span> <span data-ttu-id="b0c26-118">Příklady klíčových slov zahrnují: *Sociální zabezpečení, Sociální zabezpečení #, Soc Sec, SSN* .</span><span class="sxs-lookup"><span data-stu-id="b0c26-118">Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  .</span></span> <span data-ttu-id="b0c26-119">Například následující ukázka by aktivační událost pro zásady DLP SSN: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="b0c26-119">For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
  
<span data-ttu-id="b0c26-120">Další informace o tom, co je nutné pro ssn, které mají být detekovány pro váš obsah, naleznete v následující části tohoto článku: [Co typy citlivých informací hledat SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="b0c26-120">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="b0c26-121">Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="b0c26-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  