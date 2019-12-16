---
title: Problémy s připojením aplikace SharePoint Designer
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 9730bd66afd494385db3de605f5fe68d0f274ed3
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051706"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="064b5-102">Problémy s připojením aplikace SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="064b5-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="064b5-103">Pokud aplikace SharePoint Designer zažívá problémy s připojením k webům služby SharePoint, vyzkoušejte následující běžná řešení.</span><span class="sxs-lookup"><span data-stu-id="064b5-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="064b5-104">Krok 1: Ověřte, zda je aplikace SharePoint Designer 2013 aktualizována pomocí aktualizace [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) , a [2. srpna 2016 pro aplikaci SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="064b5-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="064b5-105">Krok 2: vymazání místních souborů mezipaměti:</span><span class="sxs-lookup"><span data-stu-id="064b5-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="064b5-106">Ukončete aplikaci SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="064b5-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="064b5-107">V místním počítači odeberte všechny soubory nalezené v následujících složkách.</span><span class="sxs-lookup"><span data-stu-id="064b5-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="064b5-108">%AppData%\microsoft\webový Server Extensions\Cache</span><span class="sxs-lookup"><span data-stu-id="064b5-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="064b5-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="064b5-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="064b5-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="064b5-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="064b5-111">Spusťte aplikaci SharePoint Designer 2013 a znovu zadejte účet, aby bylo vidět, zda funguje.</span><span class="sxs-lookup"><span data-stu-id="064b5-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="064b5-112">Krok 3: [Povolte moderní ověřování pro sadu Office 2013 v zařízeních systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="064b5-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).</span></span>

<span data-ttu-id="064b5-113">Krok 4: Správci budou muset **Povolit vlastní skript** v nastavení centra pro správu služby SharePoint, aby bylo možné povolit připojení aplikace SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="064b5-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="064b5-114">Další informace naleznete v tématu [Povolení nebo zákaz vlastního skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .</span><span class="sxs-lookup"><span data-stu-id="064b5-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


