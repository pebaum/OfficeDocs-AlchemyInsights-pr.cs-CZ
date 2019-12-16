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
# <a name="save-site-or-list-as-a-template"></a>Uložení webu nebo seznamu jako šablony

Šablony webů služby SharePoint jsou předem sestavené definice navržené kolem konkrétní obchodní potřeby. Další informace naleznete v tématu [použití šablon k vytvoření různých druhů webů služby SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Zde jsou uvedeny některé běžné problémy a řešení týkající se uložení webu nebo seznamu jako šablony na webu služby SharePoint Online.

**Tlačítko Uložit šablonu webu/seznamu není k dispozici nebo nebylo nalezeno**. 

- Správci budou muset povolit vlastní skripty, aby umožnily funkce šablon. Podrobné pokyny, příklady a úvahy, viz [Povolení nebo zákaz vlastního skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


- Příkaz Uložit web jako šablonu není podporován a může způsobit problémy na webech, které používají infrastrukturu publikování serveru SharePoint Server.


**Šablonu webu nelze vytvořit nebo nepracuje správně.**

- V šabloně pravděpodobně chybí [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nelze ji aktivovat. Není-li funkce k dispozici pro aktivaci v aktuální kolekci webů, nelze k vytvoření webu použít šablonu webu.


- Zkontrolujte, zda některé seznamy nebo knihovny překročí mezní [hodnotu zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) pro 5000 položek, protože to může blokovat vytvoření šablony webu.


- Web pravděpodobně používá příliš mnoho prostředků, a proto šablona webu překračuje limit 50 megabajt (MB).


- Při zobrazování dat ze seznamu, který používá vyhledávací sloupec, nastaly problémy. Další informace naleznete v tématu [seznam generovaných šablon nezobrazuje data ze správného vyhledávacího seznamu ve službě SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).


Podrobnější informace o běžných problémech a řešeních naleznete v odkazech, [vytváření a používání šablon webů](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).

