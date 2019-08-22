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
ms.custom: ''
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: 5ac56fa78c66cf3b246bc0cc01f040e27310d629
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36526973"
---
# <a name="error-attributevaluemustbeunique"></a>Chyba: AttributeValueMustBeUnique

Nejčastější příčinou AttributeValueMustBeUnique chyba je, že dva objekty s různými SourceAnchor (immutableId) mají stejnou hodnotu pro atribut ProxyAddresses nebo UserPrincipalName. Oprava chyby AttributeValueMustBeUnique:
  
1. Identifikujte duplicitní proxyAddresses, userPrincipalName a další hodnotu atributu, který je příčinou chyby. Rovněž určete, které objekty dvou (nebo více) jsou zapojeny do konfliktu. Sestavy generované Azure AD připojit stavu synchronizace můžete určit dva objekty.
    
2. Určete, který objekt by měly i nadále mít duplicitní hodnoty a který objekt by neměly.
    
3. Odeberte duplicitní hodnoty z objektu, který by tuto hodnotu. Všimněte si, že by měl provést změnu v adresáři, kde je objekt pocházející z. V některých případech je třeba odstranit některé objekty v konfliktu.
    
4. Pokud jste provedli změny v prostorách na AD, Nechť Azure AD Connect synchronizovat změnu chyba vyřešen.
    

