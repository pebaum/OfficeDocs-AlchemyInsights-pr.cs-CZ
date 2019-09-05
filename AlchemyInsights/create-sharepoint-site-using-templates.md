---
title: Vytvoření webu ve službě SharePoint Online
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 42430c8dadc17b87dc7741f3fa045ba7c25fab84
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36755301"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="fc66f-102">Vytvoření webů služby SharePoint pomocí šablon</span><span class="sxs-lookup"><span data-stu-id="fc66f-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="fc66f-103">Šablony webů služby SharePoint jsou předem sestavené definice navržené kolem konkrétní obchodní potřeby.</span><span class="sxs-lookup"><span data-stu-id="fc66f-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="fc66f-104">Další informace naleznete v tématu [použití šablon k vytvoření různých druhů webů služby SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="fc66f-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="fc66f-105">Zde jsou uvedeny některé běžné problémy a řešení týkající se uložení webu nebo seznamu jako šablony ve službě SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="fc66f-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="fc66f-106">**Tlačítko Uložit šablonu webu/seznamu není k dispozici nebo chybí**</span><span class="sxs-lookup"><span data-stu-id="fc66f-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="fc66f-107">Správci budou muset povolit vlastní skripty, aby umožnily funkce šablon.</span><span class="sxs-lookup"><span data-stu-id="fc66f-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="fc66f-108">Podrobné kroky, příklady a úvahy naleznete v tématu</span><span class="sxs-lookup"><span data-stu-id="fc66f-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="fc66f-109">Povolení nebo zákaz vlastního skriptu</span><span class="sxs-lookup"><span data-stu-id="fc66f-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="fc66f-110">Příkaz Uložit web jako šablonu není podporován a může způsobit problémy na webech, které používají infrastrukturu publikování serveru SharePoint Server.</span><span class="sxs-lookup"><span data-stu-id="fc66f-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="fc66f-111">**Šablonu webu nelze vytvořit nebo nepracuje správně.**</span><span class="sxs-lookup"><span data-stu-id="fc66f-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="fc66f-112">V šabloně pravděpodobně chybí [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nelze ji aktivovat.</span><span class="sxs-lookup"><span data-stu-id="fc66f-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="fc66f-113">Není-li funkce k dispozici pro aktivaci v aktuální kolekci webů, nelze k vytvoření webu použít šablonu webu.</span><span class="sxs-lookup"><span data-stu-id="fc66f-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="fc66f-114">Zkontrolujte, zda některé seznamy nebo knihovny překročí mezní [hodnotu zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) pro 5000 položek, protože to může blokovat vytvoření šablony webu.</span><span class="sxs-lookup"><span data-stu-id="fc66f-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="fc66f-115">Web pravděpodobně používá příliš mnoho prostředků, a proto šablona webu překračuje limit 50 MB.</span><span class="sxs-lookup"><span data-stu-id="fc66f-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="fc66f-116">Při zobrazování dat ze seznamu, který používá vyhledávací sloupec, nastaly problémy.</span><span class="sxs-lookup"><span data-stu-id="fc66f-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="fc66f-117">Další informace naleznete v tématu [seznam generovaných šablon nezobrazuje data ze správného vyhledávacího seznamu ve službě SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="fc66f-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>

<span data-ttu-id="fc66f-118">Podrobnější informace o běžných problémech a řešeních naleznete v [šabloně webu pro vytváření a používání](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="fc66f-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



