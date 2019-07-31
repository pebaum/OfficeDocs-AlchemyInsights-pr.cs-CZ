---
title: Problémy s přihlášením do aplikace sady Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2559"
ms.openlocfilehash: 5f500ecf1f779fb1be4d257fd050a3ad054087dc
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938168"
---
# <a name="fixing-the-office-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a>Řešení Office apps "modul důvěryhodné platformy v počítači nepracuje správně" zpráva

Chcete-li tuto chybu vyřešit, vyzkoušejte následující postup:

- Nainstalujte nejnovější aktualizace pro [systém Windows](https://support.microsoft.com/help/4027667/windows-10-update) a [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- [Office vymazat pověření](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.<br/>
    **Poznámka:** 16.0 změnily cesty registru pro Office 2016. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)
- Zkuste [proces obnovení uživatele](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) Chcete-li opravit chyby Trusted Platform Module (TPM).
- Nastavit EnableADAL = 0, pomocí následujících kroků:  
    1. Klepněte pravým tlačítkem myši na tlačítko Start systému Windows, zvolte **Spustit**, zadejte **příkaz regedit**a klepněte na tlačítko **OK**.
    2. Vyberte **Ano** editoru registru provádět změny zařízení.
    3. V editoru registru přidejte hodnotu DWORD **EnableADAL** na hodnotu **0** v HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.

Další informace naleznete v tématu [připojení problémy v přihlášení po aktualizaci Office 2016 sestavení 16.0.7967 v systému Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).