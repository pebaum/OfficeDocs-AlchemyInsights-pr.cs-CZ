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
ms.openlocfilehash: 0b5c1fb175275028c56e47080708520fe115fb38
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932508"
---
# <a name="dlp-issues-with-us-bank-account-numbers"></a><span data-ttu-id="0e670-102">DLP problémy s čísly bankovních účtů v USA</span><span class="sxs-lookup"><span data-stu-id="0e670-102">DLP issues with US bank account numbers</span></span>

<span data-ttu-id="0e670-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="0e670-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="0e670-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="0e670-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="0e670-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="0e670-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="0e670-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="0e670-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="0e670-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="0e670-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="0e670-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="0e670-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="0e670-109">**DLP problémy s čísly bankovních účtů v USA**</span><span class="sxs-lookup"><span data-stu-id="0e670-109">**DLP issues with US bank account numbers**</span></span>

<span data-ttu-id="0e670-110">Máte problémy s **prevencí před únikem dat (DLP),** která nefunguje pro obsah obsahující **číslo bankovního účtu v USA** při použití typu citlivých informací dlp v O365?</span><span class="sxs-lookup"><span data-stu-id="0e670-110">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US Bank Account Number** when using a DLP sensitive information type in O365?</span></span> <span data-ttu-id="0e670-111">Pokud ano, ujistěte se, že váš obsah obsahuje potřebné informace o tom, co zásady ochrany před únikem informací hledá při vyhodnocení.</span><span class="sxs-lookup"><span data-stu-id="0e670-111">If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span>
  
<span data-ttu-id="0e670-112">Například pro zásady **číslo bankovního účtu v USA** nakonfigurované s úrovní spolehlivosti 85 % jsou vyhodnoceny následující a musí být zjištěny, aby se pravidlo aktivovalo:</span><span class="sxs-lookup"><span data-stu-id="0e670-112">For example, for a **US Bank Account Number** policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="0e670-113">**[Formát:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 číslic</span><span class="sxs-lookup"><span data-stu-id="0e670-113">**[Format:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** 8-17 digits</span></span>

- <span data-ttu-id="0e670-114">**[Vzor:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 po sobě jdoucích číslic.</span><span class="sxs-lookup"><span data-stu-id="0e670-114">**[Pattern:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** 8-17 consecutive digits.</span></span>

- <span data-ttu-id="0e670-115">**[Kontrolní součet:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Ne, není žádný kontrolní součet.</span><span class="sxs-lookup"><span data-stu-id="0e670-115">**[Checksum:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span>

- <span data-ttu-id="0e670-116">**[Definice:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** Zásady ochrany před únikem informací si je 75 % jisti, že byl zjištěn tento typ citlivých informací, pokud v blízkosti 300 znaků:</span><span class="sxs-lookup"><span data-stu-id="0e670-116">**[Definition:](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span>

  - <span data-ttu-id="0e670-117">Regulární výraz Regex_usa_bank_account_number vyhledá obsah, který odpovídá vzoru</span><span class="sxs-lookup"><span data-stu-id="0e670-117">The regular expression Regex_usa_bank_account_number finds content that matches the pattern</span></span>

  - <span data-ttu-id="0e670-118">Bylo nalezeno klíčové slovo z Keyword_usa_Bank_Account.</span><span class="sxs-lookup"><span data-stu-id="0e670-118">A keyword from Keyword_usa_Bank_Account is found.</span></span>

    <span data-ttu-id="0e670-119">Například následující ukázka by aktivační událost pro zásady **číslo bankovního účtu v USA:** Běžný účet 78344011</span><span class="sxs-lookup"><span data-stu-id="0e670-119">For example, the following sample would trigger for the **US Bank Account Number** policy: Checking Account 78344011</span></span>

<span data-ttu-id="0e670-120">Další informace o tom, co je požadováno pro zjištění **čísla bankovního účtu v USA,** naleznete v následující části tohoto článku: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span><span class="sxs-lookup"><span data-stu-id="0e670-120">For more information on what is required for a **US Bank Account Number** to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US Bank Account Number](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-bank-account-number)</span></span>
  
<span data-ttu-id="0e670-121">Použití jiného typu integrovaných citlivých informací naleznete v následujícím článku, kde najdete informace o tom, co je požadováno pro jiné typy: [Co hledají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="0e670-121">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  