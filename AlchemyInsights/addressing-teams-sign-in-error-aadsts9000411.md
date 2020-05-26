---
title: Chyba při přihlašování týmů AADSTS9000411
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000744"
- "5689"
ms.openlocfilehash: b70f1320ea1dfa29e6fa489bd02acfcd1d92971b
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/20/2020
ms.locfileid: "44357401"
---
# <a name="addressing-teams-sign-in-error-aadsts9000411"></a>Chyba při přihlašování týmů AADSTS9000411

Při přihlášení k Microsoft Teams se může zobrazit chyba: **Omlouváme se, ale máme potíže s přihlášením v AADSTS9000411: Žádost není správně naformátovaná. Parametr "login_hint" je duplikován.**

Chcete-li tento problém vyřešit, zkontrolujte, zda jsou klienti Microsoft Teams aktualizováni. Další informace o aktualizaci klienta naleznete v [tématu Aktualizace aplikace Microsoft Teams](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

Pokud z nějakého důvodu nemůžete klienta aktualizovat, odhlášením klienta se vymažou většina dat uložených v mezipaměti. Pokud však stále máte problémy po odhlášení nebo přihlášení, ukončete teams a vymažte mezipaměť klienta následujícím způsobem:
1. Zavřete Microsoft Teams.
2. Přejděte na: %appdata%\microsoft\teams a odstraňte všechny soubory.
3. Znovu otevřete Microsoft Teams.
