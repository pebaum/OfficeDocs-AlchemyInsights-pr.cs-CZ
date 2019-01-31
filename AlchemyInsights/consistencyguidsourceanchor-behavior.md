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
ms.openlocfilehash: 010474bcc4cc6f97bcaafef9dfe6f4accfed4247
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/30/2019
ms.locfileid: "29659584"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid / sourceAnchor chování

Azure AD připojit (verze 1.1.524.0 a po) nyní usnadňuje použití jako sourceAnchor atribut msDS-ConsistencyGuid. Při použití této funkce, Azure AD připojit automaticky konfiguruje pravidla synchronizace:
  
- MsDS-ConsistencyGuid používejte jako atribut sourceAnchor pro objekty uživatelů. Pro ostatní typy objektů se používá atributu ObjectGUID.
    
- Pro všechny uvedené místního Active Directory objekt, jehož atribut msDS-ConsistencyGuid není vyplněné, Azure AD připojit zapíše zpět jeho hodnotu atributu objectGUID atribut msDS-ConsistencyGuid v místní službě Active Directory. Po naplnění je atribut msDS-ConsistencyGuid, Azure AD připojit exportuje objekt k Azure AD.
    
 **Poznámka:** Jednou místního objektu AD importu do Azure AD připojit (který je importován do prostoru spojnice AD a promítnuta do Metaverse), již nelze změnit jeho hodnotu sourceAnchor. Zadání hodnoty sourceAnchor uveden v prostorách AD objekt, nastavit jeho atribut msDS-ConsistencyGuid před jeho importu do Azure AD připojit. 
  
Další informace o SourceAnchor a ConsistencyGuid, naleznete na následující: [Azure AD připojit: návrh koncepce](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

