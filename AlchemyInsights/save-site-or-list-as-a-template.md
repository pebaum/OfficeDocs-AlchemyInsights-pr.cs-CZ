---
title: Uložení webu nebo seznamu jako šablony
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 627f49991aaef984f731412045351d7a1862b376
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048717"
---
# <a name="save-site-or-list-as-a-template"></a><span data-ttu-id="e21d5-102">Uložení webu nebo seznamu jako šablony</span><span class="sxs-lookup"><span data-stu-id="e21d5-102">Save site or list as a template</span></span>

<span data-ttu-id="e21d5-103">Šablony webů služby SharePoint jsou předem sestavené definice navržené kolem konkrétní obchodní potřeby.</span><span class="sxs-lookup"><span data-stu-id="e21d5-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="e21d5-104">Další informace naleznete v tématu [použití šablon k vytvoření různých druhů webů služby SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="e21d5-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="e21d5-105">Zde jsou uvedeny některé běžné problémy a řešení týkající se uložení webu nebo seznamu jako šablony na webu služby SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e21d5-105">Here are some common issues/solutions regarding Saving a Site or List as a template in SharePoint Online.</span></span>

<span data-ttu-id="e21d5-106">**Tlačítko Uložit šablonu webu/seznamu není k dispozici nebo nebylo nalezeno**.</span><span class="sxs-lookup"><span data-stu-id="e21d5-106">**Save site/list template button is not available or missing**.</span></span> 

- <span data-ttu-id="e21d5-107">Správci budou muset povolit vlastní skripty, aby umožnily funkce šablon.</span><span class="sxs-lookup"><span data-stu-id="e21d5-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="e21d5-108">Podrobné pokyny, příklady a úvahy, viz [Povolení nebo zákaz vlastního skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="e21d5-108">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


- <span data-ttu-id="e21d5-109">Příkaz Uložit web jako šablonu není podporován a může způsobit problémy na webech, které používají infrastrukturu publikování serveru SharePoint Server.</span><span class="sxs-lookup"><span data-stu-id="e21d5-109">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>


<span data-ttu-id="e21d5-110">**Šablonu webu nelze vytvořit nebo nepracuje správně.**</span><span class="sxs-lookup"><span data-stu-id="e21d5-110">**The site template cannot be created or does not work correctly**</span></span>

- <span data-ttu-id="e21d5-111">V šabloně pravděpodobně chybí [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nelze ji aktivovat.</span><span class="sxs-lookup"><span data-stu-id="e21d5-111">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won’t activate.</span></span> <span data-ttu-id="e21d5-112">Není-li funkce k dispozici pro aktivaci v aktuální kolekci webů, nelze k vytvoření webu použít šablonu webu.</span><span class="sxs-lookup"><span data-stu-id="e21d5-112">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>


- <span data-ttu-id="e21d5-113">Zkontrolujte, zda některé seznamy nebo knihovny překročí mezní [hodnotu zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) pro 5000 položek, protože to může blokovat vytvoření šablony webu.</span><span class="sxs-lookup"><span data-stu-id="e21d5-113">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>


- <span data-ttu-id="e21d5-114">Web pravděpodobně používá příliš mnoho prostředků, a proto šablona webu překračuje limit 50 megabajt (MB).</span><span class="sxs-lookup"><span data-stu-id="e21d5-114">The site may be using too many resources and therefore the site template exceeds the 50 megabyte (MB) limit.</span></span>


- <span data-ttu-id="e21d5-115">Při zobrazování dat ze seznamu, který používá vyhledávací sloupec, nastaly problémy.</span><span class="sxs-lookup"><span data-stu-id="e21d5-115">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="e21d5-116">Další informace naleznete v tématu [seznam generovaných šablon nezobrazuje data ze správného vyhledávacího seznamu ve službě SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="e21d5-116">For more information, see [Template-generated list doesn’t display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>


<span data-ttu-id="e21d5-117">Podrobnější informace o běžných problémech a řešeních naleznete v odkazech, [vytváření a používání šablon webů](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="e21d5-117">For more detailed information on common problems and solutions please reference, [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>

