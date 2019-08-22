---
title: DLP pravidlo pro nás číslo bankovního účtu nefunguje
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
ms.openlocfilehash: 0a32708b5ac8d95ec6777ada2d151a15f90d65bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36529854"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="3230f-102">DLP problémy s námi čísla bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="3230f-102">DLP issues with US Bank Account Numbers</span></span>

<span data-ttu-id="3230f-103">Došlo k potížím s **Dat ztráta prevence (DLP)** nefunguje pro obsah při použití typu DLP citlivých informací v O365 obsahující **Číslo bankovního účtu v USA** ?</span><span class="sxs-lookup"><span data-stu-id="3230f-103">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="3230f-104">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace pro co zásady DLP hledá Pokud je vyhodnocena.</span><span class="sxs-lookup"><span data-stu-id="3230f-104">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="3230f-105">Například **Číslo bankovního účtu USA** zásad nakonfigurován s konfidenční úrovni 85 % následující jsou vyhodnocovány a musí být rozpoznány pro pravidlo spustit:</span><span class="sxs-lookup"><span data-stu-id="3230f-105">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="3230f-106">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** číslice 8-17</span><span class="sxs-lookup"><span data-stu-id="3230f-106">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="3230f-107">**[Vzorek:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 po sobě jdoucích číslic.</span><span class="sxs-lookup"><span data-stu-id="3230f-107">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="3230f-108">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, neexistuje žádný kontrolní součet</span><span class="sxs-lookup"><span data-stu-id="3230f-108">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="3230f-109">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Zásady DLP je 75 % jistotu, že zjistil tento druh důvěrné informace, jestliže Rada do vzdálenosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="3230f-109">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="3230f-110">Obsah, který odpovídá vzoru nalezne regulární výraz Regex_usa_bank_account_number</span><span class="sxs-lookup"><span data-stu-id="3230f-110">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="3230f-111">Klíčové slovo z Keyword_usa_Bank_Account nebyla nalezena.</span><span class="sxs-lookup"><span data-stu-id="3230f-111">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="3230f-112">Například následující ukázka by znamenala pro politiku **USA číslo bankovního účtu** : běžný účet 78344011</span><span class="sxs-lookup"><span data-stu-id="3230f-112">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="3230f-113">Další informace o co je požadováno pro **USA číslo bankovního účtu** zjistit pro váš obsah, naleznete v následující části v tomto článku: [Co citlivé typy informací vyhledejte číslo bankovního účtu v USA](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="3230f-113">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="3230f-114">Pomocí různých předdefinovaných citlivé informace typu, naleznete v následujícím článku informace o co je požadováno pro jiné typy: [Hledat co citlivé typy informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="3230f-114">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  