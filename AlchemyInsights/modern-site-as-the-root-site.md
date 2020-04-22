---
title: Moderní web jako kořenový web
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.date: 04/21/2020
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: 0388f95e2b7815dcbbb6aca200f44e55e9c5724f
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713784"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="37bf3-102">Moderní web jako kořenový web</span><span class="sxs-lookup"><span data-stu-id="37bf3-102">Modern site as root site</span></span>

<span data-ttu-id="37bf3-103">Začali jsme zavádět novou funkci, která vám umožní [vyměnit váš klasický kořenový web s moderním webem](https://docs.microsoft.com/sharepoint/modern-root-site).</span><span class="sxs-lookup"><span data-stu-id="37bf3-103">We have begun to rollout a new feature that will allow you to [swap your classic site root site with a modern site](https://docs.microsoft.com/sharepoint/modern-root-site).</span></span> <span data-ttu-id="37bf3-104">Pomocí [invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu vyměnit umístění webu s jiným webem.</span><span class="sxs-lookup"><span data-stu-id="37bf3-104">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="37bf3-105">K dispozici jak pro týmový web (není připojen ke skupině), tak pro komunikační web.</span><span class="sxs-lookup"><span data-stu-id="37bf3-105">Available for both Team Site (not connected to a group) and Communication Site.</span></span>

>[!Important]
> <span data-ttu-id="37bf3-106">Neodstraňujte klasický kořenový web a vytvořte moderní komunikační web.</span><span class="sxs-lookup"><span data-stu-id="37bf3-106">Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="37bf3-107">Společnost Microsoft to nepodporuje.</span><span class="sxs-lookup"><span data-stu-id="37bf3-107">This is not supported by Microsoft.</span></span> <span data-ttu-id="37bf3-108">Odstraněním kořenového webu budou všechny weby služby SharePoint ve vaší organizaci nepřístupné všem uživatelům, dokud web neobnovíte nebo nevytvoříte nový web na stejné adrese URL.</span><span class="sxs-lookup"><span data-stu-id="37bf3-108">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> <span data-ttu-id="37bf3-109">Tuto funkci budeme komunikovat prostřednictvím centra zpráv.</span><span class="sxs-lookup"><span data-stu-id="37bf3-109">We’ll be communicating this feature via the message center.</span></span> <span data-ttu-id="37bf3-110">Měli byste očekávat, že funkce, která má být zapnuta ve vašem tenantovi v brzké době.</span><span class="sxs-lookup"><span data-stu-id="37bf3-110">You should expect the feature to be turned on in your tenant shortly.</span></span>

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="37bf3-111">Známé problémy s výměnou webů</span><span class="sxs-lookup"><span data-stu-id="37bf3-111">Known issues with swapping sites</span></span>
- <span data-ttu-id="37bf3-112">Cílový web může vrátit chybu "nebyl nalezen" (HTTP 404) na krátkou dobu.</span><span class="sxs-lookup"><span data-stu-id="37bf3-112">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="37bf3-113">Obsah bude nutné znovu procházet, aby se aktualizoval index vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="37bf3-113">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="37bf3-114">Zde není nutný žádný ruční krok, bude to provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="37bf3-114">There is no manual step required here, this will be done automatically.</span></span>
- <span data-ttu-id="37bf3-115">Vše, co závisí na "statických" odkazech (například synchronizace souborů a soubory aplikace OneNote), bude nutné ručně opravit.</span><span class="sxs-lookup"><span data-stu-id="37bf3-115">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="37bf3-116">Servery microsoftoffice může být nutné ověřit, aby bylo zajištěno, že jsou stále správně přidruženy.</span><span class="sxs-lookup"><span data-stu-id="37bf3-116">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span> 
