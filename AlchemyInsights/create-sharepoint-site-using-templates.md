---
title: Vytvoření webu v SharePointu Online
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: b9009fdbdc2a5e7443151446daade1685d2f5d45
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770416"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="f4694-102">Vytváření sharepointových webů pomocí šablon</span><span class="sxs-lookup"><span data-stu-id="f4694-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="f4694-103">Možnost uložení webu jako šablony není podporována pomocí moderní komunikace nebo týmových webů.</span><span class="sxs-lookup"><span data-stu-id="f4694-103">The ability to save a site as a template is not supported with modern Communication or Team Sites.</span></span> <span data-ttu-id="f4694-104">Další informace o používání šablon najdete v [tématu Uložení, stažení a nahrání sharepointového webu jako šablony](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).</span><span class="sxs-lookup"><span data-stu-id="f4694-104">For more information about using templates see [Save, download and upload a SharePoint site as a template](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).</span></span>

<span data-ttu-id="f4694-105">Zde jsou některé běžné problémy /řešení týkající se ukládání webu nebo seznamu jako šablony v Sharepointu Online.</span><span class="sxs-lookup"><span data-stu-id="f4694-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="f4694-106">**Tlačítko Uložit šablonu webu/seznamu není k dispozici nebo chybí**</span><span class="sxs-lookup"><span data-stu-id="f4694-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="f4694-107">Správci budou muset povolit vlastní skript, aby mohli funkce šablony povolit.</span><span class="sxs-lookup"><span data-stu-id="f4694-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="f4694-108">Podrobné kroky, příklady a důležité informace naleznete v tématu</span><span class="sxs-lookup"><span data-stu-id="f4694-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="f4694-109">Povolení nebo zabránění vlastnímu skriptu</span><span class="sxs-lookup"><span data-stu-id="f4694-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="f4694-110">Příkaz Uložit web jako šablonu není podporován a může způsobit problémy na webech, které používají infrastrukturu publikování sharepointového serveru.</span><span class="sxs-lookup"><span data-stu-id="f4694-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="f4694-111">**Šablonu webu nelze vytvořit nebo nefunguje správně.**</span><span class="sxs-lookup"><span data-stu-id="f4694-111">**The site template cannot be created or does not work correctly**</span></span>

<span data-ttu-id="f4694-112">V šabloně pravděpodobně [chybí funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nebude se aktivovat.</span><span class="sxs-lookup"><span data-stu-id="f4694-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="f4694-113">Pokud tato funkce není k dispozici pro aktivaci v aktuální kolekci webů, nelze k vytvoření webu použít šablonu webu.</span><span class="sxs-lookup"><span data-stu-id="f4694-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="f4694-114">Zkontrolujte, zda některé seznamy nebo knihovny nepřekračují [prahovou hodnotu limitu zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 položek, protože to může blokovat vytvoření šablony webu.</span><span class="sxs-lookup"><span data-stu-id="f4694-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="f4694-115">Web může používat příliš mnoho prostředků, a proto šablona webu překračuje limit 50 MB.</span><span class="sxs-lookup"><span data-stu-id="f4694-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="f4694-116">Při zobrazování dat ze seznamu, který používá vyhledávací sloupec, dochází k potížím.</span><span class="sxs-lookup"><span data-stu-id="f4694-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="f4694-117">Další informace naleznete v [tématu Seznam generovaný šablonou nezobrazuje data ze správného vyhledávacího seznamu v SharePointu Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span><span class="sxs-lookup"><span data-stu-id="f4694-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>

<span data-ttu-id="f4694-118">Podrobnější informace o běžných problémech a řešeních naleznete v tématu [Vytvořit a používat šablony webů](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="f4694-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>



