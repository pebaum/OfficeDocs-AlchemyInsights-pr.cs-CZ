---
title: DLP může potřebovat vlastní typ
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: b83bb77383e2ae7e78c31f35c972182c54487c60
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704482"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="7d7ff-102">DLP může potřebovat vlastní typ</span><span class="sxs-lookup"><span data-stu-id="7d7ff-102">DLP might need a custom type</span></span>

<span data-ttu-id="7d7ff-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="7d7ff-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="7d7ff-104">**Ochrana před únikem informací může vyžadovat vlastní typ informací.**</span><span class="sxs-lookup"><span data-stu-id="7d7ff-104">**DLP may require a custom information type**</span></span>

<span data-ttu-id="7d7ff-105">Pomocí zásad ochrany před únikem dat (DLP) můžete identifikovat a chránit citlivá data ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="7d7ff-105">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="7d7ff-106">V některých případech může být nutné vytvořit vlastní **typ** citlivých informací k ochraně dat vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="7d7ff-106">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="7d7ff-107">Vaše organizace může například potřebovat identifikovat a chránit ID zaměstnanců nebo jiná data v nějakém formátu specifickém pro vaši organizaci. Pokud ano, naleznete další informace v následujících článcích.</span><span class="sxs-lookup"><span data-stu-id="7d7ff-107">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="7d7ff-108">**Přizpůsobení integrovaného typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="7d7ff-108">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="7d7ff-109">Pokud by vestavěný typ citlivých informací vyhovoval vašim potřebám pomocí několika úprav, můžete [přizpůsobit vestavěný typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="7d7ff-109">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="7d7ff-110">Můžete například přidat nebo odebrat klíčová slova nebo přidat nebo odebrat podpůrné důkazy, například datum nebo adresu.</span><span class="sxs-lookup"><span data-stu-id="7d7ff-110">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="7d7ff-111">**Vytvoření vlastního typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="7d7ff-111">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="7d7ff-112">Ale pokud potřebujete identifikovat a chránit jiný typ citlivých informací úplně, můžete [vytvořit vlastní typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) v ui centra pro & dodržování předpisů.</span><span class="sxs-lookup"><span data-stu-id="7d7ff-112">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="7d7ff-113">**Vytvoření vlastního typu citlivých informací v prostředí Security & Compliance Center PowerShell**</span><span class="sxs-lookup"><span data-stu-id="7d7ff-113">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="7d7ff-114">A konečně, pokud uI neposkytuje všechny možnosti, které potřebujete, můžete [vytvořit vlastní typ citlivých informací v zabezpečení & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="7d7ff-114">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="7d7ff-115">Začněte se souborem XML a můžete použít všechny dostupné možnosti.</span><span class="sxs-lookup"><span data-stu-id="7d7ff-115">By starting with an XML file, you can use every option available.</span></span>
