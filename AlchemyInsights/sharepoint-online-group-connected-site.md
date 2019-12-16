---
title: Přidání skupiny na web služby SharePoint
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
ms.openlocfilehash: 14ad9dd094902c85eaf0398c76003cea20ad4c0a
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051094"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a><span data-ttu-id="3bcf3-102">Problémy při vytváření nebo seskupování připojených sítí ve službě SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="3bcf3-102">Issues when creating or group connected sites in SharePoint Online</span></span>

<span data-ttu-id="3bcf3-103">Při vytváření nebo vytváření nového serveru připojeného ke skupině došlo k několika běžným problémům.</span><span class="sxs-lookup"><span data-stu-id="3bcf3-103">There are a couple of common issues encountered when creating or re-creating a group connected site.</span></span>

 <span data-ttu-id="3bcf3-104">Pokud jste odstranili skupinu a její připojený web a chcete vytvořit další web se stejnou adresou URL, bude nutné trvale odebrat předchozí Web.</span><span class="sxs-lookup"><span data-stu-id="3bcf3-104">If you have deleted a group and its connected site and wish to create another site with the same URL, you'll need to permanently remove the previous site.</span></span>

<span data-ttu-id="3bcf3-105">Stáhnout [prostředí správy spo](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span><span class="sxs-lookup"><span data-stu-id="3bcf3-105">Download [SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)</span></span>

 <span data-ttu-id="3bcf3-106">Další informace o zahájení v prostředí PowerShell naleznete v tématu Začínáme [s prostředím SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span><span class="sxs-lookup"><span data-stu-id="3bcf3-106">For more info on getting started with powershell, see [Getting started with SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)</span></span>

<span data-ttu-id="3bcf3-107">Odebrání webu z odstraněných serverů pomocí rutiny pro [Odebrání-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) PowerShell</span><span class="sxs-lookup"><span data-stu-id="3bcf3-107">Remove the Site from Deleted Sites using the [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) powershell cmdlet.</span></span>

<span data-ttu-id="3bcf3-108">Pokud vytváříte připojený skupinový web a přijímáte upozornění jiná skupina se stejným alias již existuje, zkontrolujte existující skupiny z [webu Office 365 z centra pro správu](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span><span class="sxs-lookup"><span data-stu-id="3bcf3-108">If you're creating a group connected site and receive a warning Another group with the same alias already exists, check the existing groups from the [Office 365 from the Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups).</span></span> <span data-ttu-id="3bcf3-109">Chcete-li tento problém vyřešit, odstraňte existující skupinu, pokud již není potřebná, nebo vytvořte web s přiřazeným jiným aliasem.</span><span class="sxs-lookup"><span data-stu-id="3bcf3-109">To resolve the issue, delete the existing group if it's no longer needed or create the site with a different alias assigned.</span></span>

<span data-ttu-id="3bcf3-110">Existují různé způsoby, jak vytvořit a používat moderní skupiny se službou SharePoint.</span><span class="sxs-lookup"><span data-stu-id="3bcf3-110">There are different ways to create and use modern groups with SharePoint.</span></span>

<span data-ttu-id="3bcf3-111">Existující weby můžete připojit ke skupině Office 365.</span><span class="sxs-lookup"><span data-stu-id="3bcf3-111">You can connect existing sites to an Office 365 group.</span></span> <span data-ttu-id="3bcf3-112">Další informace naleznete v tématu [připojení skupiny Office 365 pomocí neexistujícího uživatele služby SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span><span class="sxs-lookup"><span data-stu-id="3bcf3-112">For more info, see [Connect an Office 365 group using the SharePoint user ineterface](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).</span></span>

<span data-ttu-id="3bcf3-113">Chcete-li vytvořit připojený web sady Office 365, je třeba vytvořit týmový Web.</span><span class="sxs-lookup"><span data-stu-id="3bcf3-113">To create an Office 365 group connected site, you'll need to create a Team Site.</span></span> <span data-ttu-id="3bcf3-114">Další informace naleznete v tématu [vytvoření týmového webu ve službě SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span><span class="sxs-lookup"><span data-stu-id="3bcf3-114">For more info, see [Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).</span></span>

