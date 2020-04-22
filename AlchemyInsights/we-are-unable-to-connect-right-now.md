---
title: Problém s aktivací – nedaří se nám připojit právě teď
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 56accf68f2cf41dbe6119281b74e2cb56b702789
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716165"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a>Oprava zprávy Opravou aplikací Office "Nejsme se teď schopni připojit"

Pokud se zobrazí tato zpráva, vyzkoušejte následující postup:

1. Zkontrolujte bránu firewall, antivirový software a nastavení proxy serveru a ověřte, zda neblokují přístup k Internetu aplikacím Office. Viz [Adresy URL společnosti Microsoft a rozsahy IP adres](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Přejděte na **spustit** > **a**zadejte **services.msc**. Ujistěte se, že jsou spuštěny všechny následující služby:
    - Automatické nastavení síťových připojených zařízení
    - Služba Seznam sítí
    - Povědomí o umístění v síti
    - Protokol událostí systému Windows

Pokud některá z těchto služeb není spuštěna, zkuste ji spustit. Pokud máte problém se spuštěním služby, spusťte následující příkaz otevřením příkazového řádku se zvýšenými oprávněními:

**sfc /scannow**

Po dokončení tohoto příkazu restartujte počítač.

Podrobné informace najdete [v tématu "Omlouváme se, ale nemůžeme se připojit k vašemu účtu. Zkuste to prosím znovu později" chyba při aktivaci Office z Microsoft u 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).