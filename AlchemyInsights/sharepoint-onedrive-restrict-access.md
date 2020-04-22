---
title: Omezení přístupu na SharePointu nebo OneDrivu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 39aa8cd6e649eca4a1e196eeb589a825364d0977
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692758"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="c9242-102">Omezení přístupu na SharePointu nebo OneDrivu</span><span class="sxs-lookup"><span data-stu-id="c9242-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="c9242-103">Přístup ke službám SharePointu Online/OneDrive můžete omezit mnoha způsoby.</span><span class="sxs-lookup"><span data-stu-id="c9242-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="c9242-104">Tyto různé metody omezení přístupu jsou uvedeny níže.</span><span class="sxs-lookup"><span data-stu-id="c9242-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="c9242-105">**Omezení oprávnění**</span><span class="sxs-lookup"><span data-stu-id="c9242-105">**Permission Restriction**</span></span>

<span data-ttu-id="c9242-106">V SharePointu Online a OneDrivu pro firmy omezujeme přístup k položkám, jako jsou weby, soubory a složky, tím, že udělujeme přístup jenom těm skupinám nebo jednotlivcům, kteří by k nim měli mít přístup.</span><span class="sxs-lookup"><span data-stu-id="c9242-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

- [<span data-ttu-id="c9242-107">Přizpůsobení oprávnění pro sharepointový seznam nebo knihovnu</span><span class="sxs-lookup"><span data-stu-id="c9242-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [<span data-ttu-id="c9242-108">Přizpůsobení oprávnění sharepointového webu</span><span class="sxs-lookup"><span data-stu-id="c9242-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [<span data-ttu-id="c9242-109">Změna oprávnění v podsložce</span><span class="sxs-lookup"><span data-stu-id="c9242-109">Change the permissions on a subfolder</span></span>](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [<span data-ttu-id="c9242-110">Řízení přístupu z nespravovaných zařízení</span><span class="sxs-lookup"><span data-stu-id="c9242-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="c9242-111">Jako sharepointový nebo globální správce můžete blokovat nebo omezit přístup k obsahu SharePointu a OneDrivu z nespravovaných zařízení (těch, která v Intune nehybridní ad připojili nebo nedodržují předpisy).</span><span class="sxs-lookup"><span data-stu-id="c9242-111">As a SharePoint or global admin, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="c9242-112">**Omezení umístění v síti**</span><span class="sxs-lookup"><span data-stu-id="c9242-112">**Network Location Restriction**</span></span>

<span data-ttu-id="c9242-113">Jako správce IT můžete řídit přístup k prostředkům SharePointu a OneDrivu na základě definovaných síťových umístění, kterým důvěřujete.</span><span class="sxs-lookup"><span data-stu-id="c9242-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="c9242-114">To se také označuje jako zásady založené na poloze.</span><span class="sxs-lookup"><span data-stu-id="c9242-114">This is also known as location-based policy.</span></span> <span data-ttu-id="c9242-115">Další informace najdete v [tématu Řízení přístupu k sharepointovým online a onedrivem dat na základě umístění v síti.](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span><span class="sxs-lookup"><span data-stu-id="c9242-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="c9242-116">**Omezení uzamčení webu**</span><span class="sxs-lookup"><span data-stu-id="c9242-116">**Site Lock Restriction**</span></span> 

<span data-ttu-id="c9242-117">V SharePointu Online můžete uzamknout kolekci webů, aby k ní neměl nikdo přístup.</span><span class="sxs-lookup"><span data-stu-id="c9242-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="c9242-118">To se nastavuje přes PowerShell a [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) pomocí [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState vlastnost.</span><span class="sxs-lookup"><span data-stu-id="c9242-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="c9242-119">**Omezení vytváření webů nebo podřízených webů uživateli**</span><span class="sxs-lookup"><span data-stu-id="c9242-119">**Restrict users from creating sites or subsites**</span></span>

<span data-ttu-id="c9242-120">Jako správce SharePointu nebo globální správce můžete uživatelům udělit vlastní sharepointové weby, určit, jaký typ webů můžou vytvářet, a určit umístění webů.</span><span class="sxs-lookup"><span data-stu-id="c9242-120">As a SharePoint admin or Global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="c9242-121">Další informace najdete v tématu [Správa vytváření webů v SharePointu Online.](https://docs.microsoft.com/sharepoint/manage-site-creation)</span><span class="sxs-lookup"><span data-stu-id="c9242-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span></span>

