---
title: Přístup služby odchod do důchodu
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 5f171050479f34077f3dc155bec40437f86b84c0
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35359332"
---
# <a name="access-services-retirement"></a><span data-ttu-id="31ff0-102">Přístup služby odchod do důchodu</span><span class="sxs-lookup"><span data-stu-id="31ff0-102">Access services retirement</span></span>

<span data-ttu-id="31ff0-103">Původně oznámené v MC97576, v březnu 2017 a komunikuje v minulém roce i nadále přístup ke službě jsou vyřazovaného ze služeb Office 365.</span><span class="sxs-lookup"><span data-stu-id="31ff0-103">As we originally announced in MC97576, in March 2017, and continued to communicate over the past year Access Services are being retired from Office 365.</span></span> <span data-ttu-id="31ff0-104">Další fáze v tomto procesu bude odebrání webových databází Access jako jejich podkladové úložiště dat použít seznamy služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="31ff0-104">The next phase in this process will be the removal of Access Web Databases that use SharePoint lists as their underlying data storage.</span></span>

<span data-ttu-id="31ff0-105">**Jak mě to ovlivňuje?**</span><span class="sxs-lookup"><span data-stu-id="31ff0-105">**How does this affect me?**</span></span>

<span data-ttu-id="31ff0-106">Od června 2019, jsme zastaví vytváření nové databáze aplikace Access v Online služby SharePoint a vypněte službu a všechny zbývající apps do roku 2020 dne.</span><span class="sxs-lookup"><span data-stu-id="31ff0-106">Starting June 2019, we will stop creation of new Access databases in SharePoint Online and shut down the service and any remaining apps by April 2020.</span></span>

<span data-ttu-id="31ff0-107">**Co je třeba udělat, aby tuto změnu připravit?**</span><span class="sxs-lookup"><span data-stu-id="31ff0-107">**What do I need to do to prepare for this change?**</span></span>

<span data-ttu-id="31ff0-108">Doporučujeme vytvořit plán přechodu pro databáze web Access vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="31ff0-108">We encourage you to create a transition plan for your organization’s Access web databases.</span></span> <span data-ttu-id="31ff0-109">Admins můžete získat soupis přístup aplikací, které používají servery [přístupu služby SharePoint app skener](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) .</span><span class="sxs-lookup"><span data-stu-id="31ff0-109">Admins can use the [SharePoint Access app scanner](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) to obtain an inventory of the Access apps that sites are using.</span></span>

<span data-ttu-id="31ff0-110">K migraci dat databáze webového přístupu několika způsoby:</span><span class="sxs-lookup"><span data-stu-id="31ff0-110">There are several ways to migrate Access web databases data:</span></span>

- <span data-ttu-id="31ff0-111">Import do místní databáze aplikace Access (. ACCDB) nebo souboru aplikace Excel.</span><span class="sxs-lookup"><span data-stu-id="31ff0-111">Importing to a local Access database (.ACCDB) or to an Excel file.</span></span>
- <span data-ttu-id="31ff0-112">Doporučujeme také procházení Microsoft PowerApps jako alternativní platforma pro vytvoření bez kódu obchodní řešení pro web a mobilní zařízení.</span><span class="sxs-lookup"><span data-stu-id="31ff0-112">We also recommend exploring Microsoft PowerApps as an alternative platform to create no-code business solutions for web and mobile devices.</span></span>