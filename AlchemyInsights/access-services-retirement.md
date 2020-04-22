---
title: Přístup ke službě odchodu do důchodu
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 977bd5887ef58b328463a9befcd6b47ac55f5a85
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687251"
---
# <a name="access-services-retirement"></a><span data-ttu-id="24d5f-102">Přístup ke službě odchodu do důchodu</span><span class="sxs-lookup"><span data-stu-id="24d5f-102">Access services retirement</span></span>

<span data-ttu-id="24d5f-103">Jak jsme původně oznámili v MC97576, v březnu 2017, a pokračovali v komunikaci v uplynulém roce, přístupové služby jsou vyřazeny.</span><span class="sxs-lookup"><span data-stu-id="24d5f-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired.</span></span> <span data-ttu-id="24d5f-104">Další fází tohoto procesu bude odebrání webových databází aplikace Access, které používají seznamy služby SharePoint jako základní úložiště dat.</span><span class="sxs-lookup"><span data-stu-id="24d5f-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="24d5f-105">**Jak to ovlivní mě?**</span><span class="sxs-lookup"><span data-stu-id="24d5f-105">**How does this affect me?**</span></span>

<span data-ttu-id="24d5f-106">Od června 2019 přestaneme vytvářet nové databáze Accessu v SharePointu Online a do dubna 2020 službu a všechny zbývající aplikace vypneme.</span><span class="sxs-lookup"><span data-stu-id="24d5f-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="24d5f-107">**Co musím udělat, abych se na tuto změnu připravil?**</span><span class="sxs-lookup"><span data-stu-id="24d5f-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="24d5f-108">Doporučujeme vytvořit plán přechodu pro webové databáze accessu vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="24d5f-108">We encourage you to create a transition plan for your organization's Access web databases.</span></span> <span data-ttu-id="24d5f-109">Správci můžou pomocí [skeneru aplikací pro SharePoint Access](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) získat inventář aplikací pro Access, které weby používají.</span><span class="sxs-lookup"><span data-stu-id="24d5f-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="24d5f-110">Data webových databází aplikace Access lze migrovat několika způsoby:</span><span class="sxs-lookup"><span data-stu-id="24d5f-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="24d5f-111">Import do místní databáze aplikace Access (. ACCDB) nebo do souboru aplikace Excel.</span><span class="sxs-lookup"><span data-stu-id="24d5f-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="24d5f-112">Doporučujeme také prozkoumat Microsoft PowerApps jako alternativní platformu pro vytvoření bezkódových obchodních řešení pro web a mobilní zařízení.</span><span class="sxs-lookup"><span data-stu-id="24d5f-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>