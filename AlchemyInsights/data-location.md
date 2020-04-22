---
title: Umístění dat
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: c769c17796d805f88afb4d5b32adb7d4a9bb3ce0
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/21/2020
ms.locfileid: "43655275"
---
# <a name="data-location"></a><span data-ttu-id="5e93f-102">Umístění dat</span><span class="sxs-lookup"><span data-stu-id="5e93f-102">Data location</span></span>

<span data-ttu-id="5e93f-103">Umístění vašeho tenanta můžete zobrazit v Centru pro správu nebo připojením k Exchange Online přes PowerShell.</span><span class="sxs-lookup"><span data-stu-id="5e93f-103">You can view the location of your tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="5e93f-104">**Centrum pro správu:**</span><span class="sxs-lookup"><span data-stu-id="5e93f-104">**Admin center:**</span></span>
1. <span data-ttu-id="5e93f-105">Přihlaste se do [Centra pro správu](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="5e93f-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="5e93f-106">Vyberte **nastavení** > **profilu organizace**.</span><span class="sxs-lookup"><span data-stu-id="5e93f-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="5e93f-107">V části **Umístění dat**vyberte **Zobrazit podrobnosti**.</span><span class="sxs-lookup"><span data-stu-id="5e93f-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="5e93f-108">**Powershell:**</span><span class="sxs-lookup"><span data-stu-id="5e93f-108">**PowerShell:**</span></span>
1. <span data-ttu-id="5e93f-109">Připojte se k Exchange Online pomocí prostředí Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="5e93f-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="5e93f-110">Spusťte rutinu [Get-OrganizationalUnit,](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) chcete-li zobrazit seznam vlastností vašeho klienta.</span><span class="sxs-lookup"><span data-stu-id="5e93f-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant's properties.</span></span> 
3. <span data-ttu-id="5e93f-111">Podívejte se na majetek Organizace id.</span><span class="sxs-lookup"><span data-stu-id="5e93f-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="5e93f-112">Pokud máte umístění dat pro EXO a SPO, můžete určit umístění dat pro další služby, které můžete použít z [místa, kde se vaše data nacházejí](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="5e93f-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>