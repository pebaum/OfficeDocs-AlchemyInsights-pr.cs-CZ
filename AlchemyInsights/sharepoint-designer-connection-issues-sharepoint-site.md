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
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511537"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="53ac2-102">Problémy s připojením aplikace SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="53ac2-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="53ac2-103">Pokud se SharePoint Designer potýká s problémy s připojením k webům Služby SharePoint, vyzkoušejte následující běžná řešení.</span><span class="sxs-lookup"><span data-stu-id="53ac2-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="53ac2-104">Krok 1: Ověřte, zda je SharePoint Designer 2013 aktualizován [aktualizací SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) a [aktualizací ze srpna 2016 pro SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="53ac2-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="53ac2-105">Krok 2: Vymazání místních souborů mezipaměti:</span><span class="sxs-lookup"><span data-stu-id="53ac2-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="53ac2-106">Zavřít SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="53ac2-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="53ac2-107">V místním počítači odeberte všechny soubory nalezené v každé z následujících složek.</span><span class="sxs-lookup"><span data-stu-id="53ac2-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="53ac2-108">%APPDATA%\Microsoft\Rozšíření webového serveru\Mezipaměť</span><span class="sxs-lookup"><span data-stu-id="53ac2-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="53ac2-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="53ac2-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="53ac2-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="53ac2-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="53ac2-111">Otevřete SharePoint Designer 2013 a znovu zadejte účet, abyste zjistili, jestli funguje.</span><span class="sxs-lookup"><span data-stu-id="53ac2-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="53ac2-112">Krok 3: [Povolení moderního ověřování pro Office 2013 na zařízeních s Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="53ac2-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>

<span data-ttu-id="53ac2-113">Krok 4: Správci budou muset **povolit vlastní skript** v nastavení Centra pro správu SharePointu, aby povolili připojení k SharePoint Designeru.</span><span class="sxs-lookup"><span data-stu-id="53ac2-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="53ac2-114">Další informace najdete [v tématu Povolení nebo zabránění vlastnímu skriptu.](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)</span><span class="sxs-lookup"><span data-stu-id="53ac2-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>


