---
title: Chybě rozhraní Winsock. 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 96a9cfd11941158ddf13655c74974e3eb800e570
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281225"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="4e224-102">Rozhraní Winsock chyby 10061</span><span class="sxs-lookup"><span data-stu-id="4e224-102">Winsock error 10061</span></span>

<span data-ttu-id="4e224-p101">Tento chybový kód znamená, že Office 365 nemohl vytvořit soket TCP (připojení) s cílového hostitele. Nejpravděpodobnější příčina této chyby je problém s konfigurací brány firewall. Chcete-li problém vyřešit, zkontrolujte tato nastavení:</span><span class="sxs-lookup"><span data-stu-id="4e224-p101">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host. The most likely cause of this error is a problem with your firewall configuration. To fix the problem, check these settings:</span></span>
  
- <span data-ttu-id="4e224-106">Zkontrolujte konfiguraci brány firewall s informacemi v [Office 365 adresy URL a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="4e224-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>
    
- <span data-ttu-id="4e224-107">Pokud došlo k chybě specifické pro server Exchange Online ochrany (EOP), je by byly dříve sděleny změny na [Exchange Online ochrany IP adresy](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="4e224-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
    
- <span data-ttu-id="4e224-108">Ověřte, že váš poskytovatel služeb Internetu (ISP) neblokuje port.</span><span class="sxs-lookup"><span data-stu-id="4e224-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>
    
- <span data-ttu-id="4e224-109">Ověřte inteligentní nastavení serveru hostitele a cíl v spojnice.</span><span class="sxs-lookup"><span data-stu-id="4e224-109">Verify the smart host and target server settings in your connectors.</span></span>
    
<span data-ttu-id="4e224-110">Všimněte si, že Office 365 nelze blokovat *příchozí* připojení tímto způsobem.</span><span class="sxs-lookup"><span data-stu-id="4e224-110">Note that Office 365 doesn't block  *incoming*  connections in this manner.</span></span> 
  

