---
title: 932 AADConnect inovace
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 932
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 0bbb847bb1381330065ebba6e109795908b06490
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30778735"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="76c08-102">Inovace Azure AD připojit</span><span class="sxs-lookup"><span data-stu-id="76c08-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="76c08-103">Standardně je povoleno automatické inovace pro Azure AD připojit, což pomůže zajistit, že používáte nejnovější verzi.</span><span class="sxs-lookup"><span data-stu-id="76c08-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="76c08-104">Chcete-li ověřit nastavení automatického upgradu, použijte rutiny **Get-ADSyncAutoUpgrade** v prostředí PowerShell Azure AD.</span><span class="sxs-lookup"><span data-stu-id="76c08-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="76c08-105">Rutiny vrátí jednu z následujících hodnot:</span><span class="sxs-lookup"><span data-stu-id="76c08-105">The cmdlet will return one of following values:</span></span> 
  
- <span data-ttu-id="76c08-106">**Povoleno**: je povolen automatický upgrade.</span><span class="sxs-lookup"><span data-stu-id="76c08-106">**Enabled**: Automatic upgrade is enabled.</span></span> 
    
- <span data-ttu-id="76c08-107">**Zakázáno**: automatický upgrade je zakázáno.</span><span class="sxs-lookup"><span data-stu-id="76c08-107">**Disabled**: Automatic upgrade is disabled.</span></span> 
    
- <span data-ttu-id="76c08-108">**Suspended**: systém je již oprávněni přijímat automatické upgrady.</span><span class="sxs-lookup"><span data-stu-id="76c08-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="76c08-109">Nelze nastavit tuto hodnotu; systém je nastaven.</span><span class="sxs-lookup"><span data-stu-id="76c08-109">You can't configure this value; it's set by the system.</span></span> 
    
<span data-ttu-id="76c08-110">Další informace naleznete v tématu [automatické inovace](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="76c08-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>
  
<span data-ttu-id="76c08-111">Chcete-li stáhnout nejnovější verzi Azure AD připojit, přejděte na [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span><span class="sxs-lookup"><span data-stu-id="76c08-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
  

