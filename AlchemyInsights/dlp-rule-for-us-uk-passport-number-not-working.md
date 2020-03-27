---
title: Pravidlo DLP pro číslo pasu USA/UK nefunguje
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1319"
- "3200001"
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 534e258c31a9a71c618765511487487c53f455b5
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977099"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="74d5e-102">Problémy s DLP - ČÍSLA pasů v USA/Velké Británii</span><span class="sxs-lookup"><span data-stu-id="74d5e-102">Problems with DLP - US/UK passport numbers</span></span>

<span data-ttu-id="74d5e-103">**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)</span><span class="sxs-lookup"><span data-stu-id="74d5e-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="74d5e-104">**Problémy s dlp s čísly pasů usa / UK**</span><span class="sxs-lookup"><span data-stu-id="74d5e-104">**DLP issues with US/UK passport numbers**</span></span>

<span data-ttu-id="74d5e-105">Máte problémy s **prevencí před únikem dat (DLP),** která nefunguje pro obsah obsahující **číslo pasu USA/UK** při použití typu citlivých informací dlp v O365?</span><span class="sxs-lookup"><span data-stu-id="74d5e-105">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK passport number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="74d5e-106">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací hledá při vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="74d5e-106">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="74d5e-107">Například pro zásady **číslo pasu USA/Velké Británie** nakonfigurované s úrovní spolehlivosti 75 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo.</span><span class="sxs-lookup"><span data-stu-id="74d5e-107">For example, for a **US/UK passport number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span>
  
- <span data-ttu-id="74d5e-108">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Devět číslic</span><span class="sxs-lookup"><span data-stu-id="74d5e-108">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span>

- <span data-ttu-id="74d5e-109">**[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devět po sobě jdoucích číslic</span><span class="sxs-lookup"><span data-stu-id="74d5e-109">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span>

- <span data-ttu-id="74d5e-110">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, není žádný kontrolní součet.</span><span class="sxs-lookup"><span data-stu-id="74d5e-110">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="74d5e-111">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Zásady ochrany před únikem informací si je 75 % jisti, že byl zjištěn tento typ citlivých informací, pokud v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="74d5e-111">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="74d5e-112">Funkce Func_usa_uk_passport vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="74d5e-112">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>

  - <span data-ttu-id="74d5e-113">Bylo nalezeno klíčové slovo z Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="74d5e-113">A keyword from Keyword_passport is found.</span></span>

    <span data-ttu-id="74d5e-114">Například následující ukázka by aktivační událost pro **usa / Spojené království číslo pasu** politiky: Us Passport číslo 123456789</span><span class="sxs-lookup"><span data-stu-id="74d5e-114">For example, the following sample would trigger for the **US/UK passport number** policy: U.S. Passport number 123456789</span></span>

<span data-ttu-id="74d5e-115">Další informace o tom, co je požadováno pro zjištění čísla pasu USA/UK pro váš obsah, naleznete v následující části tohoto článku: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="74d5e-115">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="74d5e-116">Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="74d5e-116">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  