---
title: DLP pravidlo pro US / UK číslo pasu nefunguje
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
ms.openlocfilehash: bc91af8be58d49204f84cd7d22f481348af3c013
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529912"
---
# <a name="problems-with-dlp---usuk-passport-numbers"></a><span data-ttu-id="17af9-102">Problémy s DLP - USA / UK čísla účtu služby Passport</span><span class="sxs-lookup"><span data-stu-id="17af9-102">Problems with DLP - US/UK Passport Numbers</span></span>

<span data-ttu-id="17af9-103">Máte problémy s **Dat ztráta prevence (DLP)** obsahující obsahu nefunguje **US / UK číslo pasu** při použití typu DLP citlivých informací v O365?</span><span class="sxs-lookup"><span data-stu-id="17af9-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="17af9-104">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro co zásady DLP hledá Pokud je vyhodnocena.</span><span class="sxs-lookup"><span data-stu-id="17af9-104">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="17af9-105">Například **US / UK číslo pasu** zásad nakonfigurován s konfidenční úrovni 75 %, následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit</span><span class="sxs-lookup"><span data-stu-id="17af9-105">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span>
  
- <span data-ttu-id="17af9-106">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Číslice devět</span><span class="sxs-lookup"><span data-stu-id="17af9-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span>

- <span data-ttu-id="17af9-107">**[Vzorek:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Devět po sobě jdoucích číslic.</span><span class="sxs-lookup"><span data-stu-id="17af9-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span>

- <span data-ttu-id="17af9-108">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, neexistuje žádný kontrolní součet</span><span class="sxs-lookup"><span data-stu-id="17af9-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="17af9-109">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Zásady DLP je 75 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="17af9-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="17af9-110">Funkce Func_usa_uk_passport vyhledá obsah, který odpovídá vzoru.</span><span class="sxs-lookup"><span data-stu-id="17af9-110">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>

  - <span data-ttu-id="17af9-111">Klíčové slovo z Keyword_passport nebyla nalezena.</span><span class="sxs-lookup"><span data-stu-id="17af9-111">A keyword from Keyword_passport is found.</span></span>

    <span data-ttu-id="17af9-112">Například následující ukázka by znamenala pro **US / UK číslo pasu** zásad: Passport USA číslo 123456789</span><span class="sxs-lookup"><span data-stu-id="17af9-112">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span>

<span data-ttu-id="17af9-113">Další informace o co je požadováno pro americké / číslo pasu UK zjistit obsah, naleznete v následující části v tomto článku: [co citlivé informace typy vzhledu pro USA / UK číslo pasu](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="17af9-113">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="17af9-114">Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="17af9-114">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  