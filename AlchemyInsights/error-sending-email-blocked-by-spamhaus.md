---
title: Chyba při odesílání e-mailu blokováno SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 39213f6f1b96c2bef9ea071f43c38766debf64d1
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527125"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a>Chyba při odesílání e-mailu: klienta host blokovaných Spamhaus pomocí

Adresu IP, který zprávu odeslal, je na seznamu blokování [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245)vlastněné. Hostují účty obsahovat důvody blokován nastavením Spamhaus ohrožení počítače sdílení veřejných adres IP a zásad poskytovatele služeb Internetu (ISP). Jsou možné opravy:
  
- Blokování příchozích zpráv kde ovládacího prvku zdrojového serveru e-mailu služeb Office 365 je třeba zjistit příčinu a odstranit blokování Spamhaus webu.

- U blokovaných příchozích zpráv do služeb Office 365, pokud je zdrojová adresa IP patří někomu jinému musí odstranit blok z webu Spamhaus adresa vlastníka. Pokud adresa IP je v seznamu zásad bloku (PBL), vlastník můžete přiřadit jinou statickou adresu IP nebo adresu odebrat z PBL.

- Pro blokované odchozí zprávy z vaší domény služeb Office 365 můžete obdržet tuto chybu Pokud zprávy jsou směrovány prostřednictvím služby 3. strana. Vyhledávací nástroj WHOIS můžete použít k nalezení vlastníka blokované adresy IP.
