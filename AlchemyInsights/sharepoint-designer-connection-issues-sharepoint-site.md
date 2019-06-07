---
title: SharePoint Online úrovně oprávnění
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760686"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="89ae2-102">Problémy s připojením aplikace SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="89ae2-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="89ae2-103">Pokud aplikace SharePoint Designer dochází k problémy s připojením k webům služby SharePoint, prosím o následující společné řešení.</span><span class="sxs-lookup"><span data-stu-id="89ae2-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please attempt the following common solutions.</span></span>

<span data-ttu-id="89ae2-104">Krok 1: Ověřte aktualizaci SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="89ae2-104">Step 1: Verify SharePoint Designer is updated.</span></span>

- [<span data-ttu-id="89ae2-105">Aplikace SharePoint Designer 2013</span><span class="sxs-lookup"><span data-stu-id="89ae2-105">SharePoint Designer 2013</span></span>](https://www.microsoft.com/download/details.aspx?id=35491)

- [<span data-ttu-id="89ae2-106">Aplikace SharePoint Designer Service Pack 1 (SP1)</span><span class="sxs-lookup"><span data-stu-id="89ae2-106">SharePoint Designer Service Pack 1 (SP1)</span></span>](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [<span data-ttu-id="89ae2-107">Aktualizace SharePoint Designer 2013 (KB3114721)</span><span class="sxs-lookup"><span data-stu-id="89ae2-107">Update for SharePoint Designer 2013 (KB3114721)</span></span>](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

<span data-ttu-id="89ae2-108">Krok 2: Vymazat místní mezipaměť souborů</span><span class="sxs-lookup"><span data-stu-id="89ae2-108">Step 2: Clear the local cache files</span></span>

- <span data-ttu-id="89ae2-109">Zavřete aplikaci SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="89ae2-109">Close SharePoint Designer 2013.</span></span>

- <span data-ttu-id="89ae2-110">Vyhledejte následující složky odeberte soubory uložené v mezipaměti místního počítače.</span><span class="sxs-lookup"><span data-stu-id="89ae2-110">On the local computer, browse to the following folders to remove cached files.</span></span>

- <span data-ttu-id="89ae2-111">Klepněte na tlačítko Start, spustit a odstranit všechny soubory nalezeny v každé pod umístění.</span><span class="sxs-lookup"><span data-stu-id="89ae2-111">Click Start, Run and delete all files found under each of the below locations.</span></span>

<span data-ttu-id="89ae2-112">%APPDATA%\Microsoft\Web server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="89ae2-112">%APPDATA%\Microsoft\Web Server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

<span data-ttu-id="89ae2-113">Otevřete aplikaci SharePoint Designer 2013 a zadejte účet zjistíte, zda funguje.</span><span class="sxs-lookup"><span data-stu-id="89ae2-113">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="89ae2-114">Krok 3: [Povolit moderní ověřování Office 2013 na zařízení systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="89ae2-114">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span></span>

<span data-ttu-id="89ae2-115">Krok 4: Administrators bude nutné povolit vlastní skript k povolení připojení aplikace SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="89ae2-115">Step 4: Administrators will need to Allow Custom Script to allow the SharePoint Designer connection.</span></span>

<span data-ttu-id="89ae2-116">Podrobné kroky, příklady a důležité informace naleznete v [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="89ae2-116">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


