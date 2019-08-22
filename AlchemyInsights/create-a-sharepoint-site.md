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
ms.openlocfilehash: 96780bd2f4182c1385406ec2a31cd62745137985
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36515800"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="7b8f6-102">Vytvoření webu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="7b8f6-102">Create a SharePoint site</span></span>

<span data-ttu-id="7b8f6-103">Můžete zobrazit následující informace o vytváření webů služby SharePoint:</span><span class="sxs-lookup"><span data-stu-id="7b8f6-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="7b8f6-104">[Správa webů v centru nového správce služby SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation): Další informace o možnosti vytvoření webu, včetně vytvoření klasické web nebo web týmům, který nebude obsahovat skupinu služeb Office 365.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="7b8f6-105">[Vytvořit týmový web služby SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Zjistěte, jak vytvořit týmový web.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Learn how to create a team site.</span></span>
- <span data-ttu-id="7b8f6-106">[Vytvořit web komunikace v Online služby SharePoint](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Zjistěte, jak vytvořit web komunikace.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="7b8f6-107">[Správa webů v centru nového správce služby SharePoint](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Zjistěte, jak vytvořit klasický web nebo Týmový web, který nebude obsahovat skupinu služeb Office 365.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
> [! Tipy]
> - <span data-ttu-id="7b8f6-109">Nelze vytvořit web pomocí stejnou adresu URL existujícího webu.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="7b8f6-110">Pokud odstranit web a jsou chtějí znovu použít adresu URL, je možné, že odstraněné serveru stále existuje v seznamu **odstraněných webů**.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="7b8f6-111">Ke správě odstranění webů naleznete v tématu [Odstranění webu](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="7b8f6-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="7b8f6-112">K úplnému odebrání serveru pomocí prostředí Powershell, naleznete v příkladu rutiny [SPSite odebrat](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .</span><span class="sxs-lookup"><span data-stu-id="7b8f6-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
> - <span data-ttu-id="7b8f6-113">Někteří uživatelé nemusí být schopen vytvořit web.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="7b8f6-114">Viz [vytváření webů spravovat v Online služby SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="7b8f6-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
> - <span data-ttu-id="7b8f6-115">Je možné že na webu se zobrazí zablokované na **vytváření** déle, než bylo očekáváno.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="7b8f6-116">Pokud více než 24 hodin uplynulo od poprvé viděli tento problém, zkontrolujte protokolu lístek podpory.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="7b8f6-117">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="7b8f6-118">Uveďte, prosím, nás alespoň 24 hodin, řešení.</span><span class="sxs-lookup"><span data-stu-id="7b8f6-118">Please give us at least 24 hours to complete a solution.</span></span>
> - <span data-ttu-id="7b8f6-119">Pokud potřebujete vytvořit nový týmový web, který nebude obsahovat skupinu služeb Office 365</span><span class="sxs-lookup"><span data-stu-id="7b8f6-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 


