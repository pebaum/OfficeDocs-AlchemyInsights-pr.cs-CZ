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
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36526973"
---
# <a name="error-attributevaluemustbeunique"></a>Chyba: AttributeValueMustBeUnique

Nejběžnější příčinou chyby AttributeValueMustBeUnique jsou dva objekty s odlišnou hodnotou Sourcekotvu (immutableId), které mají stejnou hodnotu atributů ProxyAddresses a/nebo UserPrincipalName. Při opravě chyby AttributeValueMustBeUnique postupujte takto:
  
1. Identifikujte duplikované proxyAddresses, userPrincipalName nebo jinou hodnotu atributu, která způsobuje chybu. Identifikujte také, které dva (nebo více) objekty jsou do konfliktu zapojeny. Sestava vytvořená pomocí Azure stavu připojení pro synchronizaci vám pomůže identifikovat tyto dva objekty.
    
2. Určete, který objekt by měl i nadále mít duplikátní hodnotu a který objekt by neměl být.
    
3. Odeberte duplikátní hodnotu z objektu, který by neměl mít tuto hodnotu. Nezapomeňte provést změnu v adresáři, ze kterého je objekt odvozen. V některých případech může být nutné odstranit některý z objektů v konfliktu.
    
4. Pokud jste provedli změnu v prostorách služby AD, nechť Azure AD Connect provede synchronizaci změny, aby se chyba vyřeší.
    

