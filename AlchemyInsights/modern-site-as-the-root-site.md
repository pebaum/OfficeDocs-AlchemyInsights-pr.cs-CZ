---
title: Moderní web jako kořenový web
ms.author: efrene
author: efrene
ms.audience: ITPro
ms.topic: article
ms.date: 8/7/2019
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000265"
- "1874"
ms.openlocfilehash: a3cf44d52a3948634fc0eed64c852ff17515fd9b
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36753897"
---
# <a name="modern-site-as-root-site"></a><span data-ttu-id="1ff5d-102">Moderní web jako kořenový web</span><span class="sxs-lookup"><span data-stu-id="1ff5d-102">Modern site as root site</span></span>

<span data-ttu-id="1ff5d-103">Zahájili jsme novou funkci, která vám umožní [vyměnit klasickou kořenovou lokalitu webů s moderním webem](https://docs.microsoft.com/sharepoint/modern-root-site).</span><span class="sxs-lookup"><span data-stu-id="1ff5d-103">We have begun to rollout a new feature that will allow you to [swap your classic site root site with a modern site](https://docs.microsoft.com/sharepoint/modern-root-site).</span></span> <span data-ttu-id="1ff5d-104">Pomocí metody [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) můžete při archivaci původního webu zaměnit umístění webu s jiným webem.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-104">Use [Invoke-SPOSiteSwap](https://docs.microsoft.com/powershell/module/sharepoint-online/invoke-spositeswap?view=sharepoint-ps) to swap the location of a site with another site while archiving the original site.</span></span> <span data-ttu-id="1ff5d-105">K dispozici pro týmový web (není připojen ke skupině) a komunikační Web.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-105">Available for both Team Site (not connected to a group) and Communication Site.</span></span>

>[!Important]
> <span data-ttu-id="1ff5d-106">Neodstraňujte klasickou kořenovou lokalitu, abyste vytvořili moderní komunikační Web.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-106">Do not delete your classic root site to create a modern Communication Site.</span></span> <span data-ttu-id="1ff5d-107">Společnost Microsoft tuto podporu nepodporuje.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-107">This is not supported by Microsoft.</span></span> <span data-ttu-id="1ff5d-108">Odstranění kořenového webu způsobí, že všechny weby služby SharePoint ve vaší organizaci nebudou přístupné všem uživatelům, dokud web neobnovíte nebo vytvoříte nový web na stejné adrese URL.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-108">Deleting the root site will make all SharePoint sites in your organization inaccessible to all users, until you restore the site or create a new site at the same URL.</span></span> <span data-ttu-id="1ff5d-109">Tuto funkci budeme komunikovat prostřednictvím centra zpráv.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-109">We’ll be communicating this feature via the message center.</span></span> <span data-ttu-id="1ff5d-110">Měli byste očekávat, že bude funkce v nájemci brzy zapnuta.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-110">You should expect the feature to be turned on in your tenant shortly.</span></span>

## <a name="known-issues-with-swapping-sites"></a><span data-ttu-id="1ff5d-111">Známé problémy s odkládání webů</span><span class="sxs-lookup"><span data-stu-id="1ff5d-111">Known issues with swapping sites</span></span>
- <span data-ttu-id="1ff5d-112">Cílový web může po krátkou dobu vrátit chybu "nenalezena" (HTTP 404).</span><span class="sxs-lookup"><span data-stu-id="1ff5d-112">The target site may return a "not found" (HTTP 404) error for a short period of time.</span></span>
- <span data-ttu-id="1ff5d-113">Obsah bude nutné znovu prohledat, aby se aktualizoval vyhledávací index.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-113">Content will need to be recrawled to update the search index.</span></span> <span data-ttu-id="1ff5d-114">Zde není nutné provádět žádný ruční krok, bude to provedeno automaticky.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-114">There is no manual step required here, this will be done automatically.</span></span>
- <span data-ttu-id="1ff5d-115">Cokoli, co je závislé na "statických" odkazech (například soubory synchronizace souborů a OneNote), bude nutné ručně opravit.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-115">Anything dependent on "static" links (such as File Sync and OneNote files) will need to be manually corrected.</span></span>
- <span data-ttu-id="1ff5d-116">Je možné, že weby projektového serveru budou muset být ověřeny, aby bylo zajištěno, že jsou stále správně spojeny.</span><span class="sxs-lookup"><span data-stu-id="1ff5d-116">Project Server sites may need to be validated to ensure that they are still associated correctly.</span></span> 
