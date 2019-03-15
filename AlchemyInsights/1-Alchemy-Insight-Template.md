---
title: 'stejný jako název souboru je nejlepší [pravidlo #-popis]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: e248c2ee3cbb9a86f21c1f36be10c893df76ff52
ms.sourcegitcommit: 3070905131e6d8449981231a3551c0bb4ca38ae6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/14/2019
ms.locfileid: "30634497"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="1c2f2-102">Nejsou k dispozici požadované Alchymie hlavičku H1, H2 je.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="1c2f2-103">Doporučené postupy a pokyny pro vytváření Alchymie:</span><span class="sxs-lookup"><span data-stu-id="1c2f2-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="1c2f2-104">**Nelze vnořit Alchymie poznatky ve složkách**- tím dojde k porušení struktury adres url.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="1c2f2-105">Díváme se do tohoto řešení.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="1c2f2-106">Soubory ve složce **AlchemyInsights** by měl mít ID pravidla a pravidlo název [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net) v názvu souboru.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-106">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="1c2f2-107">ex.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-107">ex.</span></span> <span data-ttu-id="1c2f2-108">***976-How-to-enable-litigation-Hold***</span><span class="sxs-lookup"><span data-stu-id="1c2f2-108">***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="1c2f2-109">Použití metadat v horní části tohoto souboru jako šablony.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-109">Use the metadata at the top of this file as your template.</span></span> <span data-ttu-id="1c2f2-110">Nic jiného je vyžadován.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-110">Nothing else is required.</span></span>
1. <span data-ttu-id="1c2f2-111">Na [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net), přejděte dolů k části **název odběratele přehled:** a použití, které jako počáteční bod pro váš nadpis H1 insight.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-111">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="1c2f2-112">Alchymie poznatky musí mít pouze jeden H1 nahoře nebo bude přerušení výroby.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-112">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="1c2f2-113">H2s není vykreslit tak použití **tučného písma** nebo jiné konvence označuje samostatné oddíly.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-113">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="1c2f2-114">Dále v textu pomocí návrhu materiálu v sekci zákazník poznatky stránky Alchymie pravidlo výplně</span><span class="sxs-lookup"><span data-stu-id="1c2f2-114">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="1c2f2-115">Seznamy s odrážkami jsou jemné</span><span class="sxs-lookup"><span data-stu-id="1c2f2-115">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="1c2f2-116">Číslované seznamy příliš</span><span class="sxs-lookup"><span data-stu-id="1c2f2-116">Numbered lists too</span></span>
    1. <span data-ttu-id="1c2f2-117">**Tučné písmo** a *kurzívu* jsou a-ok</span><span class="sxs-lookup"><span data-stu-id="1c2f2-117">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="1c2f2-118">Odkazy by měly být vždy buď **"odkazy na web" / externí** nebo **hluboké odkazy na prvky uživatelského rozhraní**, nikoli vnitřní propojení.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-118">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="1c2f2-119">A to je ve skutečnosti již trochu příliš dlouhý.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-119">And this is really already a bit too long.</span></span> <span data-ttu-id="1c2f2-120">Nejlepší je asi 400 znaků---</span><span class="sxs-lookup"><span data-stu-id="1c2f2-120">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="1c2f2-121">Jakmile váš obsah je připraven, živé větve ho vytáhněte.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-121">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="1c2f2-122">Potom přejděte na [portál pro partnery Alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-122">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="1c2f2-123">Ujistěte se, Insight přezkoumána a publikovány říká "Ano" a potom klepněte na tlačítko Aktualizovat pravidlo.</span><span class="sxs-lookup"><span data-stu-id="1c2f2-123">Make sure Insight reviewed and published says "yes" and then click Update Rule.</span></span> <span data-ttu-id="1c2f2-124">**(To bude vypadat v nové verzi portálu - uvolnění brzy prettier.)** 
 ![pole url](media/for-content-team.PNG)</span><span class="sxs-lookup"><span data-stu-id="1c2f2-124">**(This will look prettier in the new version of the portal - releasing soon.)**
![url field](media/for-content-team.PNG)</span></span>

