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
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 8038d5ef768d6ee228db7d038ad71d926f4047f3
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29937937"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="d7d04-102">Inovace Azure AD připojit</span><span class="sxs-lookup"><span data-stu-id="d7d04-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="d7d04-p101">Standardně je povoleno automatické inovace pro Azure AD připojit, což pomůže zajistit, že používáte nejnovější verzi. Chcete-li ověřit nastavení automatického upgradu, použijte rutiny **Get-ADSyncAutoUpgrade** v prostředí PowerShell Azure AD. Rutiny vrátí jednu z následujících hodnot:</span><span class="sxs-lookup"><span data-stu-id="d7d04-p101">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version. To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell. The cmdlet will return one of following values:</span></span> 
  
- <span data-ttu-id="d7d04-106">**Povoleno**: je povolen automatický upgrade.</span><span class="sxs-lookup"><span data-stu-id="d7d04-106">**Enabled**: Automatic upgrade is enabled.</span></span> 
    
- <span data-ttu-id="d7d04-107">**Zakázáno**: automatický upgrade je zakázáno.</span><span class="sxs-lookup"><span data-stu-id="d7d04-107">**Disabled**: Automatic upgrade is disabled.</span></span> 
    
- <span data-ttu-id="d7d04-p102">**Suspended**: systém je již oprávněni přijímat automatické upgrady. Nelze nastavit tuto hodnotu; systém je nastaven.</span><span class="sxs-lookup"><span data-stu-id="d7d04-p102">**Suspended**: The system is no longer eligible to receive automatic upgrades. You can't configure this value; it's set by the system.</span></span> 
    
<span data-ttu-id="d7d04-110">Další informace naleznete v tématu [automatické inovace](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="d7d04-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>
  
<span data-ttu-id="d7d04-111">Chcete-li stáhnout nejnovější verzi Azure AD připojit, přejděte na [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span><span class="sxs-lookup"><span data-stu-id="d7d04-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
  

