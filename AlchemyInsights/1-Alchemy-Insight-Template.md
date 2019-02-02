---
title: 'stejný jako název souboru je nejlepší [pravidlo #-popis]'
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 278a26f4b986a85e33442baef690d3bb44462ace
ms.sourcegitcommit: 32355b76d45b730a069575efeec708149d4aeaa3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/01/2019
ms.locfileid: "29697123"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="6ffc2-102">Nejsou k dispozici požadované Alchymie hlavičku H1, H2 je.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="6ffc2-103">Doporučené postupy a pokyny pro vytváření Alchymie:</span><span class="sxs-lookup"><span data-stu-id="6ffc2-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="6ffc2-p101">**Nelze vnořit Alchymie poznatky ve složkách**- tím dojde k porušení struktury adres url. Díváme se do tohoto řešení.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-p101">**Do not nest Alchemy Insights in folders**- this will break the url structure. We're looking into fixing this.</span></span>
1. <span data-ttu-id="6ffc2-106">Soubory ve složce **AlchemyInsights** by měl mít ID pravidla a pravidlo název [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net) v názvu souboru.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-106">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="6ffc2-p102">například ***976-How-to-enable-litigation-hold***</span><span class="sxs-lookup"><span data-stu-id="6ffc2-p102">ex. ***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="6ffc2-p103">Použití metadat v horní části tohoto souboru jako šablony. Nic jiného je vyžadován.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-p103">Use the metadata at the top of this file as your template. Nothing else is required.</span></span>
1. <span data-ttu-id="6ffc2-111">Na [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net), přejděte dolů k části **název odběratele přehled:** a použití, které jako počáteční bod pro váš nadpis H1 insight.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-111">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="6ffc2-p104">Alchymie poznatky musí mít pouze jeden H1 nahoře nebo bude přerušení výroby. H2s není vykreslit tak použití **tučného písma** nebo jiné konvence označuje samostatné oddíly.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-p104">Alchemy Insights MUST have only a single H1 at the top or they will break in production. H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="6ffc2-114">Dále v textu pomocí návrhu materiálu v sekci zákazník poznatky stránky Alchymie pravidlo výplně</span><span class="sxs-lookup"><span data-stu-id="6ffc2-114">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="6ffc2-115">Seznamy s odrážkami jsou jemné</span><span class="sxs-lookup"><span data-stu-id="6ffc2-115">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="6ffc2-116">Číslované seznamy příliš</span><span class="sxs-lookup"><span data-stu-id="6ffc2-116">Numbered lists too</span></span>
    1. <span data-ttu-id="6ffc2-117">**Tučné písmo** a *kurzívu* jsou a-ok</span><span class="sxs-lookup"><span data-stu-id="6ffc2-117">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="6ffc2-118">Odkazy by měly být vždy buď **"odkazy na web" / externí** nebo **hluboké odkazy na prvky uživatelského rozhraní**, nikoli vnitřní propojení.</span><span class="sxs-lookup"><span data-stu-id="6ffc2-118">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="6ffc2-p105">A to je ve skutečnosti již trochu příliš dlouhý. Nejlepší je asi 400 znaků---</span><span class="sxs-lookup"><span data-stu-id="6ffc2-p105">And this is really already a bit too long. Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="6ffc2-p106">Jakmile váš obsah je připraven, živé větve ho vytáhněte. Potom přejděte na [portál pro partnery Alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url. Ujistěte se, Insight přezkoumána a publikovány říká "Ano" a potom klepněte na tlačítko Aktualizovat pravidlo. **(To bude vypadat prettier v nové verzi portálu - uvolnění brzy.)** 
 ![pole url](media/for-content-team.PNG)</span><span class="sxs-lookup"><span data-stu-id="6ffc2-p106">Once your content is ready, pull it to the live branch. Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field. Make sure Insight reviewed and published says "yes" and then click Update Rule. **(This will look prettier in the new version of the portal - releasing soon.)**
![url field](media/for-content-team.PNG)</span></span>

