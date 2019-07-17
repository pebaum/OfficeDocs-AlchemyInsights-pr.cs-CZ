---
title: Dynamics 365 - chybný řídicí panel se zobrazí v rozhraní Unified Dynamics 365
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 6edf6fbae0174f3fa4d635c7a99e7daae1243b60
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/16/2019
ms.locfileid: "35747219"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="61c51-102">Chybný řídicí panel se zobrazí v rozhraní unified Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="61c51-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="61c51-103">Existuje několik důvodů, proč se může zobrazit jiný řídicí panel než ten, který můžete očekávat:</span><span class="sxs-lookup"><span data-stu-id="61c51-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="61c51-104">Uživatel nastavil výchozí uživatelský řídicí panel</span><span class="sxs-lookup"><span data-stu-id="61c51-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="61c51-105">Obvykle můžete identifikovat uživatele výchozí řídicí panel je nastavena, je-li na tlačítko **Nastavit jako výchozí** řídicí panel panel příkazů nezobrazuje.</span><span class="sxs-lookup"><span data-stu-id="61c51-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="61c51-106">Uživatelský řídicí panel Výchozí přepíše všechny ostatní výchozí řídicí panely, i když není v aktuální aplikaci app uživatele výchozí řídicí panel.</span><span class="sxs-lookup"><span data-stu-id="61c51-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="61c51-107">Použijte následující řešení Chcete-li zrušit jejich výchozího řídicího panelu.</span><span class="sxs-lookup"><span data-stu-id="61c51-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="61c51-108">Vytvořte nový osobní řídicí panel.</span><span class="sxs-lookup"><span data-stu-id="61c51-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="61c51-109">Nastavte tento nový řídicí panel jako výchozí nastavení uživatele.</span><span class="sxs-lookup"><span data-stu-id="61c51-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="61c51-110">Odstraňte tento řídicí panel.</span><span class="sxs-lookup"><span data-stu-id="61c51-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="61c51-111">Řídicí panel je nastavena v mapě stránek</span><span class="sxs-lookup"><span data-stu-id="61c51-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="61c51-112">Mohou být nastavena výchozí řídicí panel organizace řídicího panelu vyberete a zvolíte "Nastavit jako výchozí" v části vlastní nastavení systému.</span><span class="sxs-lookup"><span data-stu-id="61c51-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="61c51-113">Ale podle mapy webu Návrhář řídicího panelu má přednost tento řídicí panel, pokud má uživatel přístup k němu.</span><span class="sxs-lookup"><span data-stu-id="61c51-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="61c51-114">Pokud chcete, aby uživatelé řídicího panelu, které jste nastavili jako výchozí organizace naleznete v tématu, můžete buď:</span><span class="sxs-lookup"><span data-stu-id="61c51-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="61c51-115">Nastavit tento řídicí panel v mapě stránek</span><span class="sxs-lookup"><span data-stu-id="61c51-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="61c51-116">Odebrat přístup k řídicího panelu definované mapy webu pro uživatele</span><span class="sxs-lookup"><span data-stu-id="61c51-116">Remove access to the sitemap defined dashboard for those users</span></span>
