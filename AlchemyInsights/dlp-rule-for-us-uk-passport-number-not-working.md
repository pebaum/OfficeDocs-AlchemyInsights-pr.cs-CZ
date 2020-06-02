---
title: Pravidlo ochrany před únikem letového provozu pro číslo pasu USA/Uk nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 3d3b7dc2d9510376bc9eef6ec69b87ad7c681b05
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507291"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="ca066-102">Problémy s DLP - USA / UK čísla pasu</span><span class="sxs-lookup"><span data-stu-id="ca066-102">Problems with DLP - US/UK passport numbers</span></span>

<span data-ttu-id="ca066-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="ca066-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="ca066-104">**DLP problémy s USA / UK čísla pasu**</span><span class="sxs-lookup"><span data-stu-id="ca066-104">**DLP issues with US/UK passport numbers**</span></span>

<span data-ttu-id="ca066-105">Máte problémy s **ochranou před ztrátou dat (DLP)** nefunguje pro obsah obsahující **usa / UK číslo pasu** při použití DLP citlivé informace typu v O365?</span><span class="sxs-lookup"><span data-stu-id="ca066-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK passport number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="ca066-106">Pokud ano, ujistěte se, že obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací při jeho vyhodnocení hledají.</span><span class="sxs-lookup"><span data-stu-id="ca066-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="ca066-107">Například pro zásady **čísla pasu USA/Spojeného království,** které jsou nakonfigurovány s úrovní spolehlivosti 75 %, jsou vyhodnoceny následující zásady, které musí být detekovány, aby pravidlo spustilo</span><span class="sxs-lookup"><span data-stu-id="ca066-107">For example, for a **US/UK passport number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span>
  
- <span data-ttu-id="ca066-108">**[Formát:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** Devět číslic</span><span class="sxs-lookup"><span data-stu-id="ca066-108">**[Format:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#format-77)** Nine digits</span></span>

- <span data-ttu-id="ca066-109">**[Vzor:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** Devět po sobě jdoucích číslic</span><span class="sxs-lookup"><span data-stu-id="ca066-109">**[Pattern:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#pattern-77)** Nine consecutive digits</span></span>

- <span data-ttu-id="ca066-110">**[Kontrolní součet:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** Ne, žádný kontrolní součet neexistuje.</span><span class="sxs-lookup"><span data-stu-id="ca066-110">**[Checksum:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="ca066-111">**[Definice:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-77)** Zásady ochrany před únikem informací si 75 % jsou jisti, že tento typ citlivých informací zjistil, pokud se v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="ca066-111">**[Definition:](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="ca066-112">Funkce Func_usa_uk_passport vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="ca066-112">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>

  - <span data-ttu-id="ca066-113">Bylo nalezeno klíčové slovo z Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="ca066-113">A keyword from Keyword_passport is found.</span></span>

    <span data-ttu-id="ca066-114">Například následující vzorek by se aktivuje pro **usa / Uk pas číslo** politiky: US Passport číslo 123456789</span><span class="sxs-lookup"><span data-stu-id="ca066-114">For example, the following sample would trigger for the **US/UK passport number** policy: U.S. Passport number 123456789</span></span>

<span data-ttu-id="ca066-115">Další informace o tom, co je potřeba k zjištění pasového čísla USA/Velké Británie pro váš obsah, naleznete v následující části v tomto článku: [Co vyhledáte u pasového čísla USA/Velké Británie](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="ca066-115">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions#us--uk-passport-number)</span></span>
  
<span data-ttu-id="ca066-116">Použití jiného předdefinovaného typu citlivých informací naleznete v následujícím článku informace o tom, co je požadováno pro jiné typy: [Co vyhledávají typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span><span class="sxs-lookup"><span data-stu-id="ca066-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions)</span></span>
  