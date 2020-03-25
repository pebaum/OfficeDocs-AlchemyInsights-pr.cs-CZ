---
title: Pravidlo DLP pro číslo kreditní karty nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1270"
- "3200001"
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: 6b28534d072c024a98a9b05f6cb55bfdc3435db6
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932436"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="37ef7-102">Problémy s DLP s čísly kreditních karet</span><span class="sxs-lookup"><span data-stu-id="37ef7-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="37ef7-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="37ef7-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="37ef7-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="37ef7-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="37ef7-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="37ef7-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="37ef7-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="37ef7-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="37ef7-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="37ef7-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="37ef7-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="37ef7-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="37ef7-109">**Problémy s DLP s čísly kreditních karet**</span><span class="sxs-lookup"><span data-stu-id="37ef7-109">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="37ef7-110">Máte problémy s **prevencí před ztrátou dat (DLP),** která nefunguje pro obsah obsahující **číslo kreditní karty** při použití typu citlivých informací DLP v O365?</span><span class="sxs-lookup"><span data-stu-id="37ef7-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="37ef7-111">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro aktivaci zásady ochrany před únikem informací při vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="37ef7-111">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="37ef7-112">Například pro **zásady platební karty** nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo:</span><span class="sxs-lookup"><span data-stu-id="37ef7-112">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="37ef7-113">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 číslic, které mohou být formátovány nebo neformátované (ddddddddddddddddddd) a musí projít Luhntestem.</span><span class="sxs-lookup"><span data-stu-id="37ef7-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="37ef7-114">**[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Velmi složitý a robustní vzor, který detekuje karty od všech hlavních značek po celém světě, včetně Visa, MasterCard, Discover Card, JCB, American Express, dárkové karty a karty.</span><span class="sxs-lookup"><span data-stu-id="37ef7-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="37ef7-115">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Ano, kontrolní součet Luhn</span><span class="sxs-lookup"><span data-stu-id="37ef7-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="37ef7-116">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zásady ochrany před únikem informací jsou z 85 % přesvědčeny, že tento typ citlivých informací zjistil, pokud v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="37ef7-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="37ef7-117">Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="37ef7-117">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="37ef7-118">Platí jedna z následujících skutečností:</span><span class="sxs-lookup"><span data-stu-id="37ef7-118">One of the following is true:</span></span>

  - <span data-ttu-id="37ef7-119">Bylo nalezeno klíčové slovo z Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="37ef7-119">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="37ef7-120">Bylo nalezeno klíčové slovo z Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="37ef7-120">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="37ef7-121">Funkce Func_expiration_date vyhledá datum ve správném formátu data.</span><span class="sxs-lookup"><span data-stu-id="37ef7-121">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="37ef7-122">Kontrolní součet prochází</span><span class="sxs-lookup"><span data-stu-id="37ef7-122">The checksum passes</span></span>

    <span data-ttu-id="37ef7-123">Například následující ukázka by aktivační událost pro zásady číslo platební karty DLP:</span><span class="sxs-lookup"><span data-stu-id="37ef7-123">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="37ef7-124">Vízum: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="37ef7-124">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="37ef7-125">Platnost: 2/2009</span><span class="sxs-lookup"><span data-stu-id="37ef7-125">Expires: 2/2009</span></span>

<span data-ttu-id="37ef7-126">Další informace o tom, co je požadováno pro **zjištění čísla platební karty** pro váš obsah, naleznete v následující části tohoto článku: Co typy citlivých informací hledají číslo platební [karty#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="37ef7-126">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="37ef7-127">Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="37ef7-127">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  