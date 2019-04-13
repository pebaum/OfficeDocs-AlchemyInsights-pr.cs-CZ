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
# <a name="winsock-error-10061"></a>Rozhraní Winsock chyby 10061

Tento chybový kód znamená, že Office 365 nemohl vytvořit soket TCP (připojení) s cílového hostitele. Nejpravděpodobnější příčina této chyby je problém s konfigurací brány firewall. Chcete-li problém vyřešit, zkontrolujte tato nastavení:

- Zkontrolujte konfiguraci brány firewall s informacemi v [Office 365 adresy URL a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)

- Pokud došlo k chybě specifické pro server Exchange Online ochrany (EOP), je by byly dříve sděleny změny na [Exchange Online ochrany IP adresy](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

- Ověřte, že váš poskytovatel služeb Internetu (ISP) neblokuje port.

- Ověřte inteligentní nastavení serveru hostitele a cíl v spojnice.

Všimněte si, že Office 365 nelze blokovat *příchozí* připojení tímto způsobem.
