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
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29498511"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="2c696-102">ConsistencyGuid / sourceAnchor chování</span><span class="sxs-lookup"><span data-stu-id="2c696-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="2c696-p101">Azure AD připojit (verze 1.1.524.0 a po) nyní usnadňuje použití jako sourceAnchor atribut msDS-ConsistencyGuid. Při použití této funkce, Azure AD připojit automaticky konfiguruje pravidla synchronizace:</span><span class="sxs-lookup"><span data-stu-id="2c696-p101">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute. When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="2c696-p102">MsDS-ConsistencyGuid používejte jako atribut sourceAnchor pro objekty uživatelů. Pro ostatní typy objektů se používá atributu ObjectGUID.</span><span class="sxs-lookup"><span data-stu-id="2c696-p102">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects. ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="2c696-p103">Pro všechny uvedené místního Active Directory objekt, jehož atribut msDS-ConsistencyGuid není vyplněné, Azure AD připojit zapíše zpět jeho hodnotu atributu objectGUID atribut msDS-ConsistencyGuid v místní službě Active Directory. Po naplnění je atribut msDS-ConsistencyGuid, Azure AD připojit exportuje objekt k Azure AD.</span><span class="sxs-lookup"><span data-stu-id="2c696-p103">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory. After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="2c696-p104">**Poznámka:** Jednou místního objektu AD importu do Azure AD připojit (který je importován do prostoru spojnice AD a promítnuta do Metaverse), již nelze změnit jeho hodnotu sourceAnchor. Zadání hodnoty sourceAnchor uveden v prostorách AD objekt, nastavit jeho atribut msDS-ConsistencyGuid před jeho importu do Azure AD připojit.</span><span class="sxs-lookup"><span data-stu-id="2c696-p104">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore. To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="2c696-111">Další informace o SourceAnchor a ConsistencyGuid, naleznete na následující: [Azure AD připojit: návrh koncepce](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="2c696-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

