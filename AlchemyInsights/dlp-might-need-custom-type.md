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
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932651"
---
# <a name="dlp-might-need-a-custom-type"></a><span data-ttu-id="0f7d9-102">DLP může potřebovat vlastní typ</span><span class="sxs-lookup"><span data-stu-id="0f7d9-102">DLP might need a custom type</span></span>

<span data-ttu-id="0f7d9-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="0f7d9-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="0f7d9-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="0f7d9-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="0f7d9-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="0f7d9-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="0f7d9-109">**Ochrana před únikem informací může vyžadovat vlastní typ informací.**</span><span class="sxs-lookup"><span data-stu-id="0f7d9-109">**DLP may require a custom information type**</span></span>

<span data-ttu-id="0f7d9-110">Pomocí zásad ochrany před únikem dat (DLP) můžete identifikovat a chránit citlivá data ve vaší organizaci.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-110">With a data loss prevention (DLP) policy, you can identify and protect sensitive data in your organization.</span></span> <span data-ttu-id="0f7d9-111">V některých případech může být nutné vytvořit vlastní **typ** citlivých informací k ochraně dat vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-111">In some scenarios, you might need to create your own **custom** sensitive information type to protect your organization's data.</span></span>

<span data-ttu-id="0f7d9-112">Vaše organizace může například potřebovat identifikovat a chránit ID zaměstnanců nebo jiná data v nějakém formátu specifickém pro vaši organizaci. Pokud ano, naleznete další informace v následujících článcích.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-112">For example, your organization might need to identify and protect employee IDs or other data in some format specific to your org. If so, see the following articles for more information.</span></span>
  
 <span data-ttu-id="0f7d9-113">**Přizpůsobení integrovaného typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="0f7d9-113">**Customize a built-in sensitive information type**</span></span>
  
<span data-ttu-id="0f7d9-114">Pokud by vestavěný typ citlivých informací vyhovoval vašim potřebám pomocí několika úprav, můžete [přizpůsobit vestavěný typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="0f7d9-114">If a built-in sensitive information type would meet your needs with just a few tweaks, you can [customize a built-in sensitive information type](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type).</span></span> <span data-ttu-id="0f7d9-115">Můžete například přidat nebo odebrat klíčová slova nebo přidat nebo odebrat podpůrné důkazy, například datum nebo adresu.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-115">For example, you can add or remove keywords, or add or remove supporting evidence such as a date or address.</span></span>
  
 <span data-ttu-id="0f7d9-116">**Vytvoření vlastního typu citlivých informací**</span><span class="sxs-lookup"><span data-stu-id="0f7d9-116">**Create a custom sensitive information type**</span></span>
  
<span data-ttu-id="0f7d9-117">Ale pokud potřebujete identifikovat a chránit jiný typ citlivých informací úplně, můžete [vytvořit vlastní typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) v ui centra pro & dodržování předpisů.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-117">But if you need to identify and protect a different type of sensitive information altogether, you can [create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) in the UI of the Security & Compliance Center.</span></span>
  
<span data-ttu-id="0f7d9-118">**Vytvoření vlastního typu citlivých informací v prostředí Security & Compliance Center PowerShell**</span><span class="sxs-lookup"><span data-stu-id="0f7d9-118">**Create a custom sensitive information type in Security & Compliance Center PowerShell**</span></span>

<span data-ttu-id="0f7d9-119">A konečně, pokud uI neposkytuje všechny možnosti, které potřebujete, můžete [vytvořit vlastní typ citlivých informací v zabezpečení & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span><span class="sxs-lookup"><span data-stu-id="0f7d9-119">Finally, if the UI doesn't provide all the options you need, you can [create a custom sensitive information type in Security & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell).</span></span> <span data-ttu-id="0f7d9-120">Začněte se souborem XML a můžete použít všechny dostupné možnosti.</span><span class="sxs-lookup"><span data-stu-id="0f7d9-120">By starting with an XML file, you can use every option available.</span></span>
