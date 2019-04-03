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
# <a name="save-site-or-list-as-a-template"></a>Uložit jako šablonu webu nebo seznamu

Šablony webu služby SharePoint jsou předem sestavené definice navrženo pro konkrétní obchodní potřeby. Další informace naleznete v tématu [použití šablon k vytvoření různých typů webů služby SharePoint](https://support.office.com/en-us/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Zde jsou některé běžné problémy/řešení týkající se ukládání web nebo do seznamu jako šablony v Online služby SharePoint.

**Uložení webu nebo seznamu je tlačítko šablony není k dispozici nebo chybí**. 

- Správce bude nutné povolit vlastní skript funkcí šablony. Podrobné kroky, příklady a důležité informace naleznete v [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).


- Uložit web jako šablonu příkaz není podporováno a může způsobit problémy na serverech, které používají Infrastruktura publikování serveru SharePoint.


**Nelze vytvořit šablonu webu nebo nefunguje správně**

- Šablony mohou být chybějící [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nebude aktivovat. Pokud funkce není k dispozici v aktuální kolekci webů aktivovat, nelze použít šablonu webu vytvořit web.


- Zkontrolujte, pokud všechny seznamy a knihovny překročit [Mezní hodnotu Limit zobrazení seznamu](https://support.office.com/en-us/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 položek jako to může blokovat vytvoření šablony webu.


- Web pravděpodobně používá příliš mnoho prostředků a proto šablony webu překračuje limit 50 megabajtů (MB).


- Existují problémy se zobrazením dat ze seznamu, který používá vyhledávací sloupec. Další informace naleznete v tématu [Generování šablony seznamu nezobrazuje data ze seznamu správnou vyhledávání v Online služby SharePoint](https://support.office.com/en-us/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).


Podrobnější informace týkající se běžných problémů a řešení prosím odkaz, [Vytvoření a použití šablon webů](https://support.office.com/en-us/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).

