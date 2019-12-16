---
title: Vytvoření webu ve službě SharePoint Online
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
ms.openlocfilehash: 458990889d3c074820527982cbfa6e2d198d3e66
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052462"
---
# <a name="create-sharepoint-sites-using-templates"></a>Vytvoření webů služby SharePoint pomocí šablon

Šablony webů služby SharePoint jsou předem sestavené definice navržené kolem konkrétní obchodní potřeby. Další informace naleznete v tématu [použití šablon k vytvoření různých druhů webů služby SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Zde jsou uvedeny některé běžné problémy a řešení týkající se uložení webu nebo seznamu jako šablony ve službě SharePoint Online. 

**Tlačítko Uložit šablonu webu/seznamu není k dispozici nebo chybí**

Správci budou muset povolit vlastní skripty, aby umožnily funkce šablon. Podrobné kroky, příklady a úvahy naleznete v tématu 

- [Povolení nebo zákaz vlastního skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- Příkaz Uložit web jako šablonu není podporován a může způsobit problémy na webech, které používají infrastrukturu publikování serveru SharePoint Server.

**Šablonu webu nelze vytvořit nebo nepracuje správně.**

V šabloně pravděpodobně chybí [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nelze ji aktivovat. Není-li funkce k dispozici pro aktivaci v aktuální kolekci webů, nelze k vytvoření webu použít šablonu webu.

- Zkontrolujte, zda některé seznamy nebo knihovny překročí mezní [hodnotu zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) pro 5000 položek, protože to může blokovat vytvoření šablony webu.

- Web pravděpodobně používá příliš mnoho prostředků, a proto šablona webu překračuje limit 50 MB.


- Při zobrazování dat ze seznamu, který používá vyhledávací sloupec, nastaly problémy. Další informace naleznete v tématu [seznam generovaných šablon nezobrazuje data ze správného vyhledávacího seznamu ve službě SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).

Podrobnější informace o běžných problémech a řešeních naleznete v [šabloně webu pro vytváření a používání](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).



