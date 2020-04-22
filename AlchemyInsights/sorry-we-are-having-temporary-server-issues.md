---
title: Oprava aplikací Office Omlouváme se, máme zprávu o dočasných problémech se serverem
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: a1ac62f3587e318d563cfea1df8db23b720358a6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764110"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a>Oprava zprávy Opravou aplikací Office "Omlouváme se, máme problémy s dočasným serverem"

Pokud se zobrazí tato zpráva, vyzkoušejte následující postup:

1. Zkontrolujte bránu firewall, antivirový software a nastavení proxy serveru a ověřte, zda neblokují přístup k Internetu aplikacím Office. Viz [adresy URL a rozsahy IP adres](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

2. Přejděte na **spustit** > **a**zadejte **services.msc**. Ujistěte se, že jsou spuštěny všechny následující služby:
    - Automatické nastavení síťových připojených zařízení
    - Služba Seznam sítí
    - Povědomí o umístění v síti
    - Protokol událostí systému Windows

Pokud některá z těchto služeb není spuštěna, zkuste ji spustit. Pokud máte problém se spuštěním služby, spusťte následující příkaz otevřením příkazového řádku se zvýšenými oprávněními:

**sfc /scannow**

Po dokončení tohoto příkazu restartujte počítač.

Podrobné informace najdete [v tématu "Omlouváme se, ale nemůžeme se připojit k vašemu účtu. Opakujte akci později" chyba při aktivaci](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).