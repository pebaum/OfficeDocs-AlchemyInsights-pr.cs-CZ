---
title: 932 Inovace služby AADConnect
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "932"
- "1300025"
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: fcc5fddb5cfd15407d0533449035317d187931ed
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766486"
---
# <a name="upgrade-azure-ad-connect"></a><span data-ttu-id="ad291-102">Upgrade Azure AD Connect</span><span class="sxs-lookup"><span data-stu-id="ad291-102">Upgrade Azure AD Connect</span></span>

<span data-ttu-id="ad291-103">Ve výchozím nastavení je pro Azure AD Connect povolen automatický upgrade, který pomáhá zajistit, že používáte nejnovější verzi.</span><span class="sxs-lookup"><span data-stu-id="ad291-103">By default, automatic upgrade is enabled for Azure AD Connect, which helps to ensure you're running the latest version.</span></span> <span data-ttu-id="ad291-104">Chcete-li ověřit nastavení automatického upgradu, použijte rutinu **Get-ADSyncAutoUpgrade** v prostředí Azure AD PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ad291-104">To verify the automatic upgrade settings, use the **Get-ADSyncAutoUpgrade** cmdlet in Azure AD PowerShell.</span></span> <span data-ttu-id="ad291-105">Rutina vrátí jednu z následujících hodnot:</span><span class="sxs-lookup"><span data-stu-id="ad291-105">The cmdlet will return one of following values:</span></span>

- <span data-ttu-id="ad291-106">**Povoleno**: Automatický upgrade je povolen.</span><span class="sxs-lookup"><span data-stu-id="ad291-106">**Enabled**: Automatic upgrade is enabled.</span></span>

- <span data-ttu-id="ad291-107">**Zakázáno**: Automatický upgrade je zakázán.</span><span class="sxs-lookup"><span data-stu-id="ad291-107">**Disabled**: Automatic upgrade is disabled.</span></span>

- <span data-ttu-id="ad291-108">**Pozastaveno**: Systém již není způsobilý pro automatické upgrady.</span><span class="sxs-lookup"><span data-stu-id="ad291-108">**Suspended**: The system is no longer eligible to receive automatic upgrades.</span></span> <span data-ttu-id="ad291-109">Tuto hodnotu nelze nakonfigurovat. Je to nastaveno systémem.</span><span class="sxs-lookup"><span data-stu-id="ad291-109">You can't configure this value; it's set by the system.</span></span>

<span data-ttu-id="ad291-110">Další informace naleznete v [tématu Automatický upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span><span class="sxs-lookup"><span data-stu-id="ad291-110">For more information, see [Automatic upgrade](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).</span></span>

<span data-ttu-id="ad291-111">Pokud chcete stáhnout nejnovější verzi Služby [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594)Azure AD Connect, přejděte na .</span><span class="sxs-lookup"><span data-stu-id="ad291-111">To download the latest version of Azure AD Connect, go to [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).</span></span>
