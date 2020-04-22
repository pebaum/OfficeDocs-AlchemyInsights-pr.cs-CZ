---
title: V Obchodě s termíny SharePointu Online chybí podmínky
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 54ac2dbc1f45f88541c2338f3b55a777b4b57123
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766846"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Povolení šifrování nástroje Bitlocker pomocí Intune

Zásady ochrany koncového bodu Intune lze použít ke konfiguraci nastavení šifrování Boitlocker u zařízení s Windows, jak je popsáno v : Nastavení Windows10 (a novější) k ochraně zařízení pomocí Intune

Měli byste si být vědomi toho, že mnoho novějších zařízení se systémem Windows 10 podporuje automatické šifrování nástroje BitLocker, které se aktivuje bez použití zásad MDM. To může mít vliv na použití zásady, pokud jsou nakonfigurována nevýchozí nastavení. Další podrobnosti najdete v častých dotazech.


Častý  dotaz Q: Které edice systému Windows podporují šifrování zařízení pomocí zásad ochrany koncových bodů?
 A: Nastavení v Zásadách ochrany koncového bodu Intune jsou implementovány pomocí nástroje CSP nástroje Bitlocker.Ne všechny edice ani sestavení systému Windows podporují csp nástroje Bitlocker. 
      V tomto okamžiku Windows Editions: Enterprise; Vzdělávání, Mobilní, Mobilní podnik a Professional (od sestavení 1809 dále) jsou podporovány.




Otázka: Pokud je zařízení již šifrováno pomocí nástroje Bitlocker pomocí výchozího nastavení operačního systému pro metodu šifrování a síla šifrování (XTS-AES-128), bude použití zásady s různými nastaveními automaticky aktivovat opětovné šifrování jednotky s novým nastavením?

A: Ne. Chcete-li použít nové nastavení šifry, musí být jednotka nejprve dešifrována.

Poznámka: U zařízení zaregistrovaných pomocí funkce Autopilot se automatické šifrování, ke kterému by došlo během OOBE, neaktivuje, dokud se nevyhodnotí zásady Intune, které umožňují použití nastavení na základě zásad namísto výchozích nastavení operačního systému




Q Pokud je zařízení zašifrováno v důsledku použití zásad Intune, bude dešifrováno, když je tato zásada odebrána?

A: Odstranění zásad souvisejících s šifrováním nemá za následek dešifrování jednotek, které byly nakonfigurovány.




Otázka: Proč zásady dodržování předpisů intune ukazují, že moje zařízení nemá povoleno nástroj Bitlocker, ale je?

A: Nastavení "Bitlocker povoleno" v zásadách dodržování předpisů intune využívá windows zařízení potvrzení stavu (DHA) klienta. Tento klient měří pouze stav zařízení při spuštění. Pokud tedy zařízení nebylo restartováno od dokončení šifrování nástrojem BitLocker, klientská služba DHA nenahlásí nástroj BitLocker jako aktivní.