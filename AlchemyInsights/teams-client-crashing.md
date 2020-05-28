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
ms.openlocfilehash: ac1cc05adfa33626ff34d30dca6c77f1bb96477a
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/23/2020
ms.locfileid: "44354045"
---
# <a name="teams-client-crashing"></a>V klientovi Teams dochází k chybám?

Pokud v klientovi Teams dochází k chybám, vyzkoušejte následující postup:

- Pokud používáte desktopovou aplikaci Teams, [zkontrolujte, jestli je tato aplikace kompletně aktualizovaná](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

- Zkontrolujte, zda jsou přístupné všechny [adresy URL a rozsahy adres společnosti Microsoft 365.](https://docs.microsoft.com/microsoftteams/connectivity-issues)

- Přihlaste se pomocí účtu správce klienta a zkontrolujte [řídicí panel stavu služby](https://docs.microsoft.com/office365/enterprise/view-service-health) a ověřte, zda neexistuje žádný výpadek nebo snížení stavu služby.

- Odinstalace a přeinstalace aplikace Teams (odkaz)
    - Přejděte do složky %appdata%\Microsoft\teams\ v počítači a odstraňte všechny soubory v tomto adresáři.
    - [Stáhněte si a nainstalujte aplikaci Teams](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software#office-DesktopAppDownload-ofoushy)a pokud je to možné, nainstalujte teams jako správce (klikněte pravým tlačítkem myši na instalační program Teams a vyberte možnost Spustit jako správce, pokud je k dispozici).

Pokud váš klient Teams stále padá, můžete problém reprodukovat? Pokud ano:

1. Pomocí záznamníku kroků zachyťte své kroky.
    - Zavřete všechny zbytečné nebo důvěrné aplikace.
    - Spusťte záznam postupu a reprodukovat problém při přihlášení pomocí ovlivněné ho uživatelského účtu.
    - [Shromažďovat protokoly týmů, které zachycují zaznamenané kroky repro](https://docs.microsoft.com/microsoftteams/log-files). **Poznámka:** Ujistěte se, že jste zachytili přihlašovací adresu ovlivněného uživatele.
    - Shromážděte informace o výpisu a/nebo vadě (Windows). Spusťte prostředí Windows Powershell v počítači, kde dochází k chybě, a spusťte následující příkazy:

        `
        PS C:\Users\user01> cd $env:temp
        PS C:\Users\user01\AppData\Local\Temp> Get-EventLog -LogName Application -Message "*Teams.exe*" -InstanceId 1001 | Select-Object -First 10 | Format-List > FaultBuckets.txt
        PS C:\Users\user01\AppData\Local\Temp> notepad .\FaultBuckets.txt
        `
    
2. Připojte soubor k případu podpory.
