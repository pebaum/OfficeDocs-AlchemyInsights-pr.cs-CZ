---
title: Vytvoření webu služby SharePoint
ms.author: efrene
author: efrene
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 30c51d84005534cc1de9e8b8136da1a07be57b73
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36738190"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="8a644-102">Vytvoření webu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="8a644-102">Create a SharePoint site</span></span>

<span data-ttu-id="8a644-103">Informace o vytváření webů služby SharePoint lze zobrazit následujícím způsobem:</span><span class="sxs-lookup"><span data-stu-id="8a644-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="8a644-104">[Spravovat weby v novém centru pro správu služby SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation): Získejte informace o možnostech vytváření webů, včetně způsobu vytvoření klasického webu nebo webu týmů, který neobsahuje skupinu Office 365.</span><span class="sxs-lookup"><span data-stu-id="8a644-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="8a644-105">[Vytvoření týmového webu ve službě SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): Naučte se vytvořit týmový Web.</span><span class="sxs-lookup"><span data-stu-id="8a644-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d): Learn how to create a team site.</span></span>
- <span data-ttu-id="8a644-106">[Vytvoření komunikačního webu ve službě SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Naučte se, jak vytvořit web komunikace.</span><span class="sxs-lookup"><span data-stu-id="8a644-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="8a644-107">[Spravovat weby v novém centru pro správu služby SharePoint](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Naučte se, jak vytvořit klasický web nebo týmový web, který neobsahuje skupinu Office 365.</span><span class="sxs-lookup"><span data-stu-id="8a644-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
> <span data-ttu-id="8a644-108">[! Tipy</span><span class="sxs-lookup"><span data-stu-id="8a644-108">[!Tips]</span></span>
> - <span data-ttu-id="8a644-109">Nelze vytvořit web se stejnou adresou URL existujícího webu.</span><span class="sxs-lookup"><span data-stu-id="8a644-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="8a644-110">Pokud jste odstranili web a chtěli znovu použít tuto adresu URL, je možné, že odstraněný web stále existuje pod **odstraněným**webem.</span><span class="sxs-lookup"><span data-stu-id="8a644-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="8a644-111">Chcete-li spravovat odstraněné weby, viz [odstranění webu](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="8a644-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="8a644-112">Chcete-li web zcela odebrat pomocí prostředí PowerShell, podívejte se na příklad rutiny [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .</span><span class="sxs-lookup"><span data-stu-id="8a644-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
> - <span data-ttu-id="8a644-113">Někteří uživatelé nemusí být schopni vytvořit web.</span><span class="sxs-lookup"><span data-stu-id="8a644-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="8a644-114">Viz [Správa vytváření webů na webu služby SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="8a644-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
> - <span data-ttu-id="8a644-115">Je možné, že se web zdá být zablokený při **vytváření** déle, než bylo očekáváno.</span><span class="sxs-lookup"><span data-stu-id="8a644-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="8a644-116">Pokud od prvního vydání tohoto problému uplynulo více než 24 hodin, zadejte do protokolu lístek odborné pomoci.</span><span class="sxs-lookup"><span data-stu-id="8a644-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="8a644-117">V mnoha případech už pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="8a644-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="8a644-118">K dokončení řešení nám prosím dejte alespoň 24 hodin.</span><span class="sxs-lookup"><span data-stu-id="8a644-118">Please give us at least 24 hours to complete a solution.</span></span>
> - <span data-ttu-id="8a644-119">Pokud potřebujete vytvořit nový týmový web, který neobsahuje skupinu Office 365,</span><span class="sxs-lookup"><span data-stu-id="8a644-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 


