---
title: Pravidlo číslo kreditní karty nefunguje DLP
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 30496c79-c8b4-4337-a46d-abed12864209
ms.openlocfilehash: a56f32b54e6cb32fa044d26d08868bac8c368de5
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281211"
---
<span data-ttu-id="bfed4-p101">Došlo k potížím s **Dat ztráta prevence (DLP)** pro obsah obsahující **Číslo kreditní karty** , při použití typu DLP citlivých informací v O365 nefunguje? Pokud ano, přesvědčte se, zda váš obsah obsahuje potřebné informace pro spuštění DLP zásady, pokud je vyhodnocen. Například pro **kreditní karty zásad** nakonfigurován s konfidenční úrovni 85 %, následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit:</span><span class="sxs-lookup"><span data-stu-id="bfed4-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Credit Card Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information to trigger the the DLP policy when it is evaluated. For example, for a **Credit Card policy** configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span> 
  
- <span data-ttu-id="bfed4-105">**[Formát:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 číslic, které mohou být upraveny nebo neformátovaný (dddddddddddddddd) a musejí vyhovět zkoušce Luhn.</span><span class="sxs-lookup"><span data-stu-id="bfed4-105">**[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-19)** 16 digits which can be formatted or unformatted (dddddddddddddddd) and must pass the Luhn test.</span></span> 
    
- <span data-ttu-id="bfed4-106">**[Vzorek:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Velmi komplexní a robustní vzorek, který rozpozná karty ze všech hlavních značek po celém světě, včetně Visa, Mastercard, Objevování karta, JCB, American Express, dárkové poukazy a karty diner.</span><span class="sxs-lookup"><span data-stu-id="bfed4-106">**[Pattern:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-19)** Very complex and robust pattern that detects cards from all major brands worldwide, including Visa, MasterCard, Discover Card, JCB, American Express, gift cards, and diner cards.</span></span> 
    
- <span data-ttu-id="bfed4-107">**[Kontrolní součet:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Ano, Luhn kontrolního součtu</span><span class="sxs-lookup"><span data-stu-id="bfed4-107">**[Checksum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-19)** Yes, the Luhn checksum</span></span> 
    
- <span data-ttu-id="bfed4-108">**[Definice:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** Zásady DLP je 85 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="bfed4-108">**[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-19)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="bfed4-109">Funkce Func_credit_card vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="bfed4-109">The function Func_credit_card finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="bfed4-110">Je splněna jedna z následujících akcí:</span><span class="sxs-lookup"><span data-stu-id="bfed4-110">One of the following is true:</span></span> 
    
  - <span data-ttu-id="bfed4-111">Klíčové slovo z Keyword_cc_verification nebyla nalezena.</span><span class="sxs-lookup"><span data-stu-id="bfed4-111">A keyword from Keyword_cc_verification is found.</span></span>
    
  - <span data-ttu-id="bfed4-112">Klíčové slovo z Keyword_cc_name je nalezen.</span><span class="sxs-lookup"><span data-stu-id="bfed4-112">A keyword from Keyword_cc_name is found</span></span>
    
  - <span data-ttu-id="bfed4-113">Funkce Func_expiration_date najde datum ve formátu data vpravo.</span><span class="sxs-lookup"><span data-stu-id="bfed4-113">The function Func_expiration_date finds a date in the right date format.</span></span>
    
  - <span data-ttu-id="bfed4-114">Předá kontrolní součet</span><span class="sxs-lookup"><span data-stu-id="bfed4-114">The checksum passes</span></span>
    
    <span data-ttu-id="bfed4-115">Například následující ukázka by znamenala pro DLP zásady číslo platební karty:</span><span class="sxs-lookup"><span data-stu-id="bfed4-115">For example, the following sample would trigger for a DLP Credit Card Number Policy:</span></span>
    
  - <span data-ttu-id="bfed4-116">Víza: 4485 3647 3952 7352</span><span class="sxs-lookup"><span data-stu-id="bfed4-116">Visa: 4485 3647 3952 7352</span></span> 
    
  - <span data-ttu-id="bfed4-117">Platnost vyprší: 2/2009</span><span class="sxs-lookup"><span data-stu-id="bfed4-117">Expires: 2/2009</span></span>
    
<span data-ttu-id="bfed4-118">Další informace o co je požadováno pro **Číslo kreditní karty** mají být rozpoznány pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací vyhledejte platební karty #](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span><span class="sxs-lookup"><span data-stu-id="bfed4-118">For more information on what is required for a **Credit Card Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for Credit Card#](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#credit-card-number)</span></span>
  
<span data-ttu-id="bfed4-119">Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="bfed4-119">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  

