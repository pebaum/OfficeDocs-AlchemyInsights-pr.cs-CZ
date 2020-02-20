---
title: Zásady AllowSelfServicePurchase nelze nastavit ani zobrazit.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3526"
ms.openlocfilehash: 587a05cccbc71a970d4bd7723bff0df0c3b64ccc
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158554"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a><span data-ttu-id="8d665-102">Zásady AllowSelfServicePurchase nelze nastavit ani zobrazit.</span><span class="sxs-lookup"><span data-stu-id="8d665-102">Unable to set or view the AllowSelfServicePurchase policy</span></span>

<span data-ttu-id="8d665-103">Při pokusu o nastavení nebo zobrazení zásad AllowSelfServicePurchase se zobrazí následující chybová zpráva:</span><span class="sxs-lookup"><span data-stu-id="8d665-103">When attempting to set or view the AllowSelfServicePurchase policy, you receive the following error message:</span></span>

<span data-ttu-id="8d665-104">*HandleError : Nepodařilo se načíst zásady produktu s PolicyId 'AllowSelfServicePurchase', ErrorMessage - Základní připojení bylo uzavřeno: Při odesílání došlo k neočekávané chybě.*</span><span class="sxs-lookup"><span data-stu-id="8d665-104">*HandleError : Failed to retrieve product policy with PolicyId 'AllowSelfServicePurchase', ErrorMessage - The underlying connection was closed: An unexpected error occurred on a send.*</span></span>

<span data-ttu-id="8d665-105">To může být způsobeno starší verzí zabezpečení transportní vrstvy (TLS).</span><span class="sxs-lookup"><span data-stu-id="8d665-105">This may be due to an older version of Transport Layer Security (TLS).</span></span> <span data-ttu-id="8d665-106">Chcete-li připojit službu MSCommerce, musíte použít TLS 1.2 nebo vyšší.</span><span class="sxs-lookup"><span data-stu-id="8d665-106">To connect the MSCommerce service, you need to use TLS 1.2 or greater.</span></span>  

<span data-ttu-id="8d665-107">Pomocí následujících kroků povolte nebo nastavte protokol TLS na 1.2, ověřte a opakujte akci.</span><span class="sxs-lookup"><span data-stu-id="8d665-107">Try the following steps to enable/set the TLS protocol to 1.2, verify, and retry.</span></span>
 1. <span data-ttu-id="8d665-108">Na příkazovém řádku Prostředí\) PowerShell (PS C: zadejte následující příkaz pro nastavení protokolu TLS na verzi 1.2:</span><span class="sxs-lookup"><span data-stu-id="8d665-108">At the PowerShell command prompt (PS C:\) enter the following command to set the TLS protocol to version 1.2:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12`

2. <span data-ttu-id="8d665-109">Ověřte protokoly TLS, které se používají, pomocí následujícího příkazu:</span><span class="sxs-lookup"><span data-stu-id="8d665-109">Verify the TLS protocol(s) in use, with the following command:</span></span>

    `[Net.ServicePointManager]::SecurityProtocol` 

3. <span data-ttu-id="8d665-110">Podle potřeby opakujte příkazy Získat nebo aktualizovat.</span><span class="sxs-lookup"><span data-stu-id="8d665-110">Retry the Get or Update commands as needed.</span></span>

