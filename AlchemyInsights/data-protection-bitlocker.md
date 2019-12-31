---
title: DataProtection-nástroj BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1802"
- "9000220"
ms.openlocfilehash: c23a2a2bde240900119382a9c1185a6e02520149
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908703"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Povolení šifrování nástrojem BitLocker pomocí nástroje Intune

 Zásady ochrany koncového bodu Intune lze použít ke konfiguraci nastavení šifrování nástrojem BitLocker pro zařízení systému Windows. Další informace naleznete v [nastavení systému Windows 10 (a novějších) pro ochranu zařízení pomocí nástroje Intune](https://docs.microsoft.com/intune/endpoint-protection-windows-10#windows-encryption).
 
Je třeba si uvědomit, že mnoho novějších zařízení používajících systém Windows 10 podporuje automatické šifrování nástrojem BitLocker, které je spuštěno bez použití zásad MDM. To může mít vliv na použití zásady, pokud je nakonfigurováno jiné než výchozí nastavení. Další informace naleznete v následujících nejčastějších dotazech.
 
Informace o odstraňování potíží s nástrojem BitLocker naleznete [v tématu Poradce při potížích s zásadami nástroje BitLocker v systému Microsoft Intune](https://docs.microsoft.com/intune/protect/troubleshoot-bitlocker-policies).
 
 
**Časté otázky**

 Q: které edice systému Windows podporují šifrování pomocí zásad ochrany koncových bodů?<br>
 A: nastavení v zásadách ochrany koncových bodů nástroje Intune jsou implementována pomocí [zprostředkovatele kryptografických služeb (BitLocker](https://docs.microsoft.com/windows/client-management/mdm/bitlocker-csp)). Některé edice a verze systému Windows nepodporují nástroj BitLocker CSP. <br><br>
      V tomto okamžiku jsou podporovány následující edice systému Windows: Enterprise, školství, Mobile, Mobile Enterprise a Professional (sestavení 1809 a novější).
 
Q: Pokud je zařízení již zašifrováno pomocí nástroje BitLocker s použitím výchozího nastavení operačního systému pro šifrovací metodu a sílu šifrování (XTS-AES-128), použije zásada s různým nastavením automaticky opětovné spuštění šifrování jednotky s novým nastavením?<br>
A: ne. Chcete-li použít nové nastavení šifrování, musí být jednotka nejprve dešifrována.<br><br>
**Poznámka:** U zařízení, která jsou zapsáni pomocí funkce autopilot, nebude automatické šifrování, ke kterému dojde během počátečního spuštění počítače, spuštěno, dokud nebude vyhodnocena zásada Intune, která umožňuje použití nastavení založeného na zásadách namísto výchozích hodnot operačního systému.
 
Q: Pokud je zařízení zašifrováno v důsledku použití zásady Intune, bude při odebrání této zásady dešifrován?<br>
A: odebrání zásad týkajících se šifrování nevede k dešifrování nakonfigurovaných jednotek.
 
Q: Proč se v zásadách kompatibility Intune zobrazují, že zařízení nemá povolen nástroj BitLocker, i když je?<br>
A: nastavení "BitLocker Enabled" v zásadách Compliance (Intune) používá klienta ověřování stavu zařízení systému Windows (DHA). Tento klient měří stav zařízení pouze při spuštění. Pokud tedy nebylo zařízení po dokončení šifrování nástrojem BitLocker ukončeno, nebude klientská služba pro připojení k obnovení dat vykazovat nástroj BitLocker jako aktivní.
 
 