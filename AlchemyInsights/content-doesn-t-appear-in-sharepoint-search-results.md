---
title: Obsah se ve výsledcích sharepointového vyhledávání nezobrazuje
ms.author: tlarsen
author: tklarsen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: a21e0047b41390f740f9e13d31cba32b13990151
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705654"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a>Obsah se ve výsledcích sharepointového vyhledávání nezobrazuje

Pokud se očekávaný obsah nezobrazuje ve výsledcích hledání, postupujte podle těchto kroků řešení potíží:
  
1. Zkontrolujte, zda je **web,** který obsahuje očekávaný obsah, nastaven tak, aby se obsah zobrazoval ve výsledcích hledání. Postupujte podle pokynů v části [Zobrazit obsah na webu ve výsledcích vyhledávání](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).

2. Zkontrolujte, zda je **seznam** nebo **knihovna** obsahující očekávaný obsah nastavena tak, aby se obsah zobrazoval ve výsledcích hledání. Postupujte podle pokynů v části [Zobrazit obsah ze seznamů nebo knihoven ve výsledcích hledání](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).

3. Ověřte, zda je rozložení stránky, dokumentu nebo vlastní stránky publikováno jako **hlavní verze.** Podle kroku 3 ve [Vyhledávání nevracívšechny výsledky v SharePointu Online](https://go.microsoft.com/fwlink/?linkid=874525).

4. Ověřte, zda má uživatel **oprávnění** k zobrazení obsahu. Postupujte podle pokynů v [části Principy úrovní oprávnění v SharePointu](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
    
5. Pokud bylo schéma hledání změněno přidáním nové spravované vlastnosti, úpravou spravované vlastnosti nebo odebráním spravované vlastnosti, bude vyžadovánpožadavek na procházení a přeindexování. **Obsah můžete znovu indexovat** podle kroků uvedených v části [Ruční vyžádání procházení a přeindexování webu, knihovny nebo seznamu](https://docs.microsoft.com/sharepoint/crawl-site-content). To může chvíli trvat, počkejte 24 hodin, než znovu zkontrolujete výsledky.

Další informace naleznete v [tématu Povolení vyhledávání obsahu na webu](https://docs.microsoft.com/sharepoint/make-site-content-searchable). 
  
