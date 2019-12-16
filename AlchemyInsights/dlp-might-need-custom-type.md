---
title: DLP může potřebovat vlastní typ
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 872fca326065ada002300061c951620b3d9a8d0e
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052894"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="d630c-102">DLP může potřebovat vlastní typ</span><span class="sxs-lookup"><span data-stu-id="d630c-102">DLP might need a custom type</span></span>

<span data-ttu-id="d630c-103">Díky zásadám DLP (zabránění ztrátám dat) můžete identifikovat a chránit citlivá data v organizaci.</span><span class="sxs-lookup"><span data-stu-id="d630c-103">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="d630c-104">V některých případech může být nutné vytvořit **vlastní citlivý typ** informací pro ochranu dat organizace.</span><span class="sxs-lookup"><span data-stu-id="d630c-104">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="d630c-105">Vaše organizace může například potřebovat identifikovat a chránit ID zaměstnanců nebo jiná data v určitém formátu specifickém pro vaši organizaci. Pokud ano, naleznete další informace v následujících článcích.</span><span class="sxs-lookup"><span data-stu-id="d630c-105">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="d630c-106">**Přizpůsobení vestavěného typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="d630c-106">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="d630c-107">Pokud by vestavěný citlivý typ informací uspokojovali vaše potřeby pouze s několika typy úprav, můžete [upravit předdefinovaný typ informací](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="d630c-107">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="d630c-108">Můžete například přidat nebo odebrat klíčová slova nebo přidat nebo odebrat podpůrné doklady, například datum nebo adresu.</span><span class="sxs-lookup"><span data-stu-id="d630c-108">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="d630c-109">**Vytvoření vlastního typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="d630c-109">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="d630c-110">Pokud však potřebujete identifikovat a chránit jiný typ citlivých informací úplně, můžete [vytvořit vlastní citlivý typ informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) v uživatelském rozhraní centra kompatibility & zabezpečení.</span><span class="sxs-lookup"><span data-stu-id="d630c-110">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="d630c-111">**Vytvoření vlastního typu citlivých informací v zabezpečení & centrum kompatibility prostředí PowerShell**</span><span class="sxs-lookup"><span data-stu-id="d630c-111">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="d630c-112">Nakonec, pokud uživatelské rozhraní neposkytuje všechny potřebné možnosti, můžete [v okně zabezpečení & prostředí PowerShell v centru kompatibility vytvořit vlastní citlivý typ informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="d630c-112">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="d630c-113">Při spuštění pomocí souboru XML můžete použít všechny dostupné možnosti.</span><span class="sxs-lookup"><span data-stu-id="d630c-113">By starting with an XML file, you can use every option available.</span></span>
