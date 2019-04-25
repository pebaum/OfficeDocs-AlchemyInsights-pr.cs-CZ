---
title: Poradce při potížích s zprávy o odepření přístupu
ms.author: kaarins
author: kaarins
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: f1a4803838b6511ef4fe7f03cafa4aa13b3c9734
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420693"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="bdaca-102">Poradce při potížích s zprávy o odepření přístupu</span><span class="sxs-lookup"><span data-stu-id="bdaca-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="bdaca-103">Pokud někdo máte zprávu "Přístup byl odepřen" ve sdílené složce, správce kolekce webů může být povoleno "omezený přístup uživateli oprávnění režim uzamčení."</span><span class="sxs-lookup"><span data-stu-id="bdaca-103">If someone got an "Access Denied" message to a shared folder, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="bdaca-104">Chcete-li tuto funkci vypnout:</span><span class="sxs-lookup"><span data-stu-id="bdaca-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="bdaca-105">Přejděte na web, klepněte na ikonu nastavení a potom klepněte na tlačítko **Nastavení webu**.</span><span class="sxs-lookup"><span data-stu-id="bdaca-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="bdaca-106">V části **Správa kolekce webů**klepněte na možnost **Funkce kolekce webů**.</span><span class="sxs-lookup"><span data-stu-id="bdaca-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="bdaca-107">**Režim uzamčení oprávnění uživatele omezený přístup**klepněte na tlačítko **deaktivovat**.</span><span class="sxs-lookup"><span data-stu-id="bdaca-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="bdaca-108">Zpráva o odepření přístupu může dojít také u sdílené složky Web je web publikování.</span><span class="sxs-lookup"><span data-stu-id="bdaca-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="bdaca-109">Informace viz [Při přístupu ke sdílené složce byl odepřen přístup](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="bdaca-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="bdaca-110">Pokud někdo obdržel zprávu "Přístup byl odepřen" při pokusu o zobrazení žádosti o přístup, uživatel musí být přidán jako správce kolekce webů nebo členem skupiny Vlastníci webu.</span><span class="sxs-lookup"><span data-stu-id="bdaca-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="bdaca-111">Další informace naleznete v tématu [Přístup k seznamu požadavků na přístup odepřen](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="bdaca-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="bdaca-112">Poté, co byly odebrány ze služby Active Directory v prostorách a přidána zpět, uživatel obdržel zprávu "Přístup byl odepřen", naleznete v tématu [Přístup odepřen při uživatelský účet je synchronizované s Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="bdaca-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

