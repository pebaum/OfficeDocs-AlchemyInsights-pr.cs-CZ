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
ms.openlocfilehash: 1ec8959a479f1a8f7bfcffb55f440e8c4ab435fb
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507507"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="deb15-102">DLP může potřebovat vlastní typ</span><span class="sxs-lookup"><span data-stu-id="deb15-102">DLP might need a custom type</span></span>

<span data-ttu-id="deb15-103">**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="deb15-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="deb15-104">**Ochrana před únikem informací může vyžadovat vlastní typ informací.**</span><span class="sxs-lookup"><span data-stu-id="deb15-104">**DLP may require a custom information type**</span></span>

<span data-ttu-id="deb15-105">Pomocí zásad ochrany před únikem dat (DLP) můžete identifikovat a chránit citlivá data ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="deb15-105">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="deb15-106">V některých případech může být nutné vytvořit **vlastní** typ citlivých informací k ochraně dat vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="deb15-106">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="deb15-107">Vaše organizace může například potřebovat identifikovat a chránit ID zaměstnanců nebo jiná data v nějakém formátu specifickém pro vaši organizaci. Pokud ano, naleznete v následujících článcích další informace.</span><span class="sxs-lookup"><span data-stu-id="deb15-107">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="deb15-108">**Přizpůsobení integrovaného typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="deb15-108">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="deb15-109">Pokud by vestavěný typ citlivých informací vyhovoval vašim potřebám pomocí několika vylepšení, můžete [přizpůsobit vestavěný typ citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="deb15-109">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/microsoft-365/compliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="deb15-110">Můžete například přidat nebo odebrat klíčová slova nebo přidat nebo odebrat podpůrné důkazy, například datum nebo adresu.</span><span class="sxs-lookup"><span data-stu-id="deb15-110">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="deb15-111">**Vytvoření vlastního typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="deb15-111">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="deb15-112">Pokud však potřebujete zcela identifikovat a chránit jiný typ citlivých informací, můžete [vytvořit vlastní typ citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type) v uživatelském rozhraní Centra zabezpečení & dodržování předpisů.</span><span class="sxs-lookup"><span data-stu-id="deb15-112">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="deb15-113">**Vytvoření vlastního typu citlivých informací v prostředí Security & Compliance Center PowerShell**</span><span class="sxs-lookup"><span data-stu-id="deb15-113">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="deb15-114">A konečně, pokud uživatelské rozhraní neposkytuje všechny možnosti, které potřebujete, můžete [vytvořit vlastní typ citlivých informací v Centru zabezpečení & Prostředí dodržování předpisů](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="deb15-114">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="deb15-115">Spuštěním souboru XML můžete použít všechny dostupné možnosti.</span><span class="sxs-lookup"><span data-stu-id="deb15-115">By starting with an XML file, you can use every option available.</span></span>
