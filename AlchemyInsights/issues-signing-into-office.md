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
- "2574"
ms.openlocfilehash: 3622a3408b25b43090e9414ae5ffcfc2760264ee
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938166"
---
# <a name="issues-signing-in-to-office-apps"></a>Problémy s přihlášením do aplikace sady Office

K opravě potíží při přihlašování s aplikací sady Office, postupujte takto:

- Odeberte všechny účty práce, s výjimkou ohrožený účet, pomocí > nastavení systému Windows, **přístup k práci nebo ve škole**.
- [Office vymazat pověření](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.<br/>
    **Poznámka:** 16.0 změnily cesty registru pro Office 2016. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)
- Otevřete aplikaci sady Office, zvolte **soubor** > **účtu** > **Odhlásit**. Pak se přihlaste pomocí uživatelského účtu s platnou licencí. Podrobné informace naleznete v tématu [účty v sadě Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- Mac viz [nelze přihlásit Office 2016 pro Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).
- Pokud dojde k chybám při připojování k Office 2013 pomocí služeb Office 365, moderní pro ověření klienta sady Office.

Další informace najdete tady:
- [Se nelze přihlásit do služeb Office 365, Azure nebo Intune](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [Problémy s připojením v přihlášení po aktualizaci Office 2016 sestavení 16.0.7967 v systému Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- ["Bohužel jiný účet z organizace je již přihlášen v tomto počítači" v sadě Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [Řešení problémů přihlásit s Office moderní ověřování při použití službou AD FS](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)