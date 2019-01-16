---
title: S externím uživatelům sdílení nefunguje.
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 305b3891e6c83e27b5c55c13757640e6e9d51a81
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281717"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="3754d-102">Řešení potíží s externím uživatelům sdílení obsahu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="3754d-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="3754d-103">Ujistěte se, že externí sdílení pro vaši organizaci:</span><span class="sxs-lookup"><span data-stu-id="3754d-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="3754d-104">Přejděte [služby &amp; stránku doplňky ve středisku pro správce služeb Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klepněte na tlačítko **servery**.</span><span class="sxs-lookup"><span data-stu-id="3754d-104">Go to the [Services &amp; add-ins page in the Office 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="3754d-p101">Zkontrolujte, zda že je zapnuto nastavení "On". Pokud je vybrána "Pouze existující externí uživatelé", přesvědčte se, zda externí uživatel je uveden ve středisku pro správce služeb Office 365.</span><span class="sxs-lookup"><span data-stu-id="3754d-p101">Make sure the setting is turned to "On." If "Only existing external users" is selected, make sure the external user is listed in the Office 365 admin center.</span></span>
    
<span data-ttu-id="3754d-p102">Přesvědčte se, zda externí sdílení zapnuta pro web. Kolekce klasických webů:</span><span class="sxs-lookup"><span data-stu-id="3754d-p102">Make sure external sharing it turned on for the site. For a classic site collection:</span></span>
  
1. <span data-ttu-id="3754d-109">V klasické SharePoint admin center v levém podokně klikněte na **kolekce webů**.</span><span class="sxs-lookup"><span data-stu-id="3754d-109">In the classic SharePoint admin center, in the left pane, click **site collections**.</span></span>
    
2. <span data-ttu-id="3754d-110">Vyberte web nebo weby a na pásu karet, klepněte na příkaz **sdílení**.</span><span class="sxs-lookup"><span data-stu-id="3754d-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="3754d-111">Pro týmový web, který patří do skupiny Office 365, nebo komunikační web:</span><span class="sxs-lookup"><span data-stu-id="3754d-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="3754d-p103">Tyto nové typy webu Pokud budou mít stejné sdílení nastavení jako nastavení celoorganizačních celopodnikové nastavení umožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlásit. V tomto případě weby povolit sdílení se nové a existující externí uživatelé přihlásit. Chcete-li změnit nastavení pro konkrétní weby, pomocí nového centra správy služby SharePoint (Náhled) nebo v prostředí PowerShell. [Další informace](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="3754d-p103">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in. In this case, the sites allow sharing with new and existing external users who sign in. To change the setting for specific sites, use the new SharePoint admin center (preview) or PowerShell. [Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="3754d-116">Externí sdílení nastavení libovolného webu může být více omezující než nastavení celoorganizačních ale povolující ne více než celopodnikové nastavení.</span><span class="sxs-lookup"><span data-stu-id="3754d-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

