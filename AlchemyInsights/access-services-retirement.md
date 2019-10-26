---
title: Přístup ke službám v důchodu
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 197366882468ebc87fc26f2fe2733371790d1871
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36747777"
---
# <a name="access-services-retirement"></a><span data-ttu-id="8d974-102">Přístup ke službám v důchodu</span><span class="sxs-lookup"><span data-stu-id="8d974-102">Access services retirement</span></span>

<span data-ttu-id="8d974-103">Jak jsme původně oznámili v roce MC97576, v březnu 2017 a pokračovali v komunikaci v uplynulém roce služby Access Services jsou vyřazeny z úřadu 365.</span><span class="sxs-lookup"><span data-stu-id="8d974-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired from Office 365.</span></span> <span data-ttu-id="8d974-104">Další fází tohoto procesu bude odebrání webových databází aplikace Access, které používají seznamy služby SharePoint jako své podkladové úložiště dat.</span><span class="sxs-lookup"><span data-stu-id="8d974-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="8d974-105">**Jak mě to ovlivňuje?**</span><span class="sxs-lookup"><span data-stu-id="8d974-105">**How does this affect me?**</span></span>

<span data-ttu-id="8d974-106">Počínaje červnem 2019 se zastaví vytváření nových databází aplikace Access na webu služby SharePoint Online a ukončení služby a všech zbývajících aplikací do dubna 2020.</span><span class="sxs-lookup"><span data-stu-id="8d974-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="8d974-107">**Co je třeba udělat, aby se připravila na tuto změnu?**</span><span class="sxs-lookup"><span data-stu-id="8d974-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="8d974-108">Doporučujeme vytvořit plán přechodu pro webové databáze aplikace Access vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="8d974-108">We encourage you to create a transition plan for your organization’s Access web databases.</span></span> <span data-ttu-id="8d974-109">Správci mohou pomocí [skeneru aplikací služby SharePoint Access](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) získat soupis aplikací Access, které weby používají.</span><span class="sxs-lookup"><span data-stu-id="8d974-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="8d974-110">Data webových databází aplikace Access lze migrovat několika způsoby:</span><span class="sxs-lookup"><span data-stu-id="8d974-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="8d974-111">Import do místní databáze aplikace Access (. ACCDB) nebo do souboru aplikace Excel.</span><span class="sxs-lookup"><span data-stu-id="8d974-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="8d974-112">Doporučujeme také prozkoumat aplikaci Microsoft PowerApps jako alternativní platformu pro tvorbu bezkódových podnikových řešení pro webové a mobilní zařízení.</span><span class="sxs-lookup"><span data-stu-id="8d974-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>