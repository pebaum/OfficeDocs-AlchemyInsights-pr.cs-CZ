---
title: Zaměnit s moderním webu kořenového webu Classic
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
ms.openlocfilehash: ffb1466fe436d6cab7ae5fdd60c671f5dd2654dd
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36501072"
---
# <a name="swap-your-classic-root-site-with-a-modern-site"></a><span data-ttu-id="67ca7-102">Zaměnit s moderním webu kořenového webu Classic</span><span class="sxs-lookup"><span data-stu-id="67ca7-102">Swap your Classic root site with a Modern site</span></span>

<span data-ttu-id="67ca7-103">Pokud vaše prostředí byla nastavena před duben 2019, moderní web můžete změnit kořenový web pomocí Microsoft PowerShell:</span><span class="sxs-lookup"><span data-stu-id="67ca7-103">If your environment was set up before April 2019, you can change your root site to a modern site by using Microsoft PowerShell:</span></span>

- <span data-ttu-id="67ca7-104">Pokud máte jiný server, který chcete použít jako kořenový web, můžete nahradit (swap) kořenovém webu ji.</span><span class="sxs-lookup"><span data-stu-id="67ca7-104">If you have a different site that you want to use as your root site, you can replace (swap) the root site with it.</span></span> 
    - <span data-ttu-id="67ca7-105">Zaměnit umístění serveru s jinou lokalitou při archivaci původního webu pomocí [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="67ca7-105">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="67ca7-106">K dispozici pro týmový web (bez připojení do skupiny) a komunikační sítě.</span><span class="sxs-lookup"><span data-stu-id="67ca7-106">Available for both Team Site (not connected to a group) and Communication Site.</span></span> 

- <span data-ttu-id="67ca7-107">Další funkce budou zavedeny brzy, bude možné nadále používat obsah na webu, ale převést stávající web do komunikační sítě.</span><span class="sxs-lookup"><span data-stu-id="67ca7-107">Additional capabilities will be introduced soon that will allow you to keep using the content on the site, but convert the existing site to a communication site.</span></span> 
>[!Important]
><span data-ttu-id="67ca7-108">Tyto možnosti budou vrácena postupně.</span><span class="sxs-lookup"><span data-stu-id="67ca7-108">These capabilities will be rolled out gradually.</span></span> <span data-ttu-id="67ca7-109">Dále zkontrolujte Centrum Office 365 zprávy aktualizace.</span><span class="sxs-lookup"><span data-stu-id="67ca7-109">Continue to check the Office 365 Message Center for updates.</span></span> 

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="67ca7-110">Známé problémy týkající se výměny serverů</span><span class="sxs-lookup"><span data-stu-id="67ca7-110">Known issues with swapping sites</span></span>

- <span data-ttu-id="67ca7-111">Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.</span><span class="sxs-lookup"><span data-stu-id="67ca7-111">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="67ca7-112">Obsah bude třeba položka znovu prohledána aktualizace indexu vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="67ca7-112">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="67ca7-113">Neexistuje žádná ruční požadovaným krokem – to bude provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="67ca7-113">There is no manual step required - this will be done automatically.</span></span>
- <span data-ttu-id="67ca7-114">Vše závisí na "statické" propojení (například synchronizaci souboru a aplikace OneNote soubory) nutné ručně korigovat.</span><span class="sxs-lookup"><span data-stu-id="67ca7-114">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="67ca7-115">Pokud je zdrojový web serveru novinky týkající se organizace, aktualizujte adresu URL.</span><span class="sxs-lookup"><span data-stu-id="67ca7-115">If the source site was an organizational news site, update the URL.</span></span><span data-ttu-id="67ca7-116">Zobrazit seznam všech organizačních diskusní servery.</span><span class="sxs-lookup"><span data-stu-id="67ca7-116"> Get a list of all organizational news sites.</span></span>
- <span data-ttu-id="67ca7-117">Weby aplikace Project Server bude pravděpodobně nutné ověřit, aby zajistit, aby byly správně stále spojeny.</span><span class="sxs-lookup"><span data-stu-id="67ca7-117">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span>





