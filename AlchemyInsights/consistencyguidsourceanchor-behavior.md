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
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="d42f8-102">Vlastnosti ConsistencyGuid/Sourceukotvení</span><span class="sxs-lookup"><span data-stu-id="d42f8-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="d42f8-103">Azure AD Connect (verze 1.1.524.0 a After) nyní usnadňuje použití atributu msDS-ConsistencyGuid jako Sourcekotvu.</span><span class="sxs-lookup"><span data-stu-id="d42f8-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="d42f8-104">Při použití této funkce Azure AD Connect automaticky konfiguruje pravidla synchronizace na:</span><span class="sxs-lookup"><span data-stu-id="d42f8-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="d42f8-105">Jako atribut Sourcekotvy pro objekty User použijte identifikátor msDS-ConsistencyGuid.</span><span class="sxs-lookup"><span data-stu-id="d42f8-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="d42f8-106">Objekt ObjectGUID se používá pro jiné typy objektů.</span><span class="sxs-lookup"><span data-stu-id="d42f8-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="d42f8-107">Pro kterýkoli z objektů AD User, jehož atribut msDS-ConsistencyGuid není naplněn, program AD Connect zapíše svou hodnotu objectGUID zpět do atributu msDS-ConsistencyGuid v prostorách služby Active Directory.</span><span class="sxs-lookup"><span data-stu-id="d42f8-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="d42f8-108">Po naplnění atributu msDS-ConsistencyGuid provede Azure AD Connect objekt na Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d42f8-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="d42f8-109">**Poznámka:** Jakmile je v místě importován objekt AD do Azure AD Connect (to znamená, importováno do prostoru konektoru AD Connector a promítaný do metaverse), již nelze změnit jeho hodnotu Sourcekotvu.</span><span class="sxs-lookup"><span data-stu-id="d42f8-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="d42f8-110">Chcete-li určit hodnotu Sourcekotvu pro daný objekt AD, nakonfigurujte jeho atribut msDS-ConsistencyGuid před jeho importem do Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="d42f8-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="d42f8-111">Další informace o Sourcekotvy a ConsistencyGuid naleznete v následujících informacích: [Azure AD Connect: koncepce designu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="d42f8-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

