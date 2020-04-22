---
title: Chyba AttributeValueMustBeUnique
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
ms.assetid: bf8ac830-6f0c-4616-827d-987616700e59
ms.openlocfilehash: fa1fdb35f1af250bc98aa61c0e5111f1f1b8aac4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703167"
---
# <a name="error-attributevaluemustbeunique"></a>Chyba: AttributeValueMustBeUnique

Nejběžnější důvod pro AttributeValueMustMustUnique chyba je dva objekty s různými SourceAnchor (imemtableId) mají stejnou hodnotu pro ProxyAddresses a/nebo UserPrincipalName atributy. Chcete-li opravit chybu AttributeValueMustMustMustUnique:
  
1. Identifikujte duplicitní proxyAdresy, userPrincipalName nebo jinou hodnotu atributu, která chybu způsobuje. Také určit, které dva (nebo více) objekty jsou zapojeny do konfliktu. Sestava generovaná službou Azure AD Connect Health pro synchronizaci vám může pomoci identifikovat dva objekty.
    
2. Určete, který objekt by měl mít duplicitní hodnotu a který objekt by neměl.
    
3. Odeberte duplicitní hodnotu z objektu, který by neměl mít tuto hodnotu. Všimněte si, že byste měli provést změnu v adresáři, odkud je objekt pochází. V některých případech může být nutné odstranit jeden z objektů v konfliktu.
    
4. Pokud jste provedli změnu v místní službě AD, nechte Azure AD Connect synchronizovat změnu, aby se chyba opravila.
    

