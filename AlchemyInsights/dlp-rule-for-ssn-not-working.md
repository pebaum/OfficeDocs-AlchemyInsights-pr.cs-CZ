---
title: DLP pravidlo pro SSN nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1242"
- "3200001"
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: fffd355279b064b31c0a8bf60518b15ee1ed1848
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35389426"
---
# <a name="dlp-issues-with-social-security-numbers"></a><span data-ttu-id="9b759-102">DLP problémy s rodná čísla</span><span class="sxs-lookup"><span data-stu-id="9b759-102">DLP issues with Social Security Numbers</span></span>

<span data-ttu-id="9b759-103">Došlo k potížím s **Dat ztráta prevence (DLP)** nefunguje pro obsah obsahující **Číslo sociálního pojištění (ČSP)** při použití citlivých informací typu ve službách Office 365?</span><span class="sxs-lookup"><span data-stu-id="9b759-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Office 365?</span></span> <span data-ttu-id="9b759-104">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro vyhledávání zásady DLP.</span><span class="sxs-lookup"><span data-stu-id="9b759-104">If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="9b759-105">Například SSN zásad nakonfigurován s konfidenční úrovni 85 % takto vyhodnoceny a musí být rozpoznány pro pravidlo spustit:</span><span class="sxs-lookup"><span data-stu-id="9b759-105">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="9b759-106">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 číslic, které mohou být ve vzorku formátovaný nebo neformátovaný</span><span class="sxs-lookup"><span data-stu-id="9b759-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span>

- <span data-ttu-id="9b759-107">**[Vzorek:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Ve čtyři různé vzory hledat SSNs čtyři funkce:</span><span class="sxs-lookup"><span data-stu-id="9b759-107">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span>

  - <span data-ttu-id="9b759-108">Func_ssn najde SSNs s pre-2011 silný formátování, které jsou formátovány s čárkami nebo mezerami (ddd-dd dddd nebo ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="9b759-108">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="9b759-109">Func_unformatted_ssn najde SSNs s pre-2011 silný formátování neformátovaný jako devět po sobě jdoucích číslic (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="9b759-109">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>

  - <span data-ttu-id="9b759-110">Func_randomized_formatted_ssn najde SSNs post 2011, které jsou formátovány s čárkami nebo mezerami (ddd-dd dddd nebo ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="9b759-110">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>

  - <span data-ttu-id="9b759-111">Func_randomized_unformatted_ssn najde SSNs post 2011, které neformátovaný jako devět po sobě jdoucích číslic (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="9b759-111">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>

- <span data-ttu-id="9b759-112">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Ne, neexistuje žádný kontrolní součet</span><span class="sxs-lookup"><span data-stu-id="9b759-112">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, there is no Checksum</span></span>

- <span data-ttu-id="9b759-113">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Zásady DLP je 85 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="9b759-113">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="9b759-114">[Funkce Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="9b759-114">The [function Func_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) finds content that matches the pattern.</span></span>

  - <span data-ttu-id="9b759-115">Klíčové slovo z [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) nebyla nalezena.</span><span class="sxs-lookup"><span data-stu-id="9b759-115">A keyword from [Keyword_ssn](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) is found.</span></span> <span data-ttu-id="9b759-116">Obsahuje příklady klíčových slov: *sociální zabezpečení, sociální zabezpečení #, s Soc, SSN* .</span><span class="sxs-lookup"><span data-stu-id="9b759-116">Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  .</span></span> <span data-ttu-id="9b759-117">Například následující ukázka vyvolalo DLP SSN zásady: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="9b759-117">For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
  
<span data-ttu-id="9b759-118">Další informace o co je požadováno pro SSNs zjistit pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací hledejte SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="9b759-118">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="9b759-119">Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="9b759-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  