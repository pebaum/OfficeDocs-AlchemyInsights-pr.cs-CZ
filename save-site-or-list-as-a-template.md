---
title: Uložit jako šablonu webu nebo seznamu
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 7930551c0938501d006f791491594f9d6d9ba260
ms.sourcegitcommit: 56c52c73e752414d66785f175c3a0e2925ad41c1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/02/2019
ms.locfileid: "31043998"
---
# <a name="save-site-or-list-as-a-template"></a><span data-ttu-id="d0964-102">Uložit jako šablonu webu nebo seznamu</span><span class="sxs-lookup"><span data-stu-id="d0964-102">Save site or list as a template</span></span>

<span data-ttu-id="d0964-103">Šablony webu služby SharePoint jsou předem sestavené definice navrženo pro konkrétní obchodní potřeby.</span><span class="sxs-lookup"><span data-stu-id="d0964-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="d0964-104">Další informace naleznete v tématu [použití šablon k vytvoření různých typů webů služby SharePoint](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="d0964-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="d0964-105">Zde jsou některé běžné problémy/řešení týkající se ukládání web nebo do seznamu jako šablony v Online služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="d0964-105">Here are some common issues/solutions regarding Saving a Site or List as a template in SharePoint Online.</span></span>

<span data-ttu-id="d0964-106">**Uložení webu nebo seznamu je tlačítko šablony není k dispozici nebo chybí**.</span><span class="sxs-lookup"><span data-stu-id="d0964-106">**Save site/list template button is not available or missing**.</span></span> 

- <span data-ttu-id="d0964-107">Správce bude nutné povolit vlastní skript funkcí šablony.</span><span class="sxs-lookup"><span data-stu-id="d0964-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="d0964-108">Podrobné kroky, příklady a důležité informace naleznete v [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="d0964-108">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).</span></span>


- <span data-ttu-id="d0964-109">Uložit web jako šablonu příkaz není podporováno a může způsobit problémy na serverech, které používají Infrastruktura publikování serveru SharePoint.</span><span class="sxs-lookup"><span data-stu-id="d0964-109">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>


**<span data-ttu-id="d0964-110">Nelze vytvořit šablonu webu nebo nefunguje správně</span><span class="sxs-lookup"><span data-stu-id="d0964-110">The site template cannot be created or does not work correctly</span></span>**

- <span data-ttu-id="d0964-111">Šablony mohou být chybějící [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nebude aktivovat.</span><span class="sxs-lookup"><span data-stu-id="d0964-111">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won’t activate.</span></span> <span data-ttu-id="d0964-112">Pokud funkce není k dispozici v aktuální kolekci webů aktivovat, nelze použít šablonu webu vytvořit web.</span><span class="sxs-lookup"><span data-stu-id="d0964-112">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>


- <span data-ttu-id="d0964-113">Zkontrolujte, pokud všechny seznamy a knihovny překročit [Mezní hodnotu Limit zobrazení seznamu](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 položek jako to může blokovat vytvoření šablony webu.</span><span class="sxs-lookup"><span data-stu-id="d0964-113">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>


- <span data-ttu-id="d0964-114">Web pravděpodobně používá příliš mnoho prostředků a proto šablony webu překračuje limit 50 megabajtů (MB).</span><span class="sxs-lookup"><span data-stu-id="d0964-114">The site may be using too many resources and therefore the site template exceeds the 50 megabyte (MB) limit.</span></span>


- <span data-ttu-id="d0964-115">Existují problémy se zobrazením dat ze seznamu, který používá vyhledávací sloupec.</span><span class="sxs-lookup"><span data-stu-id="d0964-115">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="d0964-116">Další informace naleznete v tématu [Generování šablony seznamu nezobrazuje data ze seznamu správnou vyhledávání v Online služby SharePoint](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span><span class="sxs-lookup"><span data-stu-id="d0964-116">For more information, see [Template-generated list doesn’t display data from the correct lookup list in SharePoint Online](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span></span>


<span data-ttu-id="d0964-117">Podrobnější informace týkající se běžných problémů a řešení prosím odkaz, [Vytvoření a použití šablon webů](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="d0964-117">For more detailed information on common problems and solutions please reference, [Create and use site templates](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>

