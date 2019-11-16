---
title: Dynamics 365-chybné zobrazení řídicího panelu v Dynamics 365 sjednocené rozhraní
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 3d7258bdd7366f679b048e93926ab7dfe0b956d9
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "36528544"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="e9c41-102">Chybné zobrazení řídicího panelu ve sjednoceném rozhraní Dynamics 365</span><span class="sxs-lookup"><span data-stu-id="e9c41-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="e9c41-103">Existuje několik důvodů, proč se může zobrazit jiný řídicí panel než ten, který očekáváte:</span><span class="sxs-lookup"><span data-stu-id="e9c41-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="e9c41-104">Uživatel nastavil výchozí řídicí panel uživatele.</span><span class="sxs-lookup"><span data-stu-id="e9c41-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="e9c41-105">Obvykle lze určit, že výchozí řídicí panel uživatele je nastaven v případě, že se v příkazovém řádku řídicího panelu nezobrazí tlačítko **nastavit jako výchozí** .</span><span class="sxs-lookup"><span data-stu-id="e9c41-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="e9c41-106">Výchozí řídicí panel uživatele přepíše všechny ostatní výchozí řídicí panely, a to i v případě, že výchozí řídicí panel uživatele není v aktuální aplikaci.</span><span class="sxs-lookup"><span data-stu-id="e9c41-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="e9c41-107">Chcete-li zrušit nastavení výchozího řídicího panelu, použijte následující zástupné řešení.</span><span class="sxs-lookup"><span data-stu-id="e9c41-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="e9c41-108">Vytvoří nový osobní řídicí panel.</span><span class="sxs-lookup"><span data-stu-id="e9c41-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="e9c41-109">Nastaví nový řídicí panel jako výchozí uživatel.</span><span class="sxs-lookup"><span data-stu-id="e9c41-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="e9c41-110">Odstraňte tento řídicí panel.</span><span class="sxs-lookup"><span data-stu-id="e9c41-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="e9c41-111">Řídicí panel je nastaven v mapě webu</span><span class="sxs-lookup"><span data-stu-id="e9c41-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="e9c41-112">Můžete nastavit výchozí řídicí panel organizace výběrem řídicího panelu a zvolením možnosti nastavit jako výchozí v části vlastní nastavení systému.</span><span class="sxs-lookup"><span data-stu-id="e9c41-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="e9c41-113">Avšak řídicí panel definovaný v Návrháři mapy webu bude mít přednost před tímto řídicím panelem, pokud k němu má přístup uživatel.</span><span class="sxs-lookup"><span data-stu-id="e9c41-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="e9c41-114">Chcete-li, aby uživatelé viděli řídicí panel, který jste nastavili jako výchozí nastavení organizace, můžete buď:</span><span class="sxs-lookup"><span data-stu-id="e9c41-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="e9c41-115">Nastavit tento řídicí panel v mapě webu</span><span class="sxs-lookup"><span data-stu-id="e9c41-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="e9c41-116">Odebrání přístupu k řídicím panelům definovaným v mapě webu pro tyto uživatele</span><span class="sxs-lookup"><span data-stu-id="e9c41-116">Remove access to the sitemap defined dashboard for those users</span></span>
