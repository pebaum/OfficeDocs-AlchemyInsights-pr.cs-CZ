---
title: Výměna klasického kořenového webu s moderním webem
ms.author: efrene
author: efrene
ms.date: 8/6/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: bd477d90ab7e6737aafffc57d931aad2bd0351e8
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36749253"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="db6bc-102">Výměna klasického kořenového webu s moderním webem</span><span class="sxs-lookup"><span data-stu-id="db6bc-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="db6bc-103">Pokud bylo prostředí nastaveno do dubna 2019, můžete pomocí prostředí Microsoft PowerShell změnit kořenový web na moderní web:</span><span class="sxs-lookup"><span data-stu-id="db6bc-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="db6bc-104">Pokud máte jiný web, který chcete použít jako kořenový web, můžete nahradit [(vyměnit) kořenový web](https://docs.microsoft.com/sharepoint/modern-root-site) .</span><span class="sxs-lookup"><span data-stu-id="db6bc-104">If you have a different site that you want to use as your root site, you can replace [(swap) the root site](https://docs.microsoft.com/sharepoint/modern-root-site) with it.</span></span> 
    - <span data-ttu-id="db6bc-105">Pomocí metody [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu zaměnit umístění webu s jiným webem.</span><span class="sxs-lookup"><span data-stu-id="db6bc-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="db6bc-106">K dispozici pro týmový web (není připojen ke skupině) a komunikační Web.</span><span class="sxs-lookup"><span data-stu-id="db6bc-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="db6bc-107">Další možnosti budou zavedeny brzy, což vám umožní nadále používat obsah webu, ale převést existující web na komunikační Web.</span><span class="sxs-lookup"><span data-stu-id="db6bc-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="db6bc-108">Tyto možnosti budou postupně vyvráceny.</span><span class="sxs-lookup"><span data-stu-id="db6bc-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="db6bc-109">Pokračujte v kontrole centra zpráv sady Office 365 pro aktualizace.</span><span class="sxs-lookup"><span data-stu-id="db6bc-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="db6bc-110">Známé problémy s odkládání webů</span><span class="sxs-lookup"><span data-stu-id="db6bc-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="db6bc-111">Cílový web může po krátkou dobu vrátit chybu "nenalezena" (HTTP 404).</span><span class="sxs-lookup"><span data-stu-id="db6bc-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="db6bc-112">Obsah bude nutné znovu prohledat, aby se aktualizoval vyhledávací index.</span><span class="sxs-lookup"><span data-stu-id="db6bc-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="db6bc-113">Není nutný žádný ruční krok-toto bude provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="db6bc-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="db6bc-114">Cokoli, co je závislé na "statických" odkazech (například soubory synchronizace souborů a OneNote), bude nutné ručně opravit.</span><span class="sxs-lookup"><span data-stu-id="db6bc-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="db6bc-115">Pokud byl zdrojový web diskusním webem organizace, aktualizujte adresu URL.</span><span class="sxs-lookup"><span data-stu-id="db6bc-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="db6bc-116">Získejte seznam všech organizačních diskusních serverů.</span><span class="sxs-lookup"><span data-stu-id="db6bc-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="db6bc-117">Je možné, že weby projektového serveru budou muset být ověřeny, aby bylo zajištěno, že jsou stále správně spojeny.</span><span class="sxs-lookup"><span data-stu-id="db6bc-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>





