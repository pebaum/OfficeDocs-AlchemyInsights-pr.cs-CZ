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
# <a name="create-sharepoint-sites-using-templates"></a>Vytváření sharepointových webů pomocí šablon

Možnost uložení webu jako šablony není podporována pomocí moderní komunikace nebo týmových webů. Další informace o používání šablon najdete v [tématu Uložení, stažení a nahrání sharepointového webu jako šablony](https://docs.microsoft.com/sharepoint/dev/general-development/save-download-and-upload-a-sharepoint-site-as-a-template).

Zde jsou některé běžné problémy /řešení týkající se ukládání webu nebo seznamu jako šablony v Sharepointu Online. 

**Tlačítko Uložit šablonu webu/seznamu není k dispozici nebo chybí**

Správci budou muset povolit vlastní skript, aby mohli funkce šablony povolit. Podrobné kroky, příklady a důležité informace naleznete v tématu 

- [Povolení nebo zabránění vlastnímu skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- Příkaz Uložit web jako šablonu není podporován a může způsobit problémy na webech, které používají infrastrukturu publikování sharepointového serveru.

**Šablonu webu nelze vytvořit nebo nefunguje správně.**

V šabloně pravděpodobně [chybí funkce](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) a nebude se aktivovat. Pokud tato funkce není k dispozici pro aktivaci v aktuální kolekci webů, nelze k vytvoření webu použít šablonu webu.

- Zkontrolujte, zda některé seznamy nebo knihovny nepřekračují [prahovou hodnotu limitu zobrazení seznamu](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) 5000 položek, protože to může blokovat vytvoření šablony webu.

- Web může používat příliš mnoho prostředků, a proto šablona webu překračuje limit 50 MB.


- Při zobrazování dat ze seznamu, který používá vyhledávací sloupec, dochází k potížím. Další informace naleznete v [tématu Seznam generovaný šablonou nezobrazuje data ze správného vyhledávacího seznamu v SharePointu Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).

Podrobnější informace o běžných problémech a řešeních naleznete v tématu [Vytvořit a používat šablony webů](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).



