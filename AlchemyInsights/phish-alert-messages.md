---
title: 2491 Upozornění e-mailové zprávy z 'Phish Doručené z důvodu nájemce nebo uživatel přepsat' zásady
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2e4efd504304da757687e697ff23374aeea31851
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758901"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a>Upozornění e-mailové zprávy z 'Phish Doručené z důvodu nájemce nebo uživatel přepsat' zásady

Výchozí zásada výstrahy s názvem "Phish Delivered z důvodu přepsání klienta nebo uživatele" byla zavedena klientům s licencemi Office 365 ATP P1 a P2. Pokud jste obdrželi toto upozornění, zde jsou kroky k prošetření:

1. Ve výstražné zprávě klikněte na **Zobrazit výstrahu** a přejděte na stránku **Výstrahy** v Centru dodržování předpisů & zabezpečení.

2. Výběrem výstrahy zobrazíte možnost **Zobrazit seznam zpráv** nebo Zobrazit zprávy v **Průzkumníkovi**. Obě tyto možnosti vás přenese k podrobnostem zprávy, která obsahuje ID zprávy. Všimněte si, že odkaz Průzkumník hrozeb bude automaticky filtrovat zprávy, které odpovídají kritériím výstrahy. V Průzkumníku hrozeb může být nutné upravit filtr data.

Phishingová zpráva byla doručena z důvodu ručně nakonfigurovaného přepsání:

- Povolený odesílatel nebo doména nastavená uživatelem.

- Povolený odesílatel nebo doména nastavená správcem v zásadách ochrany proti nevyžádané poště.

- Povolená adresa IP v zásadách filtru připojení.

- Pravidlo toku pošty (označované také jako pravidlo přenosu), které je nakonfigurováno tak, aby umožňovalo zprávy.

Pokud se domníváte, že zpráva byla nesprávně označena jako phish, použijte [doplněk Zprávy aplikace](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) Outlook k odeslání ukázek zpráv společnosti Microsoft.
