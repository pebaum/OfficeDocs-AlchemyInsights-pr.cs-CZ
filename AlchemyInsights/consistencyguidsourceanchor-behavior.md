---
title: ConsistencyGuid / sourceAnchor chování
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: 8527e7c2404742a999041f85ed12d78c48cc0d8c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705726"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>ConsistencyGuid / sourceAnchor chování

Azure AD Connect (verze 1.1.524.0 a po) nyní usnadňuje použití atributu msDS-ConsistencyGuid jako sourceAnchor. Při použití této funkce Azure AD Connect automaticky nakonfiguruje pravidla synchronizace takto:
  
- Použijte msDS-ConsistencyGuid jako sourceAnchor atribut pro objekty User. ObjectGUID se používá pro jiné typy objektů.
    
- Pro všechny dané místní objekt uživatele služby AD, jehož atribut msDS-ConsistencyGuid není naplněn, Azure AD Connect zapíše jeho hodnotu objectGUID zpět do atributu msDS-ConsistencyGuid v místním adresáři Active Directory. Po naplnění atributu msDS-ConsistencyGuid azure ad připojit pak exportuje objekt do Služby Azure AD.
    
 **Poznámka:** Jakmile je místní objekt AD importován do služby Azure AD Connect (to znamená, že se importuje do prostoru konektoru a promítne se do Metaverse), už nelze změnit jeho hodnotu sourceAnchor. Chcete-li určit hodnotu sourceAnchor pro daný místní objekt Služby AD, nakonfigurujte jeho atribut msDS-ConsistencyGuid před importem do služby Azure AD Connect. 
  
Další informace o SourceAnchor a ConsistencyGuid, najdete v následujících: [Azure AD Connect: Koncepty návrhu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

