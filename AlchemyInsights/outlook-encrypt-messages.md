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
ms.openlocfilehash: 6bbbf8722dacb8b7d5191d57ce1055a48dcb4dd0
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511501"
---
# <a name="encrypt-email-messages-in-outlook"></a>Šifrování e-mailových zpráv v Outlooku

Microsoft 365 Message Encryption je založený na Microsoft Azure Rights Management (Azure RMS), který je součástí Azure Information Protection. Pokud vaše předplatné zahrnuje Azure Rights Management nebo Azure Information Protection, **nemusíte provádět žádné akce k ručnímu povolení nebo aktivaci** služby Rights Management Service.

Na základě zpětné vazby od zákazníků už nebudeme povolovat pravidlům toku pošty Exchange automaticky šifrovat odchozí e-maily obsahující určitý typ citlivých informací ve vašem tenantovi ve výchozím nastavení. Místo toho poskytujeme podrobné pokyny, jak to můžete udělat sami. Další podrobnosti o tom, jak vytvořit pravidlo přenosu pro šifrování citlivých informací, naleznete [v tomto článku](https://aka.ms/OmeEtr).

- Pokud používáte Outlook na webu (dříve **OWA**): Při vytváření e-mailové zprávy jednoduše klikněte na **Chránit** v aplikaci OWA. To bude platit "Nepřeposílat" oprávnění. Klikněte na **Změnit oprávnění** a zvolte **Šifrovat,** chcete-li zprávu zašifrovat.

- Pokud používáte **Outlook client**: Pokud chcete odeslat šifrovanou zprávu z Outlooku 2013 nebo 2016 nebo Outlooku 2016 pro Mac, vyberte **Options**  >  **Možnosti oprávnění**a vyberte možnost ochrany, kterou potřebujete.

- Chcete-li **automaticky šifrovat všechny e-maily** odeslané určitým příjemcům nebo externím partnerským organizacím, musíte v Centru pro správu Exchange vytvořit pravidlo přenosu toku pošty. Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email#create-mail-flow-rules-to-encrypt-email-messages-with-the-new-ome-capabilities).

