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
ms.openlocfilehash: 1bb1cb35f06e16a2dc85b7e2642b9fa0d203945e
ms.sourcegitcommit: b032c2ac45540b1eb5dd68a4ec7ce1a5d6922f0e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662923"
---
# <a name="required-customer-facing-h1-h2-doesnt-work"></a><span data-ttu-id="86305-102">Požadováno zákazníkem čelí H1, H2 nefunguje.</span><span class="sxs-lookup"><span data-stu-id="86305-102">Required Customer Facing H1, H2 doesn't work</span></span>
<span data-ttu-id="86305-103">Příklad textového bloku - postupujte podle následujících pokynů:</span><span class="sxs-lookup"><span data-stu-id="86305-103">Example text block - follow these instructions:</span></span>

1. <span data-ttu-id="86305-104">Soubory ve složce **AlchemyInsights** by měl mít ID pravidla a pravidlo název [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net) v názvu souboru.</span><span class="sxs-lookup"><span data-stu-id="86305-104">Files in the **AlchemyInsights** folder should have Rule ID and Rule Name from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the filename.</span></span>
    1. <span data-ttu-id="86305-p101">například ***976-How-to-enable-litigation-hold***</span><span class="sxs-lookup"><span data-stu-id="86305-p101">ex. ***976-How-to-enable-litigation-hold***</span></span>
1. <span data-ttu-id="86305-p102">Použití metadat v horní části tohoto souboru jako šablony. Nic jiného je vyžadován.</span><span class="sxs-lookup"><span data-stu-id="86305-p102">Use the metadata at the top of this file as your template. Nothing else is required.</span></span>
1. <span data-ttu-id="86305-109">Na [portálu pro partnery Alchymie](https://alchemyportal.azurewebsites.net), přejděte dolů k části **název odběratele přehled:** a použití, které jako počáteční bod pro váš nadpis H1 insight.</span><span class="sxs-lookup"><span data-stu-id="86305-109">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="86305-p103">Alchymie poznatky musí mít pouze jeden H1 nahoře nebo bude přerušení výroby. H2s není vykreslit tak použití **tučného písma** nebo jiné konvence označuje samostatné oddíly.</span><span class="sxs-lookup"><span data-stu-id="86305-p103">Alchemy Insights MUST have only a single H1 at the top or they will break in production. H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="86305-112">Dále v textu pomocí návrhu materiálu v sekci zákazník poznatky stránky Alchymie pravidlo výplně</span><span class="sxs-lookup"><span data-stu-id="86305-112">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="86305-113">Seznamy s odrážkami jsou jemné</span><span class="sxs-lookup"><span data-stu-id="86305-113">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="86305-114">Číslované seznamy příliš</span><span class="sxs-lookup"><span data-stu-id="86305-114">Numbered lists too</span></span>
    1. <span data-ttu-id="86305-115">**Tučné písmo** a *kurzívu* jsou a-ok</span><span class="sxs-lookup"><span data-stu-id="86305-115">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="86305-116">Odkazy by měly být vždy buď **"odkazy na web" / externí** nebo **hluboké odkazy na prvky uživatelského rozhraní**, nikoli vnitřní propojení.</span><span class="sxs-lookup"><span data-stu-id="86305-116">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>

<span data-ttu-id="86305-p104">A to je ve skutečnosti již trochu příliš dlouhý. Nejlepší je asi 400 znaků---</span><span class="sxs-lookup"><span data-stu-id="86305-p104">And this is really already a bit too long. Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="86305-p105">Jakmile váš obsah je připraven, živé větve ho vytáhněte. Potom přejděte na [portál pro partnery Alchymie](https://alchemyportal.azurewebsites.net) a zadejte název souboru do pole url. Ujistěte se, Insight přezkoumána a publikovány říká "Ano" a potom klepněte na tlačítko Aktualizovat pravidlo. (To bude vypadat prettier v nové verzi portálu - uvolnění brzy.)</span><span class="sxs-lookup"><span data-stu-id="86305-p105">Once your content is ready, pull it to the live branch. Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field. Make sure Insight reviewed and published says "yes" and then click Update Rule. (This will look prettier in the new version of the portal - releasing soon.)</span></span>

![pole URL](media/for-content-team.PNG)

