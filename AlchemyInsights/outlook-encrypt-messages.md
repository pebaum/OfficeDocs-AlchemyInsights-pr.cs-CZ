---
title: S/MIME v aplikaci Outlook na webu
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 6915470655b85922f6f97e8ca6fac353224b1ae0
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36752853"
---
# <a name="encrypt-email-messages-in-outlook"></a>Šifrování e-mailových zpráv v aplikaci Outlook

Šifrování zpráv sady Office 365 je postaveno na službě Microsoft Azure Rights Management (Azure RMS), která je součástí ochrany informací Azure. Pokud vaše předplatné obsahuje službu Azure Rights Management nebo ochranu informací Azure, nemusíte **provádět žádné akce pro ruční povolení nebo aktivaci** služby správy přístupových práv.

Na základě názorů zákazníků již nebude možné, aby pravidla toku pošty serveru Exchange automaticky zašifrovala odchozí e-maily obsahující určitý typ citlivých informací ve vašem nájemci ve výchozím nastavení. Místo toho nám poskytujeme podrobné instrukce, jak to můžete udělat sami. Další podrobnosti o vytvoření pravidla přenosu pro šifrování citlivých informací naleznete v [tomto článku](https://aka.ms/OmeEtr).

- Pokud používáte aplikaci Outlook na webu (dříve **OWA**): při psaní e-mailové zprávy klepněte v aplikaci OWA na tlačítko **chránit** . Bude použito oprávnění Nepředávat dál. Klepněte na tlačítko **změnit oprávnění** a zvolte možnost **Šifrovat** , chcete-li zprávu zašifrovat pouze.

- Pokud používáte **klienta aplikace Outlook**: Chcete-li odeslat zašifrovanou zprávu z aplikace Outlook 2013 nebo 2016 nebo Outlook 2016 pro Mac, vyberte**oprávnění**k **možnostem** > a vyberte požadovanou možnost ochrany.

- Chcete-li **automaticky zašifrovat všechny e-maily** odeslané určitým příjemcům nebo organizacím externích partnerů, je třeba vytvořit pravidlo přenosu pošty v centru pro správu serveru Exchange. Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).

