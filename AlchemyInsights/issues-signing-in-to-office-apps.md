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
- "2560"
ms.openlocfilehash: de0a1b78724db9a8e93d8d599ce3b503abcb86e2
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938165"
---
# <a name="fixing-the-office-apps-sorry-another-account-from-your-organization-is-already-signed-in-message"></a>Stanovení "Bohužel jiný účet z organizace je již přihlášen" zprávy aplikací sady Office

Chcete-li tuto chybu vyřešit, vyzkoušejte následující postup:

- Odeberte všechny účty práce, s výjimkou ohrožený účet, pomocí > nastavení systému Windows, **přístup k práci nebo ve škole**.
- [Office vymazat pověření](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.<br/>
    **Poznámka:** 16.0 změnily cesty registru pro Office 2016. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)
- Otevřete aplikaci sady Office, zvolte **soubor** > **účtu** > **Odhlásit**. Pak se přihlaste pomocí uživatelského účtu s platnou licencí. Podrobné informace naleznete v tématu [účty v sadě Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- Mac viz [nelze přihlásit Office 2016 pro Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).

Další informace naleznete v tématu ["Bohužel jiný účet z organizace je již přihlášen v tomto počítači" v Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).