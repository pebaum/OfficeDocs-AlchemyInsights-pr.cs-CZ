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
ms.openlocfilehash: a9b6e36e8034e71b3e72c49e3cc68a126ef97aca
ms.sourcegitcommit: cb9505f9eca032af3a4194c68d18c91789365690
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/16/2020
ms.locfileid: "42091678"
---
# <a name="unable-to-set-or-view-the-allowselfservicepurchase-policy"></a>Zásady AllowSelfServicePurchase nelze nastavit ani zobrazit.

Při pokusu o nastavení nebo zobrazení zásad AllowSelfServicePurchase se zobrazí následující chybová zpráva:

*HandleError : Nepodařilo se načíst zásady produktu s PolicyId 'AllowSelfServicePurchase', ErrorMessage - Základní připojení bylo uzavřeno: Při odesílání došlo k neočekávané chybě.*

To může být způsobeno starší verzí zabezpečení transportní vrstvy (TLS). Chcete-li připojit službu MSCommerce, musíte použít TLS 1.2 nebo vyšší.  

Pomocí následujících kroků povolte nebo nastavte protokol TLS na 1.2, ověřte a opakujte akci.
 1. Na příkazovém řádku Prostředí\) PowerShell (PS C: zadejte následující příkaz pro nastavení protokolu TLS na verzi 1.2:

    \[Net.ServicePointManager]::SecurityProtocol = \[Net.SecurityProtocolType]::Tls12

2. Ověřte protokoly TLS, které se používají, pomocí následujícího příkazu:

    \[Net.ServicePointManager]::Protokol SecurityProtocol 

3. Podle potřeby opakujte příkazy Získat nebo aktualizovat.

