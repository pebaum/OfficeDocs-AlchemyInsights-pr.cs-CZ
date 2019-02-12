---
title: Chyba AttributeValueMustBeUnique
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 7b98b68fabff6c048f1bab6cf506355114d18658
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916517"
---
# <a name="error-attributevaluemustbeunique"></a>Chyba: AttributeValueMustBeUnique

Nejčastější příčinou AttributeValueMustBeUnique chyba je, že dva objekty s různými SourceAnchor (immutableId) mají stejnou hodnotu pro atribut ProxyAddresses nebo UserPrincipalName. Oprava chyby AttributeValueMustBeUnique:
  
1. Identifikujte duplicitní proxyAddresses, userPrincipalName a další hodnotu atributu, který je příčinou chyby. Rovněž určete, které objekty dvou (nebo více) jsou zapojeny do konfliktu. Sestavy generované Azure AD připojit stavu synchronizace můžete určit dva objekty.
    
2. Určete, který objekt by měly i nadále mít duplicitní hodnoty a který objekt by neměly.
    
3. Odeberte duplicitní hodnoty z objektu, který by tuto hodnotu. Všimněte si, že by měl provést změnu v adresáři, kde je objekt pocházející z. V některých případech je třeba odstranit některé objekty v konfliktu.
    
4. Pokud jste provedli změny v prostorách na AD, Nechť Azure AD Connect synchronizovat změnu chyba vyřešen.
    

