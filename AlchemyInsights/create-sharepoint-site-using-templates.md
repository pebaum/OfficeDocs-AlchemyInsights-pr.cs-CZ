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
# <a name="create-sharepoint-sites-using-templates"></a>Vytvořit weby služby SharePoint pomocí šablony

Šablony webu služby SharePoint jsou předem sestavené definice navrženo pro konkrétní obchodní potřeby. Další informace naleznete v tématu [použití šablon k vytvoření různých typů webů služby SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).

Zde jsou některé běžné problémy/řešení týkající se ukládání web nebo do seznamu jako šablony v Online služby Sharepoint. 

**Tlačítko šablony uložit seznam webů nebo není k dispozici nebo chybí**

Správce bude nutné povolit vlastní skript funkcí šablony. Podrobné kroky viz příklady a důležité informace 

- [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- Uložit web jako šablonu příkaz není podporováno a může způsobit problémy na serverech, které používají Infrastruktura publikování serveru SharePoint.

**Nelze vytvořit šablonu webu nebo nefunguje správně**

Šablony mohou být chybějící [funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nebude aktivovat. Pokud funkce není k dispozici v aktuální kolekci webů aktivovat, nelze použít šablonu webu vytvořit web.

- Zkontrolujte, pokud všechny seznamy a knihovny překročit [Mezní hodnotu Limit zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 položek jako to může blokovat vytvoření šablony webu.

- Web pravděpodobně používá příliš mnoho prostředků a proto šablony webu překračuje limit 50 MB.


- Existují problémy se zobrazením dat ze seznamu, který používá vyhledávací sloupec. Další informace naleznete v tématu [Generování šablony seznamu nezobrazuje data ze seznamu správnou vyhledávání v Online služby SharePoint](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).

Podrobnější informace týkající se běžných problémů a řešení zkontrolujte, zda [Při vytváření a používání šablon webů](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).



