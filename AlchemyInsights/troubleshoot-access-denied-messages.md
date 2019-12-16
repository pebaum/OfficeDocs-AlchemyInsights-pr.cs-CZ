---
title: Odstraňování problémů se zprávami o odepření přístupu
ms.author: pebaum
author: pebaum
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 05d12aee49b449e8a29e84021b41298fb9983859
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050698"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="875a6-102">Odstraňování problémů se zprávami o odepření přístupu</span><span class="sxs-lookup"><span data-stu-id="875a6-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="875a6-103">Pokud někdo dostal zprávu o odepření přístupu do sdílené složky ve službě SharePoint, mohl správce kolekce webů povolit režim uzamčení oprávnění omezený přístup.</span><span class="sxs-lookup"><span data-stu-id="875a6-103">If someone got an "Access Denied" message to a shared folder in SharePoint, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="875a6-104">Chcete-li tuto funkci vypnout:</span><span class="sxs-lookup"><span data-stu-id="875a6-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="875a6-105">Přejděte na web, klepněte na ikonu nastavení a potom klepněte na tlačítko **Nastavení webu**.</span><span class="sxs-lookup"><span data-stu-id="875a6-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="875a6-106">V části **Správa kolekce webů**klepněte na možnost **kolekce webů**.</span><span class="sxs-lookup"><span data-stu-id="875a6-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="875a6-107">Vedle **režimu uzamčení přístupových oprávnění omezený přístup**klepněte na tlačítko **deaktivovat**.</span><span class="sxs-lookup"><span data-stu-id="875a6-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="875a6-108">Pokud je web webem publikování, může se u sdílených složek vyskytnout také zpráva přístup odepřen.</span><span class="sxs-lookup"><span data-stu-id="875a6-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="875a6-109">Informace naleznete v tématu [přístup odepřen při přístupu ke sdílené složce](https://go.microsoft.com/fwlink/?linkid=2004317).</span><span class="sxs-lookup"><span data-stu-id="875a6-109">For info, see [Access Denied when accessing a shared folder](https://go.microsoft.com/fwlink/?linkid=2004317).</span></span>
  
<span data-ttu-id="875a6-110">Pokud má někdo při pokusu o zobrazení žádostí o přístup zprávu "přístup byl odepřen", musí být uživatel přidán buď jako správce kolekce webů, nebo jako člen skupiny Vlastníci daného webu.</span><span class="sxs-lookup"><span data-stu-id="875a6-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="875a6-111">Další informace naleznete v tématu [přístup odepřen pro přístup k seznamu požadavků](https://go.microsoft.com/fwlink/?linkid=2004220).</span><span class="sxs-lookup"><span data-stu-id="875a6-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="875a6-112">Pokud se uživateli po odebrání z prostředí služby Active Directory zobrazí zpráva "přístup byl odepřen" a potom je znovu přidána zpět, naleznete informace v tématu [přístup odepřen při synchronizaci uživatelského účtu se sadou Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="875a6-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Office 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

