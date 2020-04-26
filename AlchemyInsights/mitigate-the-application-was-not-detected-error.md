---
title: Řešení chyby Aplikace nebyla zjištěna
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810477"
---
# <a name="mitigate-the-application-was-not-detected-error"></a>Řešení chyby „Aplikace nebyla zjištěna“

K chybě „Aplikace nebyla po úspěšném dokončení instalace zjištěna“ při instalaci aplikace přes Intune může dojít na všech hlavních operačních systémech (Windows, iOS a Android).

Nejběžnější případy, kdy k této chybě dochází:

- Aplikace se po prvotním nasazení aktualizovala mimo Intune (z obchodu s aplikacemi třetí strany). Některé aplikace, jako je Google Chrome, se můžou aktualizovat automaticky.
- Uživatel po počáteční instalaci odinstaloval aplikaci.

Abyste tento problém vyřešili, nejdřív zkontrolujte dotčená zařízení a zjistěte, proč k chybě došlo.

- Pokud se aplikace aktualizovala mimo Intune, můžete pro její nasazení nastavit, aby ignorovalo verzi aplikace. Uděláte to tak, že v **Konfigurace aplikace > Informace o aplikaci** nastavíte **Ignorovat verzi aplikace** na **Ano**.
- Při cílení na klienta může být vhodné nasadit aplikaci jako „povinnou“ a zajistit tak nasazení její nejnovější verze.
- Na platformě iOS jde případně použít funkci **automatických aktualizací** související s Programem hromadných nákupů Apple, kterou můžete nakonfigurovat, aby automaticky instalovala nové verze aplikací, jakmile budou dostupné.

Další informace o řešení problémů s instalací aplikací najdete v článku [Řešení problémů s instalací aplikací](https://docs.microsoft.com/intune/troubleshoot-app-install).
