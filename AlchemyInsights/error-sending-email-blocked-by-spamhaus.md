---
title: Při odesílání e-mailů blokovaných spamem došlo k chybě.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714251"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Při odesílání e-mailů došlo k chybě: Hostitel klienta byl zablokován pomocí spamhausu

IP adresa, která zprávu odeslala, je na seznamu blokování vlastněném [společností Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245). Mezi důvody, proč spamhaus blokuje, patří kompromitované účty, ohrožené počítače sdílející veřejnou IP adresu a zásady poskytovatele internetových služeb (ISP). Možné opravy jsou:
  
- U blokovaných příchozích zpráv, kde ovládáte zdrojový e-mailový server, je třeba určit příčinu a odstranit blok z webu Spamhaus.

- U blokovaných příchozích zpráv, u kterých zdrojová IP adresa patří někomu jinému, musí vlastník adresy odstranit blok z webu Spamhaus. Pokud je adresa IP v seznamu blokování zásad (PBL), může vlastník přiřadit jinou statickou adresu IP nebo adresu z PBL odebrat.

- U blokovaných odchozích zpráv z vaší domény připojené k Microsoftu se tato chyba zobrazí, pokud jsou zprávy směrovány prostřednictvím služby třetí strany. Pomocí vyhledávacího nástroje WHOIS můžete najít vlastníka blokované adresy IP.
