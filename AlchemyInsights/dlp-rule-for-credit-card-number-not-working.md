---
title: Pravidlo ochrany před únikem let do provozu pro číslo kreditní karty nefunguje
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
ms.openlocfilehash: e2e93bed44749b9017dc6ff919a151d46da7a3fc
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507399"
---
# <a name="dlp-issues-with-credit-card-numbers"></a><span data-ttu-id="f6dca-102">Problémy s ochranym před únikem letových průkazů s čísly platebních karet</span><span class="sxs-lookup"><span data-stu-id="f6dca-102">DLP issues with credit card numbers</span></span>

<span data-ttu-id="f6dca-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="f6dca-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="f6dca-104">**Problémy s ochranym před únikem letových průkazů s čísly platebních karet**</span><span class="sxs-lookup"><span data-stu-id="f6dca-104">**DLP issues with credit card numbers**</span></span>

<span data-ttu-id="f6dca-105">Máte problémy s **ochranou před ztrátou dat (DLP)** nefunguje pro obsah obsahující **číslo kreditní karty** při použití DLP citlivé informace typu v O365?</span><span class="sxs-lookup"><span data-stu-id="f6dca-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="f6dca-106">Pokud ano, ujistěte se, že obsah obsahuje potřebné informace pro aktivaci zásad ochrany před únikem informací při jeho vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="f6dca-106">If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated.</span></span> <span data-ttu-id="f6dca-107">Například pro **zásady kreditní karty** nakonfigurované s úrovní spolehlivosti 85 %, následující jsou vyhodnoceny a musí být zjištěny pro pravidlo spustit:</span><span class="sxs-lookup"><span data-stu-id="f6dca-107">For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="f6dca-108">**[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-19)** 16 číslic, které mohou být formátovány nebo neformátované (ddddddddddddddddddddddddd) a musí projít Luhn testem.</span><span class="sxs-lookup"><span data-stu-id="f6dca-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span>

- <span data-ttu-id="f6dca-109">**[Vzor:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-19)** Velmi složitý a robustní vzor, který detekuje karty všech hlavních značek po celém světě, včetně Visa, MasterCard, Discover Card, JCB, American Express, dárkové karty a diner karty.</span><span class="sxs-lookup"><span data-stu-id="f6dca-109">**[Pattern:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span>

- <span data-ttu-id="f6dca-110">**[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-19)** Ano, Luhnův kontrolní součet</span><span class="sxs-lookup"><span data-stu-id="f6dca-110">**[Checksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-19)** Yes, the Luhn checksum</span></span>

- <span data-ttu-id="f6dca-111">**[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-19)** Zásady ochrany před únikem informací si 85 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="f6dca-111">**[Definition:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="f6dca-112">Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="f6dca-112">The function Func_credit_card finds content that matches the pattern.</span></span>

  - <span data-ttu-id="f6dca-113">Jedna z následujících skutečností je pravdivá:</span><span class="sxs-lookup"><span data-stu-id="f6dca-113">One of the following is true:</span></span>

  - <span data-ttu-id="f6dca-114">Bylo nalezeno klíčové slovo z Keyword_cc_verification.</span><span class="sxs-lookup"><span data-stu-id="f6dca-114">A keyword from Keyword_cc_verification is found.</span></span>

  - <span data-ttu-id="f6dca-115">Bylo nalezeno klíčové slovo z Keyword_cc_name</span><span class="sxs-lookup"><span data-stu-id="f6dca-115">A keyword from Keyword_cc_name is found</span></span>

  - <span data-ttu-id="f6dca-116">Funkce Func_expiration_date najde datum ve správném formátu data.</span><span class="sxs-lookup"><span data-stu-id="f6dca-116">The function Func_expiration_date finds a date in the right date format.</span></span>

  - <span data-ttu-id="f6dca-117">Kontrolní součet projde</span><span class="sxs-lookup"><span data-stu-id="f6dca-117">The checksum passes</span></span>

    <span data-ttu-id="f6dca-118">Následující ukázka by například aktivuje zásady čísla kreditní karty DLP:</span><span class="sxs-lookup"><span data-stu-id="f6dca-118">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>

  - <span data-ttu-id="f6dca-119">Vízum: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="f6dca-119">Visa: 4485 3647 3952 7352</span></span>
  
  - <span data-ttu-id="f6dca-120">Vyprší: 2/2009</span><span class="sxs-lookup"><span data-stu-id="f6dca-120">Expires: 2/2009</span></span>

<span data-ttu-id="f6dca-121">Další informace o tom, co je potřeba k zjištění **čísla platební karty** pro váš obsah, naleznete v následující části v tomto článku: Co typy [citlivých informací hledají kreditní kartu #](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="f6dca-121">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#credit-card-number)</span></span>
  
<span data-ttu-id="f6dca-122">Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="f6dca-122">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span></span>
  