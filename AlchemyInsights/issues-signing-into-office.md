---
title: Problémy s přihlášením k aplikacím Office
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
ms.openlocfilehash: 695d449a876c22ff441da2367ef67aaea470eb66
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43762974"
---
# <a name="issues-signing-in-to-office-apps"></a>Problémy s přihlášením k aplikacím Office

Pokud chcete vyřešit problémy s přihlášením k aplikacím Office, vyzkoušejte následující:

- Odebrání všech pracovních účtů s výjimkou ovlivněných účtů pomocí nastavení systému Windows > **práci nebo škole aplikace Access**.
- [Zrušte přihlašovací údaje Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.<br/>
    **Poznámka:** Cesty registru pro Office 2016 se změnily na 16.0. (Např.: \Software\Microsoft\Office\16.0\Common\Identity\)
- Otevřete aplikaci Office a zvolte**Odhlásit**se z**účtu** >  **.** >  Poté se přihlaste pomocí uživatelského účtu s platnou licencí. Podrobné informace najdete v článku [Účty v Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- V případě Macu si projděte téma [Nejde se přihlásit k aplikaci Office 2016 pro Mac](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).
- Pokud dojde k chybám při připojování k Microsoftu 365 pomocí Office 2013, povolte moderní ověřování pro klienta Office.

Další informace najdete tady:
- [Nemůžete se přihlásit k Microsoftu 365, Azure nebo Intune.](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [Problémy s připojením při přihlášení po aktualizaci office 2016 sestavení 16.0.7967 ve Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- ["Omlouváme se, ale jiný účet z vaší organizace je již přihlášen v tomto počítači" v Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [Poradce při potížích s přihlášením s moderním ověřováním Office při použití služby ADFS](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)