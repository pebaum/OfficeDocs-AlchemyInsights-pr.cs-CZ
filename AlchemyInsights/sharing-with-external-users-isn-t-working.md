---
title: Sdílení s externími uživateli nepracuje
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: d4c8fc75ff8db2319b88a20bea9b3ee661f2e36e
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36502224"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="14cf3-102">Opravit problémy se sdílením obsahu služby SharePoint s externími uživateli</span><span class="sxs-lookup"><span data-stu-id="14cf3-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="14cf3-103">Zkontrolujte, zda je pro vaši organizaci zapnuto externí sdílení:</span><span class="sxs-lookup"><span data-stu-id="14cf3-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="14cf3-104">Přejděte na [stránku doplňky &amp; služeb v centru pro správu Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klepněte na možnost **servery**.</span><span class="sxs-lookup"><span data-stu-id="14cf3-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="14cf3-105">Ujistěte se, že je nastavení zapnuto "zapnuto".</span><span class="sxs-lookup"><span data-stu-id="14cf3-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="14cf3-106">Pokud je vybrána možnost pouze existující externí uživatelé, ujistěte se, že je externí uživatel uveden v centru pro správu Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="14cf3-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="14cf3-107">Přesvědčte se, zda je u daného webu zapnuto externí sdílení.</span><span class="sxs-lookup"><span data-stu-id="14cf3-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="14cf3-108">Klasická kolekce webů:</span><span class="sxs-lookup"><span data-stu-id="14cf3-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="14cf3-109">V novém centru pro správu služby SharePoint klepněte v levém podokně na položku **servery**.</span><span class="sxs-lookup"><span data-stu-id="14cf3-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="14cf3-110">Vyberte web nebo weby a na pásu karet klepněte na tlačítko **sdílení**.</span><span class="sxs-lookup"><span data-stu-id="14cf3-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="14cf3-111">Týmový web, který patří do skupiny Office 365, nebo na komunikační web:</span><span class="sxs-lookup"><span data-stu-id="14cf3-111">For a team site that belongs to an Office 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="14cf3-112">Tyto nové typy webů mají stejné nastavení sdílení jako nastavení pro celou organizaci, pokud nastavení na úrovni organizace neumožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlášení.</span><span class="sxs-lookup"><span data-stu-id="14cf3-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="14cf3-113">V tomto případě weby umožňují sdílení s novými a existujícími externími uživateli, kteří se budou přihlašovat.</span><span class="sxs-lookup"><span data-stu-id="14cf3-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="14cf3-114">Chcete-li změnit nastavení pro určité weby, použijte nové centrum pro správu služby SharePoint nebo prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="14cf3-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="14cf3-115">Další [informace](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="14cf3-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="14cf3-116">Nastavení externího sdílení pro všechny weby může být více omezující než nastavení celé organizace, ale nikoli více opravňující nastavení pro celou organizaci.</span><span class="sxs-lookup"><span data-stu-id="14cf3-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  

