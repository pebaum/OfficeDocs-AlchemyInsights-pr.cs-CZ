---
title: V klientovi Teams dochází k chybám?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030538"
---
# <a name="teams-client-crashing"></a>V klientovi Teams dochází k chybám?

Pokud v klientovi Teams dochází k chybám, vyzkoušejte následující postup:

- Pokud používáte desktopovou aplikaci Teams, [zkontrolujte, jestli je tato aplikace kompletně aktualizovaná](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

- Ujistěte se, že všechny [rozsahy adres a URL pro Office 365](https://docs.microsoft.com/microsoftteams/connectivity-issues) jsou přístupné.

- Přihlaste se pomocí účtu správce, podívejte se na [Řídicí panel stavu služeb](https://docs.microsoft.com/office365/enterprise/view-service-health) a zkontrolujte, že nedochází k výpadkům nebo snížení výkonu služby.

 - Jako poslední krok se můžete pokusit vymazat mezipaměť klienta Teams:

    1.  Úplně zavřete desktopového klienta Microsoft Teams. Můžete pravým tlačítkem kliknout na **Teams** na hlavním panelu a potom kliknout na **Ukončit**, nebo spustit Správce úloh a proces kompletně ukončit.

    2.  Přejděte do Průzkumníka souborů a zadejte %appdata%\Microsoft\teams.

    3.  Po zobrazení adresáře uvidíte některé z následujících složek:

         - Ve složce **Application Cache** přejděte ke složce cache a odstraňte všechny soubory v umístění mezipaměti: %appdata%\Microsoft\teams\application cache\cache.

        - Odstraňte všechny soubory ve složce **Blob_storage**: %appdata%\Microsoft\teams\blob_storage.

        - Odstraňte všechny soubory ve složce **Cache**: %appdata%\Microsoft\teams\Cache.

        - Odstraňte všechny soubory ve složce **databases**: %appdata%\Microsoft\teams\databases.

        - Odstraňte všechny soubory ve složce **GPUCache**: %appdata%\Microsoft\teams\GPUcache.

        - Odstraňte soubor .db ve složce **IndexedDB**: %appdata%\Microsoft\teams\IndexedDB.

        - Odstraňte všechny soubory ve složce **Local Storage**: %appdata%\Microsoft\teams\Local Storage.

        - A nakonec odstraňte všechny soubory ve složce **tmp**: %appdata%\Microsoft\teams\tmp.

    4. Restartujte klienta Teams.
