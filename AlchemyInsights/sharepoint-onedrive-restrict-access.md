---
title: Omezení přístupu v serveru SharePoint nebo OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 5101366ff65f477c19b9c7f2c0d7065cf88501b0
ms.sourcegitcommit: 241e21b6da226563bf70bdb1f5bad3d91c38cd2c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/05/2019
ms.locfileid: "34735136"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="c460e-102">Omezení přístupu v serveru SharePoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="c460e-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="c460e-103">Existuje mnoho způsobů, jak omezit přístup k služby SharePoint Online nebo OneDrive.</span><span class="sxs-lookup"><span data-stu-id="c460e-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="c460e-104">Tyto různé metody omezení přístupu jsou uvedeny níže.</span><span class="sxs-lookup"><span data-stu-id="c460e-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="c460e-105">Omezení oprávnění</span><span class="sxs-lookup"><span data-stu-id="c460e-105">Permission Restriction</span></span>

<span data-ttu-id="c460e-106">V SharePoint Online a OneDrive pro firmy můžeme omezit přístup k položky, jako jsou weby, soubory a složky pouze poskytnutím přístupu k skupiny nebo uživatelé, kteří mají mít přístup.</span><span class="sxs-lookup"><span data-stu-id="c460e-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

[<span data-ttu-id="c460e-107">Upravit oprávnění pro knihovnu nebo seznam SharePoint</span><span class="sxs-lookup"><span data-stu-id="c460e-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/en-us/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

[<span data-ttu-id="c460e-108">Upravit oprávnění pro web služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="c460e-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions)

[<span data-ttu-id="c460e-109">Změnit oprávnění pro podsložky</span><span class="sxs-lookup"><span data-stu-id="c460e-109">Change the permissions on a subfolder</span></span>](https://support.office.com/en-us/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

[<span data-ttu-id="c460e-110">Řízení přístupu z nespravovaných zařízení</span><span class="sxs-lookup"><span data-stu-id="c460e-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/en-us/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="c460e-111">Jako SharePoint nebo globálního správce ve službách Office 365, můžete blokovat nebo omezit přístup k obsahu služby SharePoint nebo OneDrive z nespravovaných zařízení (tyto hybridní AD spojených nebo kompatibilní v Intune).</span><span class="sxs-lookup"><span data-stu-id="c460e-111">As a SharePoint or global admin in Office 365, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="c460e-112">Omezení umístění v síti</span><span class="sxs-lookup"><span data-stu-id="c460e-112">Network Location Restriction</span></span>

<span data-ttu-id="c460e-113">Jako IT správce můžete řídit přístup k prostředkům služby SharePoint a OneDrive založené na definované síťové umístění, které považujete za důvěryhodné.</span><span class="sxs-lookup"><span data-stu-id="c460e-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="c460e-114">Je také známý jako zásady založené na umístění.</span><span class="sxs-lookup"><span data-stu-id="c460e-114">This is also known as location-based policy.</span></span> <span data-ttu-id="c460e-115">Další informace naleznete v tématu [řízení přístupu k serveru SharePoint Online a OneDrive data v závislosti na umístění v síti](https://docs.microsoft.com/en-us/sharepoint/control-access-based-on-network-location)</span><span class="sxs-lookup"><span data-stu-id="c460e-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/en-us/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="c460e-116">Omezení uzamčení webu</span><span class="sxs-lookup"><span data-stu-id="c460e-116">Site Lock Restriction</span></span> 

<span data-ttu-id="c460e-117">V rámci služby SharePoint Online máte možnost Uzamknout kolekci webů, tak nemá nikdo přístup.</span><span class="sxs-lookup"><span data-stu-id="c460e-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="c460e-118">Tato hodnota je nastavena pomocí prostředí PowerShell a [Prostředí Online správy služby SharePoint](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) pomocí vlastnosti [Sady SPOSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) - LockState.</span><span class="sxs-lookup"><span data-stu-id="c460e-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="c460e-119">Uživatelé nemohli vytvářet weby nebo podřízené weby</span><span class="sxs-lookup"><span data-stu-id="c460e-119">Restrict users from creating sites or subsites</span></span>

<span data-ttu-id="c460e-120">Jako správce serveru SharePoint nebo globálního správce služeb Office 365, umožníte uživatelům vytvářet a spravovat své vlastní weby služby SharePoint, zjistit, jaké weby mohou vytvořit a určete umístění serverů.</span><span class="sxs-lookup"><span data-stu-id="c460e-120">As a SharePoint admin or Office 365 global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="c460e-121">Další informace naleznete v tématu [Správa vytváření webu v Online služby SharePoint](https://docs.microsoft.com/en-us/sharepoint/manage-site-creation)</span><span class="sxs-lookup"><span data-stu-id="c460e-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/manage-site-creation)</span></span>

