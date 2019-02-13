---
title: Vytvoření webu služby SharePoint
ms.author: kirks
author: Techwriter40
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: a4c6029c632178136396a91ba9754752dc8f7180
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29932825"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="5ac6f-102">Vytvoření webu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="5ac6f-102">Create a SharePoint site</span></span>

<span data-ttu-id="5ac6f-p101">Možnosti vytváření webu naleznete v tématu [Správa webů v centru nového správce služby SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation ) . Vyberte pro vytvoření [týmového webu](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) , (který bude vytvořit skupinu Office 365) nebo [komunikační web](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb). Chcete-li vytvořit [Web classic](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site)nebo nové týmový web, který nebude obsahovat skupinu služeb Office 365, klepněte na **Další možnosti**.</span><span class="sxs-lookup"><span data-stu-id="5ac6f-p101">See [Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation ) for site creation options. Select to create a [team site](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US) (which will create an Office 365 group) or a [communication site](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb). To create a [classic site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site), or a new team site that doesn't include an Office 365 group, click **Other options**.</span></span> 
  
<span data-ttu-id="5ac6f-106">Tipy:</span><span class="sxs-lookup"><span data-stu-id="5ac6f-106">Tips:</span></span>
- <span data-ttu-id="5ac6f-107">*Nelze vytvořit web pomocí stejnou adresu URL existujícího webu. Pokud odstranit web a jsou chtějí znovu použít adresu URL, je možné, že odstraněné serveru stále existuje v seznamu **odstraněných webů**. Ke správě odstranění webů naleznete v tématu [Odstranění webu](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site). K úplnému odebrání serveru pomocí prostředí Powershell, naleznete v příkladu rutiny [SPSite odebrat](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .*</span><span class="sxs-lookup"><span data-stu-id="5ac6f-107">*You cannot create a site with the same URL of an existing site. If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**. To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site). To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.*</span></span>
- <span data-ttu-id="5ac6f-108">*Někteří uživatelé nemusí být schopen vytvořit web. Viz [vytváření webů spravovat v Online služby SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation).*</span><span class="sxs-lookup"><span data-stu-id="5ac6f-108">*Some users may not be able to create a site. See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).*</span></span>
- <span data-ttu-id="5ac6f-109">*Je možné že na webu se zobrazí zablokované na **vytváření** déle, než bylo očekáváno. Pokud více než 24 hodin uplynulo od poprvé viděli tento problém, zkontrolujte protokolu lístek podpory. V mnoha případech již pracujeme na řešení. Uveďte, prosím, nás alespoň 24 hodin, řešení.*</span><span class="sxs-lookup"><span data-stu-id="5ac6f-109">*It's possible the site appears stuck at **Creating** longer than expected. If more than 24 hours have passed since you first saw this issue, please log a support ticket. In many cases, we're already working on a solution. Please give us at least 24 hours to complete a solution.*</span></span>
