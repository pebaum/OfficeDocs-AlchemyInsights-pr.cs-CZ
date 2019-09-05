---
title: Omezení přístupu ve službě SharePoint nebo OneDrive
ms.author: pebaum
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: bef0612903b9bb455aa34e90d35d6b7b9093b4e0
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36750657"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a><span data-ttu-id="4ddbd-102">Omezení přístupu ve službě SharePoint nebo OneDrive</span><span class="sxs-lookup"><span data-stu-id="4ddbd-102">Restrict access in SharePoint or OneDrive</span></span>

<span data-ttu-id="4ddbd-103">Přístup ke službám služby SharePoint Online/OneDrive lze omezit mnoha způsoby.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-103">There are many ways to restrict access to SharePoint Online/OneDrive services.</span></span> <span data-ttu-id="4ddbd-104">Tyto různé metody omezení přístupu jsou popsány níže.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-104">These various access restriction methods are outlined below.</span></span> 

<span data-ttu-id="4ddbd-105">**Omezení oprávnění**</span><span class="sxs-lookup"><span data-stu-id="4ddbd-105">**Permission Restriction**</span></span>

<span data-ttu-id="4ddbd-106">V aplikaci SharePoint Online a OneDrive for Business omezujeme přístup k položkám, jako jsou weby, soubory a složky, tím, že udělíte přístup pouze těmto skupinám nebo jednotlivcům, kteří by měli mít přístup.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-106">In SharePoint Online and OneDrive for Business, we restrict access to items like sites, files and folders by only granting access to those groups/individuals who should have access.</span></span>

- [<span data-ttu-id="4ddbd-107">Přizpůsobení oprávnění pro seznam nebo knihovnu SharePoint</span><span class="sxs-lookup"><span data-stu-id="4ddbd-107">Customize permissions for a SharePoint list or library</span></span>](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [<span data-ttu-id="4ddbd-108">Vlastní nastavení oprávnění webu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="4ddbd-108">Customize SharePoint site permissions</span></span>](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [<span data-ttu-id="4ddbd-109">Změna oprávnění podsložky</span><span class="sxs-lookup"><span data-stu-id="4ddbd-109">Change the permissions on a subfolder</span></span>](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [<span data-ttu-id="4ddbd-110">Řízení přístupu z nespravovaných zařízení</span><span class="sxs-lookup"><span data-stu-id="4ddbd-110">Control access from unmanaged devices</span></span>](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

<span data-ttu-id="4ddbd-111">Jako server SharePoint nebo globální správce v sadě Office 365 můžete blokovat nebo omezit přístup k obsahu služby SharePoint a OneDrive z nespravovaných zařízení (které nejsou spojeny s křížovým přístupem nebo jsou kompatibilní v Intune).</span><span class="sxs-lookup"><span data-stu-id="4ddbd-111">As a SharePoint or global admin in Office 365, you can block or limit access to SharePoint and OneDrive content from unmanaged devices (those not hybrid AD joined or compliant in Intune).</span></span>

<span data-ttu-id="4ddbd-112">**Omezení umístění v síti**</span><span class="sxs-lookup"><span data-stu-id="4ddbd-112">**Network Location Restriction**</span></span>

<span data-ttu-id="4ddbd-113">Jako správce IT můžete řídit přístup k prostředkům SharePoint a OneDrive na základě definovaných síťových umístění, kterým důvěřujete.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-113">As an IT admin, you can control access to SharePoint and OneDrive resources based on defined network locations that you trust.</span></span> <span data-ttu-id="4ddbd-114">Toto je označováno také jako zásada založená na umístění.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-114">This is also known as location-based policy.</span></span> <span data-ttu-id="4ddbd-115">Další informace naleznete v tématu [řízení přístupu k datům služby SharePoint Online a OneDrive na základě umístění v síti](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location) .</span><span class="sxs-lookup"><span data-stu-id="4ddbd-115">For more information, please see [Control access to SharePoint Online and OneDrive data based on network location](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)</span></span>

<span data-ttu-id="4ddbd-116">**Omezení uzamčení webu**</span><span class="sxs-lookup"><span data-stu-id="4ddbd-116">**Site Lock Restriction**</span></span> 

<span data-ttu-id="4ddbd-117">V rámci služby SharePoint Online máte možnost Uzamknout kolekci webů, takže k ní nikdo nemá přístup.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-117">Within SharePoint Online you have the ability to lock down a site collection, so no one has access.</span></span> <span data-ttu-id="4ddbd-118">Tato vlastnost je nastavena prostřednictvím prostředí PowerShell a [prostředí SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) pomocí vlastnosti [set-sposite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-118">This is set via PowerShell and the [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) using the [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState property.</span></span>

<span data-ttu-id="4ddbd-119">**Omezení uživatelů na vytváření webů nebo podřízených webů**</span><span class="sxs-lookup"><span data-stu-id="4ddbd-119">**Restrict users from creating sites or subsites**</span></span>

<span data-ttu-id="4ddbd-120">Jako správce serveru SharePoint nebo Office 365 Global admin můžete uživatelům dovolit vytvářet a spravovat vlastní weby služby SharePoint, určovat, jaký druh webů mohou vytvořit, a určit umístění webů.</span><span class="sxs-lookup"><span data-stu-id="4ddbd-120">As a SharePoint admin or Office 365 global admin, you can let your users create and administer their own SharePoint sites, determine what kind of sites they can create, and specify the location of the sites.</span></span> <span data-ttu-id="4ddbd-121">Další informace naleznete [v tématu Správa vytváření webů na webu služby SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span><span class="sxs-lookup"><span data-stu-id="4ddbd-121">For more information, please see [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)</span></span>

