---
title: Výměna klasického kořenového webu za moderní web
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: ''
ms.custom:
- "9000687"
- "2579"
ms.openlocfilehash: f4831c6a232a4dee0f8f5ac0c83e4307221cfe2d
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741537"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="b456d-102">Výměna klasického kořenového webu za moderní web</span><span class="sxs-lookup"><span data-stu-id="b456d-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="b456d-103">Pokud bylo vaše prostředí nastaveno před dubnem 2019, můžete změnit kořenový web na moderní web pomocí prostředí Microsoft PowerShell:</span><span class="sxs-lookup"><span data-stu-id="b456d-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="b456d-104">Pokud máte jiný web, který chcete použít jako kořenový web, můžete s ním nahradit [(swapovat) kořenový web.](https://docs.microsoft.com/sharepoint/modern-root-site)</span><span class="sxs-lookup"><span data-stu-id="b456d-104">If you have a different site that you want to use as your root site, you can replace [(swap) the root site](https://docs.microsoft.com/sharepoint/modern-root-site) with it.</span></span> 
    - <span data-ttu-id="b456d-105">Pomocí [invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu vyměnit umístění webu s jiným webem.</span><span class="sxs-lookup"><span data-stu-id="b456d-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="b456d-106">K dispozici jak pro týmový web (není připojen ke skupině), tak pro komunikační web.</span><span class="sxs-lookup"><span data-stu-id="b456d-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="b456d-107">Brzy budou zavedeny další funkce, které vám umožní pokračovat v používání obsahu na webu, ale převést stávající web na komunikační web.</span><span class="sxs-lookup"><span data-stu-id="b456d-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="b456d-108">Tyto možnosti budou postupně zaváděny.</span><span class="sxs-lookup"><span data-stu-id="b456d-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="b456d-109">Pokračujte v kontrole aktualizací v Centru zpráv.</span><span class="sxs-lookup"><span data-stu-id="b456d-109">Continue to check the Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="b456d-110">Známé problémy s výměnou webů</span><span class="sxs-lookup"><span data-stu-id="b456d-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="b456d-111">Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.</span><span class="sxs-lookup"><span data-stu-id="b456d-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="b456d-112">Obsah bude nutné znovu procházet, aby se aktualizoval index vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="b456d-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="b456d-113">Není vyžadován žádný ruční krok - to bude provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="b456d-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="b456d-114">Vše, co závisí na "statických" odkazech (například synchronizace souborů a soubory aplikace OneNote), bude nutné ručně opravit.</span><span class="sxs-lookup"><span data-stu-id="b456d-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="b456d-115">Pokud byl zdrojový web organizační zpravodajský web, aktualizujte adresu URL.</span><span class="sxs-lookup"><span data-stu-id="b456d-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="b456d-116">Získejte seznam všech organizačních zpravodajských webů.</span><span class="sxs-lookup"><span data-stu-id="b456d-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="b456d-117">Servery microsoftoffice může být nutné ověřit, aby bylo zajištěno, že jsou stále správně přidruženy.</span><span class="sxs-lookup"><span data-stu-id="b456d-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>
