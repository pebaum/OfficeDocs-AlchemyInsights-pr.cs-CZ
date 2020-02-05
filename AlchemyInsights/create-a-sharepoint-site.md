---
title: Vytvoření sharepointového webu
ms.author: pebaum
author: todmccoy
ms.audience: Admin
ms.topic: article
ms.collection: Adm_O365
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "5200004"
- "3911416"
- "1386"
- "2303"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: e1e71ae9401448ed18058f6307302dcbaf773649
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770848"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="bcfd1-102">Vytvoření sharepointového webu</span><span class="sxs-lookup"><span data-stu-id="bcfd1-102">Create a SharePoint site</span></span>

<span data-ttu-id="bcfd1-103">Vytvářejte nebo spravujte weby z [aktivních webů](https://admin.microsoft.com/sharepoint?page=sitemanagement&modern=true) v Centru pro správu SharePointu.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-103">Create or manage sites from [Active Sites](https://admin.microsoft.com/sharepoint?page=sitemanagement&modern=true) in the SharePoint Admin Center.</span></span> <span data-ttu-id="bcfd1-104">Další informace najdete v [tématu Správa webů v novém Centru pro správu SharePointu](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="bcfd1-104">For more info, see [Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span> 

## <a name="tips"></a><span data-ttu-id="bcfd1-105">Tipy:</span><span class="sxs-lookup"><span data-stu-id="bcfd1-105">Tips:</span></span>

- <span data-ttu-id="bcfd1-106">Web se stejnou adresou URL existujícího webu **nelze** vytvořit.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-106">You **cannot** create a site with the same URL of an existing site.</span></span> <span data-ttu-id="bcfd1-107">Pokud jste web odstranili a chcete adresu URL znovu použít, je možné, že odstraněný web stále existuje v části [Odstraněné weby](https://admin.microsoft.com/sharepoint?page=recyclebin&modern=true).</span><span class="sxs-lookup"><span data-stu-id="bcfd1-107">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under [Deleted sites](https://admin.microsoft.com/sharepoint?page=recyclebin&modern=true).</span></span> <span data-ttu-id="bcfd1-108">Chcete-li adresu URL znovu použít, bude nutné web trvale odstranit.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-108">The site will need to be permanently deleted to re-use the URL.</span></span> <span data-ttu-id="bcfd1-109">Úplné odebrání webu pomocí prostředí Powershell naleznete v příkladu rutiny [Remove-SPSite.](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site)</span><span class="sxs-lookup"><span data-stu-id="bcfd1-109">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
- <span data-ttu-id="bcfd1-110">Někteří uživatelé nemusí být schopni vytvořit web.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-110">Some users may not be able to create a site.</span></span> <span data-ttu-id="bcfd1-111">[Viz Správa vytváření webů v SharePointu Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="bcfd1-111">[See Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
- <span data-ttu-id="bcfd1-112">Je možné, že web se objeví přilepená na **Vytvoření** déle, než se očekávalo.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-112">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="bcfd1-113">Pokud od prvního uviděl(a) tento problém více než 24 hodin, zaznaďte lístek podpory.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-113">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="bcfd1-114">V mnoha případech již pracujeme na řešení.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-114">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="bcfd1-115">Dejte nám prosím alespoň 24 hodin na dokončení řešení.</span><span class="sxs-lookup"><span data-stu-id="bcfd1-115">Please give us at least 24 hours to complete a solution.</span></span>
