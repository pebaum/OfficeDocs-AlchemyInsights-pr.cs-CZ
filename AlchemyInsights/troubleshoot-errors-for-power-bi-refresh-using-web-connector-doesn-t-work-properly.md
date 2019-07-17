---
Title: Aktualizovat pomocí webu connector nefunguje správně
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1316"
- "2500002"
ms.openlocfilehash: e6c0f44f8f62b01e7f4dd23776ba8c13a2999c6b
ms.sourcegitcommit: e17e7d17fdb638349bb320b318085138d18f284c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/16/2019
ms.locfileid: "35753281"
---
# <a name="refresh-using-web-connector-doesnt-work-properly"></a><span data-ttu-id="31883-102">Aktualizovat pomocí webu connector nefunguje správně</span><span class="sxs-lookup"><span data-stu-id="31883-102">Refresh using Web connector doesn't work properly</span></span>

<span data-ttu-id="31883-103">Pokud máte web connector skript, který používá funkci [Web.Page](https://msdn.microsoft.com/library/mt260924.aspx) a aktualizaci dataset nebo sestavy po 18. listopadu 2016, musíte použít bránu aktualizovat, aby správně fungovat.</span><span class="sxs-lookup"><span data-stu-id="31883-103">If you have a web connector script that's using the [Web.Page](https://msdn.microsoft.com/library/mt260924.aspx) function, and you have updated your dataset or report after November 18th, 2016, you need to use a gateway in order for refresh to work properly.</span></span>

<span data-ttu-id="31883-104">Další informace:[https://docs.microsoft.com/power-bi/refresh-troubleshooting-refresh-scenarios](https://docs.microsoft.com/power-bi/refresh-troubleshooting-refresh-scenarios)</span><span class="sxs-lookup"><span data-stu-id="31883-104">For more information: [https://docs.microsoft.com/power-bi/refresh-troubleshooting-refresh-scenarios](https://docs.microsoft.com/power-bi/refresh-troubleshooting-refresh-scenarios)</span></span>
