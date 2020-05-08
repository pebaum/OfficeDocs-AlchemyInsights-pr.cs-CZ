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
ms.openlocfilehash: b54457427ffa563b6a6323d85e1c8800191eca11
ms.sourcegitcommit: d1aad215f8aa636ba89c93a13a0c9d90e997f752
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/06/2020
ms.locfileid: "44064386"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a><span data-ttu-id="66943-102">Problémy při vytváření připojeného webu skupiny v SharePointu</span><span class="sxs-lookup"><span data-stu-id="66943-102">Issues when creating a group connected site in SharePoint</span></span>

1. <span data-ttu-id="66943-103">Při vytváření nebo opětovném vytváření připojeného webu skupiny došlo k některým běžným problémům.</span><span class="sxs-lookup"><span data-stu-id="66943-103">Some common issues encountered when creating or re-creating a group connected site.</span></span>
<span data-ttu-id="66943-104">Pokud jste odstranili skupinu a její připojený web a chcete vytvořit jiný web se stejnou adresou URL, budete muset trvale odebrat předchozí web.</span><span class="sxs-lookup"><span data-stu-id="66943-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

   - <span data-ttu-id="66943-105">Stáhnout [prostředí pro správu SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="66943-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>
   - <span data-ttu-id="66943-106">Další informace o tom, jak začít s Powershellem, najdete [v tématu Začínáme s SharePointem Online Management Shellem](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span><span class="sxs-lookup"><span data-stu-id="66943-106">For more info on getting started with Powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).</span></span>
   - <span data-ttu-id="66943-107">Odeberte web z odstraněných webů pomocí rutiny [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell.</span><span class="sxs-lookup"><span data-stu-id="66943-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell cmdlet.</span></span> <span data-ttu-id="66943-108">Powershell je nutné trvale odstranit stránky skupiny.</span><span class="sxs-lookup"><span data-stu-id="66943-108">Powershell is required to permanently delete group sites.</span></span>

1. <span data-ttu-id="66943-109">Pokud vytváříte web připojený ke skupině a zobrazí se upozornění: **Jiná skupina se stejným aliasem již existuje**, zkontrolujte existující skupiny z Centra pro [správu Microsoftu 365](https://admin.microsoft.com/AdminPortal/Home#/groups).</span><span class="sxs-lookup"><span data-stu-id="66943-109">If you're creating a group connected site and receive a warning: **Another group with the same alias already exists**, check the existing groups from the [Microsoft 365 admin center](https://admin.microsoft.com/AdminPortal/Home#/groups).</span></span> <span data-ttu-id="66943-110">Chcete-li tento problém vyřešit, odstraňte existující skupinu, pokud již není potřeba, nebo vytvořte web s přiřazeným jiným aliasem.</span><span class="sxs-lookup"><span data-stu-id="66943-110">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

1. <span data-ttu-id="66943-111">Existují různé způsoby, jak vytvářet a používat moderní skupiny se SharePointem.</span><span class="sxs-lookup"><span data-stu-id="66943-111">There are different ways to create and use modern groups with SharePoint.</span></span>

   - <span data-ttu-id="66943-112">Existující weby můžete připojit ke skupině Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="66943-112">You can connect existing sites to an Microsoft 365 group.</span></span> <span data-ttu-id="66943-113">Další informace najdete [v tématu Připojení skupiny Microsoft 365 pomocí uživatelského rozhraní SharePointu](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="66943-113">For more info, see [Connect an Microsoft 365 group using the SharePoint user interface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>
   - <span data-ttu-id="66943-114">Chcete-li vytvořit propojený web skupiny Microsoft 365, budete muset vytvořit [týmový web](https://admin.microsoft.com/sharepoint).</span><span class="sxs-lookup"><span data-stu-id="66943-114">To create an Microsoft 365 group connected site, you'll need to create a [Team Site](https://admin.microsoft.com/sharepoint).</span></span>
