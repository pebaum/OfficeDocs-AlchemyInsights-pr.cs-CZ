---
title: Vlastnosti ConsistencyGuid/Sourceukotvení
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: f0ff94a8e46f1fb4e0ac8653c51f8f651e29498b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36516967"
---
# <a name="consistencyguid--sourceanchor-behavior"></a>Vlastnosti ConsistencyGuid/Sourceukotvení

Azure AD Connect (verze 1.1.524.0 a After) nyní usnadňuje použití atributu msDS-ConsistencyGuid jako Sourcekotvu. Při použití této funkce Azure AD Connect automaticky konfiguruje pravidla synchronizace na:
  
- Jako atribut Sourcekotvy pro objekty User použijte identifikátor msDS-ConsistencyGuid. Objekt ObjectGUID se používá pro jiné typy objektů.
    
- Pro kterýkoli z objektů AD User, jehož atribut msDS-ConsistencyGuid není naplněn, program AD Connect zapíše svou hodnotu objectGUID zpět do atributu msDS-ConsistencyGuid v prostorách služby Active Directory. Po naplnění atributu msDS-ConsistencyGuid provede Azure AD Connect objekt na Azure AD.
    
 **Poznámka:** Jakmile je v místě importován objekt AD do Azure AD Connect (to znamená, importováno do prostoru konektoru AD Connector a promítaný do metaverse), již nelze změnit jeho hodnotu Sourcekotvu. Chcete-li určit hodnotu Sourcekotvu pro daný objekt AD, nakonfigurujte jeho atribut msDS-ConsistencyGuid před jeho importem do Azure AD Connect. 
  
Další informace o Sourcekotvy a ConsistencyGuid naleznete v následujících informacích: [Azure AD Connect: koncepce designu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)
  

