---
title: Obsah se nezobrazí ve výsledcích vyhledávání služby SharePoint
ms.author: tlarsen
author: tklarsen
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: 8215b0a5cde5adffa3bec37d6699418557f914dd
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35363793"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a>Obsah se nezobrazí ve výsledcích vyhledávání služby SharePoint

Postupujte při očekávaný obsah se nezobrazí ve výsledcích hledání:
  
1. Zkontrolujte, zda je **Web** , který obsahuje očekávaný obsah nastaven povolit obsah zobrazit ve výsledcích hledání. Postupujte podle kroků v [zobrazení obsahu na webu ve výsledcích hledání](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).

2. Zkontrolujte nastavení **seznamu** nebo **knihovny** , která obsahuje očekávaný obsah povolit obsah zobrazit ve výsledcích hledání. Postupujte podle kroků [Zobrazit obsah ze seznamů nebo knihoven ve výsledcích hledání](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).

3. Ověřte, že stránka, dokument nebo vlastní stránky rozložení je publikován jako **hlavní verze.** Podle pokynů v kroku 3 v [hledání nevrací všechny výsledky v Online služby SharePoint](https://go.microsoft.com/fwlink/?linkid=874525).

4. Ověřte, zda má uživatel **oprávnění** k zobrazení obsahu. Postupujte podle kroků v [Princip úrovně oprávnění ve službě SharePoint](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels).
    
5. Došlo ke změně schématu vyhledávání přidáním nové spravované vlastnosti, spravované vlastnosti úpravou nebo odstraněním spravované vlastnosti pak požaduje procházení a indexování znovu provést. **Novou indexaci** obsahu podle kroků v [požadovat ruční prohledávání a indexování znovu serveru, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-content). To může chvíli trvat, počkejte 24 hodin před další kontrolou výsledků.

Další informace naleznete v tématu [Povolení obsahu na webu, abyste je mohli prohledávat](https://docs.microsoft.com/sharepoint/make-site-content-searchable). 
  
