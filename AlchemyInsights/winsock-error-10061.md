---
title: Chybě rozhraní Winsock. 1554 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 7651effc43cb0c4bc2fbbe5349bb72303943f493
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/13/2019
ms.locfileid: "31859133"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="a69d3-102">Rozhraní Winsock chyby 10061</span><span class="sxs-lookup"><span data-stu-id="a69d3-102">Winsock error 10061</span></span>

<span data-ttu-id="a69d3-103">Tento chybový kód znamená, že Office 365 nemohl vytvořit soket TCP (připojení) s cílového hostitele.</span><span class="sxs-lookup"><span data-stu-id="a69d3-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="a69d3-104">Nejpravděpodobnější příčina této chyby je problém s konfigurací brány firewall.</span><span class="sxs-lookup"><span data-stu-id="a69d3-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="a69d3-105">Chcete-li problém vyřešit, zkontrolujte tato nastavení:</span><span class="sxs-lookup"><span data-stu-id="a69d3-105">To fix the problem, check these settings:</span></span>

- <span data-ttu-id="a69d3-106">Zkontrolujte konfiguraci brány firewall s informacemi v [Office 365 adresy URL a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span><span class="sxs-lookup"><span data-stu-id="a69d3-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>

- <span data-ttu-id="a69d3-107">Pokud došlo k chybě specifické pro server Exchange Online ochrany (EOP), je by byly dříve sděleny změny na [Exchange Online ochrany IP adresy](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="a69d3-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

- <span data-ttu-id="a69d3-108">Ověřte, že váš poskytovatel služeb Internetu (ISP) neblokuje port.</span><span class="sxs-lookup"><span data-stu-id="a69d3-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>

- <span data-ttu-id="a69d3-109">Ověřte inteligentní nastavení serveru hostitele a cíl v spojnice.</span><span class="sxs-lookup"><span data-stu-id="a69d3-109">Verify the smart host and target server settings in your connectors.</span></span>

<span data-ttu-id="a69d3-110">Všimněte si, že Office 365 nelze blokovat *příchozí* připojení tímto způsobem.</span><span class="sxs-lookup"><span data-stu-id="a69d3-110">Note that Office 365 doesn't block *incoming* connections in this manner.</span></span>
