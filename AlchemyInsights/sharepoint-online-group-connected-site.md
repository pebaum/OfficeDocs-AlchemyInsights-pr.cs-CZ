---
title: Přidání skupiny do webu služby SharePoint
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 6aea12d44a44a3e11eaf3fb1bd47ff3e9dbfd9e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507840"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a><span data-ttu-id="37557-102">Problémy při vytváření nebo skupinu připojené weby v SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="37557-102">Issues when creating or group connected sites in SharePoint Online</span></span>

<span data-ttu-id="37557-103">Existuje několik běžných problémů při vytváření nebo znovu vytvořit skupinu připojení webu.</span><span class="sxs-lookup"><span data-stu-id="37557-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="37557-104">Pokud jste odstranili skupinu a její připojenou síť a chtějí vytvořit jiného webu se stejnou adresou URL, budete muset trvale odebrat předchozí Web.</span><span class="sxs-lookup"><span data-stu-id="37557-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="37557-105">Stáhnout [prostředí Management Shell SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="37557-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="37557-106">Další informace o Začínáme s powershell naleznete v tématu [Začínáme s Online prostředí správy služby SharePoint](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="37557-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="37557-107">Odeberte web ze serverů odstraněny pomocí rutiny prostředí powershell [Odebrat SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .</span><span class="sxs-lookup"><span data-stu-id="37557-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="37557-108">Pokud vytváříte skupinu připojenou síť a zobrazí upozornění, že jiné skupiny s stejný alias již existuje, zkontrolujte existující skupiny z [Office 365 Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span><span class="sxs-lookup"><span data-stu-id="37557-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="37557-109">Chcete-li tento problém vyřešit, odstraňte existující skupiny, pokud již není potřeba nebo vytvořit web s jiný alias přiřazen.</span><span class="sxs-lookup"><span data-stu-id="37557-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="37557-110">Vytvoření a použití moderních skupin se službou SharePoint různými způsoby.</span><span class="sxs-lookup"><span data-stu-id="37557-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="37557-111">Existující weby můžete připojit do skupiny Office 365.</span><span class="sxs-lookup"><span data-stu-id="37557-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="37557-112">Další informace získáte v části [připojení skupinu Office 365 pomocí ineterface uživatelů služby SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="37557-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="37557-113">Vytvořit web připojené skupiny Office 365, musíte vytvořit týmový web.</span><span class="sxs-lookup"><span data-stu-id="37557-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="37557-114">Další informace naleznete v článku [Vytvoření týmového webu služby SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="37557-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

