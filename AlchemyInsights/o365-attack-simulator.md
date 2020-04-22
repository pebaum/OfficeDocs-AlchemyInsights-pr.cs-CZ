---
title: 2681 Attack Simulator v Microsoftu 365
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
ms.openlocfilehash: 74bd2dd62b24aaf6c9d7b387ab1d97ddab31e902
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713459"
---
# <a name="attack-simulator-in-microsoft-365"></a>Simulátor útoku v Microsoftu 365

- Chybí vám Attack Simulator? Simulátor útoků vyžaduje **plán ochrany před pokročilými hrozbami Office 365 2 (ATP Plan 2)** nebo **Office 365 Enterprise E5**. Attack Simulator **není** součástí Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3 nebo žádné předplatná Microsoft 365 Apps pro firmy.

- Účet, který používáte ke spuštění simulovaných útoků, vyžaduje oprávnění globálního správce nebo správce zabezpečení a vícefaktorové ověřování (MFA). Další informace o požadavcích simulátoru útoku naleznete v [tomto tématu](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).

- Důležité věci, které je třeba vědět o simulacích útoku **Brute Force Password:**

  - Pokud cílový účet má mfa povoleno a heslo bylo uhádnuto správně, účet se nezobrazí jako ohrožena (druhý faktor ověřování bude neúplné).

  - Soubor s heslem nesmí být větší než 10 MB. Použijte jedno heslo na řádek a za poslední heslo v seznamu uveďte prázdný řádek (návrat vozíku).

- Důležité informace o **spear phishing připojit** simulace:

  - Podle návrhu nelze zadat vlastní hodnotu adresy **URL přihlašovacího serveru phishing**.

  - Pokud příjemce používá [doplněk Povolit zprávu sestavy](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) k nahlášení zprávy jako phishing, nemusí se vám na zprávu zobrazit upozornění (protože se jedná o simulovaný útok).

- Sestavy: Po dokončení simulovaného útoku můžete přehled zobrazit kliknutím na **Podrobnosti útoku.**

- Podrobné pokyny a nové funkce v Attack Simulator, naleznete [v tématu Attack Simulator v Microsoftu 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).
