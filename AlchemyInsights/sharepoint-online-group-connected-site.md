---
title: Přidání skupiny na sharepointový web
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: e7bfabe1555bb94e915f8544d460deecce6171be
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770344"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a><span data-ttu-id="6d0c1-102">Problémy při vytváření skupinového připojeného webu v SharePointu</span><span class="sxs-lookup"><span data-stu-id="6d0c1-102">Issues when creating a group connected site in SharePoint</span></span>

1. <span data-ttu-id="6d0c1-103">Při vytváření nebo opětovném vytvoření propojeného webu skupiny se vyskytly některé běžné problémy.</span><span class="sxs-lookup"><span data-stu-id="6d0c1-103">Some common issues encountered when creating or re-creating a group connected site.</span></span>
<span data-ttu-id="6d0c1-104">Pokud jste odstranili skupinu a její připojený web a chcete vytvořit jiný web se stejnou adresou URL, budete muset předchozí web trvale odebrat.</span><span class="sxs-lookup"><span data-stu-id="6d0c1-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

   - <span data-ttu-id="6d0c1-105">Stažení [prostředí SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="6d0c1-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>
   - <span data-ttu-id="6d0c1-106">Další informace o tom, jak začít s Powershellem, najdete v tématu [Začínáme s prostředím SharePointu Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span><span class="sxs-lookup"><span data-stu-id="6d0c1-106">For more info on getting started with Powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span></span>
   - <span data-ttu-id="6d0c1-107">Odeberte web z odstraněných webů pomocí rutiny Prostředí Powershell [Remove-SPODeletedSite.](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="6d0c1-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell cmdlet.</span></span> <span data-ttu-id="6d0c1-108">Prostředí Powershell je nutné trvale odstranit weby skupin.</span><span class="sxs-lookup"><span data-stu-id="6d0c1-108">Powershell is required to permanently delete group sites.</span></span>

1. <span data-ttu-id="6d0c1-109">Pokud vytváříte skupinový propojený web a obdržíte upozornění: **Jiná skupina se stejným aliasem již existuje**, zkontrolujte existující skupiny z Centra pro správu office [365](https://admin.microsoft.com/AdminPortal/Home#/groups).</span><span class="sxs-lookup"><span data-stu-id="6d0c1-109">If you're creating a group connected site and receive a warning: **Another group with the same alias already exists**, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/AdminPortal/Home#/groups).</span></span> <span data-ttu-id="6d0c1-110">Chcete-li problém vyřešit, odstraňte existující skupinu, pokud již není potřeba, nebo vytvořte web s jiným přiřazeným aliasem.</span><span class="sxs-lookup"><span data-stu-id="6d0c1-110">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

1. <span data-ttu-id="6d0c1-111">Existují různé způsoby vytváření a používání moderních skupin se Službou SharePoint.</span><span class="sxs-lookup"><span data-stu-id="6d0c1-111">There are different ways to create and use modern groups with SharePoint.</span></span>

   - <span data-ttu-id="6d0c1-112">Existující weby můžete propojit se skupinou Office 365.</span><span class="sxs-lookup"><span data-stu-id="6d0c1-112">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="6d0c1-113">Další informace najdete v [tématu Připojení skupiny Office 365 pomocí uživatelského rozhraní SharePointu](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="6d0c1-113">For more info, see [Connect an Office 365 group using the SharePoint user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>
   - <span data-ttu-id="6d0c1-114">Chcete-li vytvořit propojený web skupiny Office 365, budete muset vytvořit [týmový web](https://admin.microsoft.com/sharepoint).</span><span class="sxs-lookup"><span data-stu-id="6d0c1-114">To create an Office 365 group connected site, you'll need to create a [Team Site](https://admin.microsoft.com/sharepoint).</span></span>
