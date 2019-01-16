---
title: ConsistencyGuid / sourceAnchor chování
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 80516ed9e15040475a8b65a1af98a1b561704d49
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281235"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid / sourceAnchor chování

Azure AD připojit (verze 1.1.524.0 a po) nyní usnadňuje použití jako sourceAnchor atribut msDS-ConsistencyGuid. Při použití této funkce, Azure AD připojit automaticky konfiguruje pravidla synchronizace:
  
- MsDS-ConsistencyGuid používejte jako atribut sourceAnchor pro objekty uživatelů. Pro ostatní typy objektů se používá atributu ObjectGUID.
    
- Pro všechny uvedené místního Active Directory objekt, jehož atribut msDS-ConsistencyGuid není vyplněné, Azure AD připojit zapíše zpět jeho hodnotu atributu objectGUID atribut msDS-ConsistencyGuid v místní službě Active Directory. Po naplnění je atribut msDS-ConsistencyGuid, Azure AD připojit exportuje objekt k Azure AD.
    
 **Poznámka:** Jednou místního objektu AD importu do Azure AD připojit (který je importován do prostoru spojnice AD a promítnuta do Metaverse), již nelze změnit jeho hodnotu sourceAnchor. Zadání hodnoty sourceAnchor uveden v prostorách AD objekt, nastavit jeho atribut msDS-ConsistencyGuid před jeho importu do Azure AD připojit. 
  
Další informace o SourceAnchor a ConsistencyGuid, naleznete na následující: [Azure AD připojit: návrh koncepce](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

