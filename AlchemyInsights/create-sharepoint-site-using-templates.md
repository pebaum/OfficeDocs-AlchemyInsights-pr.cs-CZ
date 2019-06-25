---
title: Vytvoření webu v Online služby SharePoint
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: 9ab06cbd1648da31d8a04e61c237a2326b4bbe93
ms.sourcegitcommit: f856d46a325c517fc29d935c27f21b77c4219e66
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/24/2019
ms.locfileid: "35199266"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="3be69-102">Vytvořit weby služby SharePoint pomocí šablony</span><span class="sxs-lookup"><span data-stu-id="3be69-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="3be69-103">Šablony webu služby SharePoint jsou předem sestavené definice navrženo pro konkrétní obchodní potřeby.</span><span class="sxs-lookup"><span data-stu-id="3be69-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="3be69-104">Další informace naleznete v tématu [použití šablon k vytvoření různých typů webů služby SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="3be69-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="3be69-105">Zde jsou některé běžné problémy/řešení týkající se ukládání web nebo do seznamu jako šablony v Online služby Sharepoint.</span><span class="sxs-lookup"><span data-stu-id="3be69-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="3be69-106">**Tlačítko šablony uložit seznam webů nebo není k dispozici nebo chybí**</span><span class="sxs-lookup"><span data-stu-id="3be69-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="3be69-107">Správce bude nutné povolit vlastní skript funkcí šablony.</span><span class="sxs-lookup"><span data-stu-id="3be69-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="3be69-108">Podrobné kroky viz příklady a důležité informace</span><span class="sxs-lookup"><span data-stu-id="3be69-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="3be69-109">Povolit nebo zakázat vlastní skript</span><span class="sxs-lookup"><span data-stu-id="3be69-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="3be69-110">Uložit web jako šablonu příkaz není podporováno a může způsobit problémy na serverech, které používají Infrastruktura publikování serveru SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3be69-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="3be69-111">**Nelze vytvořit šablonu webu nebo nefunguje správně**</span><span class="sxs-lookup"><span data-stu-id="3be69-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="3be69-112">Šablony mohou být chybějící [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nebude aktivovat.</span><span class="sxs-lookup"><span data-stu-id="3be69-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="3be69-113">Pokud funkce není k dispozici v aktuální kolekci webů aktivovat, nelze použít šablonu webu vytvořit web.</span><span class="sxs-lookup"><span data-stu-id="3be69-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="3be69-114">Zkontrolujte, pokud všechny seznamy a knihovny překročit [Mezní hodnotu Limit zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 položek jako to může blokovat vytvoření šablony webu.</span><span class="sxs-lookup"><span data-stu-id="3be69-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="3be69-115">Web pravděpodobně používá příliš mnoho prostředků a proto šablony webu překračuje limit 50 MB.</span><span class="sxs-lookup"><span data-stu-id="3be69-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="3be69-116">Existují problémy se zobrazením dat ze seznamu, který používá vyhledávací sloupec.</span><span class="sxs-lookup"><span data-stu-id="3be69-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="3be69-117">Další informace naleznete v tématu [Generování šablony seznamu nezobrazuje data ze seznamu správnou vyhledávání v Online služby SharePoint](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span><span class="sxs-lookup"><span data-stu-id="3be69-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span></span>

<span data-ttu-id="3be69-118">Podrobnější informace týkající se běžných problémů a řešení zkontrolujte, zda [Při vytváření a používání šablon webů](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="3be69-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



