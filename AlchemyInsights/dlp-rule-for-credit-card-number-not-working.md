---
title: Pravidlo DLP pro číslo kreditní karty nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 80ff41b3e746f95278ccbf0df19eebb61f7f9ee0
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704194"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="1834f-102">Problémy s DLP s čísly kreditních karet</span><span class="sxs-lookup"><span data-stu-id="1834f-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="1834f-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="1834f-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="1834f-104">**Problémy s DLP s čísly kreditních karet**</span><span class="sxs-lookup"><span data-stu-id="1834f-104">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="1834f-105">Máte problémy s **prevencí před ztrátou dat (DLP),** která nefunguje pro obsah obsahující **číslo kreditní karty** při použití typu citlivých informací DLP v O365?</span><span class="sxs-lookup"><span data-stu-id="1834f-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="1834f-106">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro aktivaci zásady ochrany před únikem informací při vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="1834f-106">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="1834f-107">Například pro **zásady platební karty** nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo:</span><span class="sxs-lookup"><span data-stu-id="1834f-107">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="1834f-108">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 číslic, které mohou být formátovány nebo neformátované (ddddddddddddddddddd) a musí projít Luhntestem.</span><span class="sxs-lookup"><span data-stu-id="1834f-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="1834f-109">**[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Velmi složitý a robustní vzor, který detekuje karty od všech hlavních značek po celém světě, včetně Visa, MasterCard, Discover Card, JCB, American Express, dárkové karty a karty.</span><span class="sxs-lookup"><span data-stu-id="1834f-109">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="1834f-110">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Ano, kontrolní součet Luhn</span><span class="sxs-lookup"><span data-stu-id="1834f-110">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="1834f-111">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zásady ochrany před únikem informací jsou z 85 % přesvědčeny, že tento typ citlivých informací zjistil, pokud v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="1834f-111">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="1834f-112">Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="1834f-112">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="1834f-113">Platí jedna z následujících skutečností:</span><span class="sxs-lookup"><span data-stu-id="1834f-113">One of the following is true:</span></span>

  - <span data-ttu-id="1834f-114">Bylo nalezeno klíčové slovo z Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="1834f-114">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="1834f-115">Bylo nalezeno klíčové slovo z Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="1834f-115">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="1834f-116">Funkce Func_expiration_date vyhledá datum ve správném formátu data.</span><span class="sxs-lookup"><span data-stu-id="1834f-116">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="1834f-117">Kontrolní součet prochází</span><span class="sxs-lookup"><span data-stu-id="1834f-117">The checksum passes</span></span>

    <span data-ttu-id="1834f-118">Například následující ukázka by aktivační událost pro zásady číslo platební karty DLP:</span><span class="sxs-lookup"><span data-stu-id="1834f-118">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="1834f-119">Vízum: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="1834f-119">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="1834f-120">Platnost: 2/2009</span><span class="sxs-lookup"><span data-stu-id="1834f-120">Expires: 2/2009</span></span>

<span data-ttu-id="1834f-121">Další informace o tom, co je požadováno pro **zjištění čísla platební karty** pro váš obsah, naleznete v následující části tohoto článku: Co typy citlivých informací hledají číslo platební [karty#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="1834f-121">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="1834f-122">Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="1834f-122">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  