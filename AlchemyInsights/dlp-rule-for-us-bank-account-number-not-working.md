---
title: Pravidlo DLP pro číslo bankovního účtu v USA nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: bb7d8ca91af73fa4ebed5992ec848128beb18830
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977155"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="b8a0a-102">DLP problémy s čísly bankovních účtů v USA</span><span class="sxs-lookup"><span data-stu-id="b8a0a-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="b8a0a-103">**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)</span><span class="sxs-lookup"><span data-stu-id="b8a0a-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="b8a0a-104">**DLP problémy s čísly bankovních účtů v USA**</span><span class="sxs-lookup"><span data-stu-id="b8a0a-104">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="b8a0a-105">Máte problémy s **prevencí před únikem dat (DLP),** která nefunguje pro obsah obsahující **číslo bankovního účtu v USA** při použití typu citlivých informací dlp v O365?</span><span class="sxs-lookup"><span data-stu-id="b8a0a-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="b8a0a-106">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací hledá při vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="b8a0a-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="b8a0a-107">Například pro zásady **číslo bankovního účtu v USA** nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo:</span><span class="sxs-lookup"><span data-stu-id="b8a0a-107">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="b8a0a-108">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 číslic</span><span class="sxs-lookup"><span data-stu-id="b8a0a-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="b8a0a-109">**[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 po sobě jdoucích číslic.</span><span class="sxs-lookup"><span data-stu-id="b8a0a-109">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="b8a0a-110">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, není žádný kontrolní součet.</span><span class="sxs-lookup"><span data-stu-id="b8a0a-110">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="b8a0a-111">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Zásady ochrany před únikem informací si je 75 % jisti, že byl zjištěn tento typ citlivých informací, pokud v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="b8a0a-111">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="b8a0a-112">Regulární výraz Regex_usa_bank_account_number vyhledá obsah, který odpovídá vzoru</span><span class="sxs-lookup"><span data-stu-id="b8a0a-112">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="b8a0a-113">Bylo nalezeno klíčové slovo z Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="b8a0a-113">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="b8a0a-114">Například následující ukázka by aktivační událost pro zásady **číslo bankovního účtu v USA:** Běžný účet 78344011</span><span class="sxs-lookup"><span data-stu-id="b8a0a-114">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="b8a0a-115">Další informace o tom, co je požadováno pro zjištění **čísla bankovního účtu v USA,** naleznete v následující části tohoto článku: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="b8a0a-115">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="b8a0a-116">Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="b8a0a-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  