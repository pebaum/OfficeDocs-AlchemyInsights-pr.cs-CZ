---
title: Pravidlo ochrany před únikem let do provozu pro číslo bankovního účtu v USA nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1287"
- "3200001"
ms.assetid: 80b40145-8376-4c3a-8d22-6efb9f9cb271
ms.openlocfilehash: b032a7c80e8b387114aeda95c4f6af7e57225517
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507327"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="97867-102">Problémy s dlp s čísly bankovních účtů v USA</span><span class="sxs-lookup"><span data-stu-id="97867-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="97867-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="97867-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="97867-104">**Problémy s dlp s čísly bankovních účtů v USA**</span><span class="sxs-lookup"><span data-stu-id="97867-104">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="97867-105">Máte problémy s **ochranou před únikem informací (DLP)** nefunguje pro obsah obsahující **číslo bankovního účtu v USA** při použití DLP citlivé informace typu v O365?</span><span class="sxs-lookup"><span data-stu-id="97867-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="97867-106">Pokud ano, ujistěte se, že obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací při jeho vyhodnocení hledají.</span><span class="sxs-lookup"><span data-stu-id="97867-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="97867-107">Například pro zásady **číslo bankovního účtu v USA** nakonfigurované s úrovní spolehlivosti 85 %, následující jsou vyhodnoceny a musí být zjištěny pro pravidlo spustit:</span><span class="sxs-lookup"><span data-stu-id="97867-107">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="97867-108">**[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 číslic</span><span class="sxs-lookup"><span data-stu-id="97867-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="97867-109">**[Vzor:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 po sobě jdoucích číslic.</span><span class="sxs-lookup"><span data-stu-id="97867-109">**[Pattern:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="97867-110">**[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ne, žádný kontrolní součet neexistuje.</span><span class="sxs-lookup"><span data-stu-id="97867-110">**[Checksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="97867-111">**[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** Zásady ochrany před únikem informací si 75 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="97867-111">**[Definition:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="97867-112">Regulární výraz Regex_usa_bank_account_number vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="97867-112">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="97867-113">Bylo nalezeno klíčové slovo z Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="97867-113">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="97867-114">Pro zásadu **Číslo bankovního účtu v USA** by se například aktivovala následující ukázka: Běžný účet 78344011</span><span class="sxs-lookup"><span data-stu-id="97867-114">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="97867-115">Další informace o tom, co je potřeba k zjištění **čísla bankovního účtu v USA** pro váš obsah, naleznete v následující části v tomto článku: Co typy [citlivých informací hledají číslo bankovního účtu v USA](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="97867-115">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us-bank-account-number)</span></span>
  
<span data-ttu-id="97867-116">Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="97867-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span></span>
  