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
ms.openlocfilehash: 0e683c8266d425be95e87c590d4cb5d56108721a
ms.sourcegitcommit: 71978e2bb779b5955fd113f84512b83321b26912
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/26/2019
ms.locfileid: "37207254"
---
# <a name="data-location"></a><span data-ttu-id="20925-102">Umístění dat</span><span class="sxs-lookup"><span data-stu-id="20925-102">Data location</span></span>

<span data-ttu-id="20925-103">Umístění klienta sady Office 365 můžete zobrazit v centru pro správu nebo připojením k serveru Exchange Online prostřednictvím prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="20925-103">You can view the location of your Office 365 tenant in the admin center or by connecting to Exchange Online via PowerShell.</span></span>


<span data-ttu-id="20925-104">**Centrum pro správu:**</span><span class="sxs-lookup"><span data-stu-id="20925-104">**Admin center:**</span></span>
1. <span data-ttu-id="20925-105">Přihlaste se do [centra pro správu](https://admin.microsoft.com/Adminportal/Home).</span><span class="sxs-lookup"><span data-stu-id="20925-105">Log in to the [admin center](https://admin.microsoft.com/Adminportal/Home).</span></span>
2. <span data-ttu-id="20925-106">Vyberte **Nastavení** > **profilu organizace**.</span><span class="sxs-lookup"><span data-stu-id="20925-106">Select **Settings** > **Organization profile**.</span></span>
3. <span data-ttu-id="20925-107">V části **umístění dat**vyberte **Podrobnosti zobrazení**.</span><span class="sxs-lookup"><span data-stu-id="20925-107">Under **Data location**, select **View details**.</span></span>


<span data-ttu-id="20925-108">**Powershell:**</span><span class="sxs-lookup"><span data-stu-id="20925-108">**PowerShell:**</span></span>
1. <span data-ttu-id="20925-109">Připojení k serveru Exchange Online pomocí prostředí Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="20925-109">Connect to Exchange Online by using Windows PowerShell.</span></span>
2. <span data-ttu-id="20925-110">Spuštěním rutiny [Get-OrganizationalUnit](https://docs.microsoft.com/en-us/powershell/module/exchange/active-directory/get-organizationalunit) zobrazíte seznam vlastností vašeho klienta.</span><span class="sxs-lookup"><span data-stu-id="20925-110">Execute the [Get-OrganizationalUnit](https://docs.microsoft.com/en-us/powershell/module/exchange/active-directory/get-organizationalunit) cmdlet to display a list of your tenant’s properties.</span></span> 
3. <span data-ttu-id="20925-111">Podívejte se na vlastnost OrganizationId.</span><span class="sxs-lookup"><span data-stu-id="20925-111">Look at the OrganizationId property.</span></span>

<span data-ttu-id="20925-112">Pokud máte datové umístění pro EXO a SPO, můžete určit umístění dat pro jiné služby, které můžete použít z [místa, kde jsou data umístěna](https://products.office.com/where-is-your-data-located).</span><span class="sxs-lookup"><span data-stu-id="20925-112">When you have the data location for EXO and SPO, you can determine the data location for other services you may use from [Where your data is located](https://products.office.com/where-is-your-data-located).</span></span>