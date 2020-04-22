---
title: S/MIME v Outlooku na webu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 7184ffd68f56639a8bcb87e9c6cab88388868103
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764865"
---
# <a name="encrypt-email-messages-in-outlook"></a>Šifrování e-mailových zpráv v Outlooku

Šifrování zpráv Microsoft 365 je postavené na Microsoft Azure Rights Management (Azure RMS), který je součástí Azure Information Protection. Pokud vaše předplatné zahrnuje Azure Rights Management nebo Azure Information Protection, **nemusíte provádět žádné akce, abyste ručně povolit nebo aktivovat** službu Rights Management Service.

Na základě zpětné vazby od zákazníků už nepovolíme pravidlům toku pošty Exchange automaticky šifrovat odchozí e-maily obsahující určitý typ citlivých informací ve vašem tenantovi ve výchozím nastavení. Místo toho poskytujeme podrobné pokyny, jak to můžete udělat sami. Další podrobnosti o tom, jak vytvořit pravidlo přenosu pro šifrování citlivých informací, naleznete v [tomto článku](https://aka.ms/OmeEtr).

- Pokud používáte Outlook na webu (dříve **OWA**): Při vytváření e-mailové zprávy jednoduše klikněte na **chránit** v aplikaci OWA. To bude platit "Nepředávat dál" oprávnění. Klikněte na **Změnit oprávnění** a zvolte **Šifrovat,** aby se zpráva šifrovat jena.

- Pokud používáte **klienta Outlooku**: Pokud chcete odeslat šifrovanou zprávu z Outlooku 2013 nebo 2016 nebo Outlooku 2016 pro Mac, vyberte**Oprávnění** **možností** > , vyberte požadovanou možnost ochrany.

- Chcete-li **automaticky šifrovat všechny e-maily** odeslané určitým příjemcům nebo externím partnerským organizacím, musíte v Centru pro správu Exchange vytvořit pravidlo přenosu toku pošty. Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).

