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
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="9bba6-102">ConsistencyGuid / sourceAnchor chování</span><span class="sxs-lookup"><span data-stu-id="9bba6-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="9bba6-103">Azure AD Connect (verze 1.1.524.0 a po) nyní usnadňuje použití atributu msDS-ConsistencyGuid jako sourceAnchor.</span><span class="sxs-lookup"><span data-stu-id="9bba6-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="9bba6-104">Při použití této funkce Azure AD Connect automaticky nakonfiguruje pravidla synchronizace takto:</span><span class="sxs-lookup"><span data-stu-id="9bba6-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="9bba6-105">Použijte msDS-ConsistencyGuid jako sourceAnchor atribut pro objekty User.</span><span class="sxs-lookup"><span data-stu-id="9bba6-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="9bba6-106">ObjectGUID se používá pro jiné typy objektů.</span><span class="sxs-lookup"><span data-stu-id="9bba6-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="9bba6-107">Pro všechny dané místní objekt uživatele služby AD, jehož atribut msDS-ConsistencyGuid není naplněn, Azure AD Connect zapíše jeho hodnotu objectGUID zpět do atributu msDS-ConsistencyGuid v místním adresáři Active Directory.</span><span class="sxs-lookup"><span data-stu-id="9bba6-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="9bba6-108">Po naplnění atributu msDS-ConsistencyGuid azure ad připojit pak exportuje objekt do Služby Azure AD.</span><span class="sxs-lookup"><span data-stu-id="9bba6-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="9bba6-109">**Poznámka:** Jakmile je místní objekt AD importován do služby Azure AD Connect (to znamená, že se importuje do prostoru konektoru a promítne se do Metaverse), už nelze změnit jeho hodnotu sourceAnchor.</span><span class="sxs-lookup"><span data-stu-id="9bba6-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="9bba6-110">Chcete-li určit hodnotu sourceAnchor pro daný místní objekt Služby AD, nakonfigurujte jeho atribut msDS-ConsistencyGuid před importem do služby Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="9bba6-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="9bba6-111">Další informace o SourceAnchor a ConsistencyGuid, najdete v následujících: [Azure AD Connect: Koncepty návrhu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="9bba6-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

