---
title: Poradce při potížích se zprávami o odepření přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 1930edcfd14acc48ea77b66e2793654a3e6332cc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759793"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="90770-102">Poradce při potížích se zprávami o odepření přístupu</span><span class="sxs-lookup"><span data-stu-id="90770-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="90770-103">Pokud někdo dostal zprávu "Přístup byl odepřen" do sdílené složky v SharePointu, správce kolekce webů mohl povolit režim uzamčení uživatelských oprávnění s omezeným přístupem.</span><span class="sxs-lookup"><span data-stu-id="90770-103">If someone got an "Access Denied" message to a shared folder in SharePoint, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="90770-104">Vypnutí:</span><span class="sxs-lookup"><span data-stu-id="90770-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="90770-105">Přejděte na web, klikněte na ikonu Nastavení a potom klikněte na **Nastavení webu**.</span><span class="sxs-lookup"><span data-stu-id="90770-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="90770-106">V části **Správa kolekce webů**klikněte na **Funkce kolekce webů**.</span><span class="sxs-lookup"><span data-stu-id="90770-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="90770-107">Vedle **režimu uzamčení uživatelských oprávnění s omezeným přístupem**klepněte na tlačítko **Deaktivovat**.</span><span class="sxs-lookup"><span data-stu-id="90770-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="90770-108">Zpráva o odepření přístupu může dojít také pro sdílené složky, pokud je web webem publikování.</span><span class="sxs-lookup"><span data-stu-id="90770-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="90770-109">Další informace naleznete [v tématu Access Denied when access ing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="90770-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="90770-110">Pokud někdo dostal zprávu "Přístup byl odepřen" při pokusu o zobrazení žádostí o přístup, uživatel musí být přidán jako správce kolekce webů nebo jako člen skupiny Vlastníci pro web.</span><span class="sxs-lookup"><span data-stu-id="90770-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="90770-111">Další informace naleznete v [tématu Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="90770-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="90770-112">Pokud se uživateli po odebrání ze služby Active Directory a následném přidání zpět zobrazí zpráva "Přístup byl odepřen" a poté byl přidán zpět, přečtěte si [informace o tom, že je při synchronizaci uživatelského účtu se systémem Microsoft 365 odepřen přístup.](https://go.microsoft.com/fwlink/?linkid=2004318)</span><span class="sxs-lookup"><span data-stu-id="90770-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

