---
title: Chybějící termíny v úložišti termínů služby SharePoint Online
ms.author: pebaum
author: pebaum
ms.date: 10/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1243"
- "5200021"
ms.openlocfilehash: 28913b8e57e39d51e8957b7408c19337a119c589
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40053506"
---
# <a name="enabling-bitlocker-encryption-with-intune"></a>Povolení šifrování nástrojem BitLocker pomocí nástroje Intune

Zásady ochrany koncových bodů Intune lze použít ke konfiguraci nastavení šifrování nástroje Boitlocker pro zařízení systému Windows, jak je popsáno v následujícím nastavení: Windows10 (a novější) k ochraně zařízení pomocí nástroje Intune.

Je třeba si uvědomit, že mnoho novějších zařízení používajících systém Windows 10 podporuje automatické šifrování nástrojem BitLocker, které je spuštěno bez použití zásad MDM. To může mít vliv na použití zásad, pokud není nakonfigurováno výchozí nastavení. Podrobnější informace naleznete v nejčastějších dotazech.


FAQ  Q: které edice systému Windows podporují šifrování pomocí zásad ochrany koncových bodů?
 A: nastavení v zásadách ochrany koncového bodu nástroje Intune je implementováno pomocí zprostředkovatele kryptografických služeb pro nástroj BitLocker.Některé edice a verze systému Windows nepodporují nástroj BitLocker CSP. 
      V tomto okamžiku edice Windows: Enterprise; Podporovány jsou vzdělávání, Mobile, Mobile Enterprise a Professional (od sestavení 1809 dále).




Q: Pokud je zařízení již zašifrováno pomocí nástroje BitLocker s použitím výchozího nastavení operačního systému pro šifrovací metodu a sílu šifrování (XTS-AES-128), použije zásada s odlišným nastavením automaticky opětovné spuštění šifrování jednotky s novým nastavením?

A: ne. Chcete-li použít nové nastavení šifrování, musí být jednotka nejprve dešifrována.

Poznámka: u zařízení, která jsou zapsáni pomocí funkce autopilot, nebude aktivováno automatické šifrování, které by se spustilo během počátečního nastavení počítače (OOBE), dokud nebude vyhodnocena zásada Intune, která umožňuje použití parametrů založených na zásadách místo výchozích




Q Pokud je zařízení zašifrováno v důsledku použití zásady Intune, bude při odebrání této zásady dešifrován?

A: odebrání zásady související s šifrováním nevede k dešifrování nakonfigurovaných jednotek.




Q: Proč se v zásadách kompatibility intun ukazuje, že zařízení nemá "nástroj BitLocker Enabled", ale je?

A: nastavení "BitLocker Enabled" v zásadách Compliance (Intune) používá klienta ověřování stavu zařízení systému Windows (DHA). Tento klient měří stav zařízení pouze při spuštění. Pokud tedy nebylo zařízení znovu dokončeno od dokončení šifrování nástrojem BitLocker, nebude klientská služba DHA hlásit nástroj BitLocker jako aktivní.