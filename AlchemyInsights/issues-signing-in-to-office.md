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
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938167"
---
# <a name="blank-sign-in-screen-in-office-apps"></a>Prázdná obrazovka přihlášení do aplikací sady Office

Chcete-li tento problém vyřešit, zkuste následující postup:
- Nainstalujte nejnovější aktualizace pro [systém Windows](https://support.microsoft.com/help/4027667/windows-10-update) a [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).
- Obnovení nastavení aplikace Internet Explorer: přejděte na **Nástroje** > **Možnosti Internetu** > **Upřesnit** > **Obnovení nastavení aplikace Internet Explorer** (Všimněte si, že dojde ke ztrátě vlastního nastavení) a potom zkuste znovu přihlásit k Office.
- Zakázání součásti Windows Defender aplikace Guard (WDAG) nebo podobný program brány firewall nebo antivirového programu:
    1. V Ovládacích panelech přejděte na položku **programy**a pak zvolte **Zapnout funkce systému Windows zapnout nebo vypnout**.
    2. Pokud je povolena ochrana aplikace Windows Defender, zkuste ji vypnout.<br/>
    **Poznámka:** Musíte restartovat počítač.
- Ujistěte se, že Microsoft.AAD.BrokerPlugin [WAM Poplašné plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) nejsou blokovány všechny aplikace nebo program brány firewall nebo antivirové.
- [Office vymazat pověření](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.<br/>
    **Poznámka:** 16.0 změnily cesty registru pro Office 2016. (Ex: \Software\Microsoft\Office\16.0\Common\Identity\)

Další informace naleznete v tématu [připojení problémy v přihlášení po aktualizaci Office 2016 sestavení 16.0.7967 v systému Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).