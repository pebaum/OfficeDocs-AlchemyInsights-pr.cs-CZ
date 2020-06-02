---
title: Simulátor útoku 2681 v Microsoftu 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 3dae4768ca62757ce7f92dfc527078c963d72742
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506731"
---
# <a name="attack-simulator-in-microsoft-365"></a>Simulátor útoku v Microsoftu 365

- Chybí vám simulátor útoku? Simulátor útoku vyžaduje **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** nebo **Office 365 Enterprise E5**. Simulátor útoku **není** součástí plánu ochrany před pokročilými hrozbami Office 365 1 (plán ATP 1), Office 365 Enterprise E3 ani v žádných předplatných aplikací Microsoft 365 pro firmy.

- Účet, který používáte ke spuštění simulovaných útoků, vyžaduje oprávnění globálního správce nebo správce zabezpečení a vícefaktorové ověřování (MFA). Další informace o požadavcích simulátoru útoku naleznete [v tomto tématu](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).

- Důležité věci vědět o simulacích útoku **hesla Hrubou silou:**

  - Pokud má cílový účet povoleno vícefaktorové ověřování a heslo bylo správně uhodnout, účet se nezobrazí jako ohrožené (druhý faktor ověřování bude neúplný).

  - Soubor s heslem nesmí být větší než 10 MB. Použijte jedno heslo na řádek a za poslední heslo v seznamu zahrňte prázdný řádek (návrat vozíku).

- Důležité věci vědět o **Spear Phishing** připojit simulace:

  - Podle návrhu nelze poskytnout vlastní hodnotu adresy URL serveru pro **přihlášení k podvodným zprávám**.

  - Pokud příjemce používá [doplněk Povolit zprávu](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) k nahlášení zprávy jako phishingu, nemusí se na zprávu zobrazit upozornění (protože se jedná o simulovaný útok).

- Zprávy: Po dokončení simulovaného útoku můžete zprávu zobrazit kliknutím na **Podrobnosti útoku.**

- Podrobné pokyny a nové funkce v simulátoru útoků naleznete v [tématu Attack Simulator v Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).
