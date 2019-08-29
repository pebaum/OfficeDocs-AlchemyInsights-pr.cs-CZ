---
title: S/MIME v aplikaci Outlook na webu
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: f2c047ca31c586c0aa36701e6e7ca9976cfd1734
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666833"
---
# <a name="encrypt-email-messages-in-outlook"></a>Šifrování e-mailové zprávy v aplikaci Outlook

Šifrování zpráv Office 365 je založen na Microsoft Azure Rights Management (Azure RMS), který je součástí sady Azure ochrana údajů. Pokud vaše předplatné obsahuje Azure Rights Management nebo Azure, ochrana údajů, **není nutné provádět žádné akce chcete-li ručně zapnout nebo aktivovat** službu pro správu práv.

Na základě názorů zákazníků, jsme již zapnou pravidla toku pošty Exchange automaticky šifrovat odchozí e-mail obsahující určitý typ citlivých informací do vašeho klienta ve výchozím nastavení. Místo toho poskytujeme podrobné informace o tom, jak to lze provést sami sobě. Další informace o tom, jak vytvořit pravidlo přenosu pro šifrování citlivých informací naleznete v [tomto článku](https://aka.ms/OmeEtr).

- Používáte-li aplikaci Outlook na webu (dříve **OWA**): při psaní e-mailu, jednoduše klepněte na tlačítko **Zamknout** v aplikaci OWA. Tato změna se projeví "není dopředu" oprávnění. Klepněte na tlačítko **změnit oprávnění** a zvolte **šifrovat** pouze šifrování zprávy.

- Použití **klienta aplikace Outlook**: Chcete-li odeslat šifrovanou zprávu z aplikace Outlook 2013 nebo 2016 nebo 2016 aplikace Outlook pro Mac, vyberte **Možnosti** > **oprávnění**a potom vyberte požadované možnosti ochrany.

- Chcete **automaticky zašifrovány všechny e-maily** odeslané do určitých příjemců nebo externích partnerských organizací musíte vytvořit pravidlo dopravy toku pošty v Exchange Admin Center. Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).

