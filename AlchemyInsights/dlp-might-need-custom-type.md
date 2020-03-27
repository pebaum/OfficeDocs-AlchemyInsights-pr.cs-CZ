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
ms.openlocfilehash: 87fcb5c3cc9ccd525265097b66d9d9b3a85c5feb
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977263"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="3ce5f-102">DLP může potřebovat vlastní typ</span><span class="sxs-lookup"><span data-stu-id="3ce5f-102">DLP might need a custom type</span></span>

<span data-ttu-id="3ce5f-103">**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)</span><span class="sxs-lookup"><span data-stu-id="3ce5f-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="3ce5f-104">**Ochrana před únikem informací může vyžadovat vlastní typ informací.**</span><span class="sxs-lookup"><span data-stu-id="3ce5f-104">**DLP may require a custom information type**</span></span>

<span data-ttu-id="3ce5f-105">Pomocí zásad ochrany před únikem dat (DLP) můžete identifikovat a chránit citlivá data ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="3ce5f-105">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="3ce5f-106">V některých případech může být nutné vytvořit vlastní **typ** citlivých informací k ochraně dat vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="3ce5f-106">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="3ce5f-107">Vaše organizace může například potřebovat identifikovat a chránit ID zaměstnanců nebo jiná data v nějakém formátu specifickém pro vaši organizaci. Pokud ano, naleznete další informace v následujících článcích.</span><span class="sxs-lookup"><span data-stu-id="3ce5f-107">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="3ce5f-108">**Přizpůsobení integrovaného typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="3ce5f-108">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="3ce5f-109">Pokud by vestavěný typ citlivých informací vyhovoval vašim potřebám pomocí několika úprav, můžete [přizpůsobit vestavěný typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="3ce5f-109">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="3ce5f-110">Můžete například přidat nebo odebrat klíčová slova nebo přidat nebo odebrat podpůrné důkazy, například datum nebo adresu.</span><span class="sxs-lookup"><span data-stu-id="3ce5f-110">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="3ce5f-111">**Vytvoření vlastního typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="3ce5f-111">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="3ce5f-112">Ale pokud potřebujete identifikovat a chránit jiný typ citlivých informací úplně, můžete [vytvořit vlastní typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) v ui centra pro & dodržování předpisů.</span><span class="sxs-lookup"><span data-stu-id="3ce5f-112">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="3ce5f-113">**Vytvoření vlastního typu citlivých informací v prostředí Security & Compliance Center PowerShell**</span><span class="sxs-lookup"><span data-stu-id="3ce5f-113">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="3ce5f-114">A konečně, pokud uI neposkytuje všechny možnosti, které potřebujete, můžete [vytvořit vlastní typ citlivých informací v zabezpečení & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="3ce5f-114">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="3ce5f-115">Začněte se souborem XML a můžete použít všechny dostupné možnosti.</span><span class="sxs-lookup"><span data-stu-id="3ce5f-115">By starting with an XML file, you can use every option available.</span></span>
