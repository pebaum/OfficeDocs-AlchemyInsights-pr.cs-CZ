---
title: stejný jako název souboru je nejlepší
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 31a578800468e9f3a69fff4f6e2e1945943c779c
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "35800038"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="96a92-102">Požadovaný Alchemy záhlaví H1, H2's nefunguje.</span><span class="sxs-lookup"><span data-stu-id="96a92-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="96a92-103">Doporučené postupy a pokyny pro tvorbu Alchemy:</span><span class="sxs-lookup"><span data-stu-id="96a92-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="96a92-104">**Nevnořit do složek Alchemy náhledy**-tím dojde k přerušení struktury adres URL.</span><span class="sxs-lookup"><span data-stu-id="96a92-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="96a92-105">Chceme to opravit.</span><span class="sxs-lookup"><span data-stu-id="96a92-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="96a92-106">Soubory ve složce **Alchemypostřehy** by měly být vybaveny malými názvy souborů s pomlčkami pro mezery ex.</span><span class="sxs-lookup"><span data-stu-id="96a92-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="96a92-107">***Postup-povolení-soudní***řízení.</span><span class="sxs-lookup"><span data-stu-id="96a92-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="96a92-108">Do vlastního pole MS. zahrňte ID pravidla nebo ID bloku z [portálu Alchemy partner](https://alchemyportal.azurewebsites.net) .</span><span class="sxs-lookup"><span data-stu-id="96a92-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="96a92-109">Ex.</span><span class="sxs-lookup"><span data-stu-id="96a92-109">ex.</span></span> <span data-ttu-id="96a92-110">***MS. Custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="96a92-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="96a92-111">Použijte zbývající metadata v horní části tohoto souboru jako šablonu.</span><span class="sxs-lookup"><span data-stu-id="96a92-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="96a92-112">V [portálu Alchemy partner](https://alchemyportal.azurewebsites.net)přejděte k části Přehled modulu pro **zákazníky:** a použijte jej jako výchozí bod pro váš titul H1.</span><span class="sxs-lookup"><span data-stu-id="96a92-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="96a92-113">Alchemy postřehy musí mít na vrcholu pouze jednu H1 nebo se rozlomí ve výrobě.</span><span class="sxs-lookup"><span data-stu-id="96a92-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="96a92-114">H2s se nevykreslí tak, že použijete **tučné** nebo jiné konvence k označení samostatných sekcí.</span><span class="sxs-lookup"><span data-stu-id="96a92-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="96a92-115">Dále vyplňte základní text pomocí konceptu materiálu v části pohledy zákazníka na stránce Alchemy Rule.</span><span class="sxs-lookup"><span data-stu-id="96a92-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="96a92-116">Seznamy s odrážkami jsou v pořádku</span><span class="sxs-lookup"><span data-stu-id="96a92-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="96a92-117">Číslované seznamy</span><span class="sxs-lookup"><span data-stu-id="96a92-117">Numbered lists too</span></span>
    1. <span data-ttu-id="96a92-118">**Tučné písmo** a *kurzíva* jsou-OK</span><span class="sxs-lookup"><span data-stu-id="96a92-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="96a92-119">Odkazy by měly být vždy buď **"odkazy na webové"/externí** nebo **hluboké-odkazy na prvky uživatelského rozhraní**, nikoli na interní vazby.</span><span class="sxs-lookup"><span data-stu-id="96a92-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="96a92-120">Obrázky nejsou v tuto chvíli oficiálně podporovány, ale jsou na cestovní mapě.</span><span class="sxs-lookup"><span data-stu-id="96a92-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="96a92-121">A tohle už je opravdu trochu moc dlouho.</span><span class="sxs-lookup"><span data-stu-id="96a92-121">And this is really already a bit too long.</span></span> <span data-ttu-id="96a92-122">Osvědčený postup je asi 400 znaků---------------------------------</span><span class="sxs-lookup"><span data-stu-id="96a92-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="96a92-123">Jakmile je obsah připraven, stáhněte jej do živé větve.</span><span class="sxs-lookup"><span data-stu-id="96a92-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="96a92-124">Potom přejděte na [portál Alchemy partner](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole adresy URL.</span><span class="sxs-lookup"><span data-stu-id="96a92-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> 