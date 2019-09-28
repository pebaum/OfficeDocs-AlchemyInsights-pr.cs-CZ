---
title: 2681 simulátor útoků v sadě Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 07d7622c00074f7bd0d567185824db448f1eeef3
ms.sourcegitcommit: 7232b48bcd8bb9867d52a2f055a46ce76a58b8da
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/27/2019
ms.locfileid: "37305325"
---
# <a name="attack-simulator-in-office-365"></a>Simulátor útoků v sadě Office 365

- Chybí simulátor útoku? Simulátor útoku vyžaduje **sadu office 365 pokročilý plán ochrany proti ohrožení 2 (plán ATP 2)** nebo **Office 365 Enterprise E5**. Simulátor útoků **není zahrnut v** sadě Office 365 pokročilý plán ochrany proti ohrožení 1 (plán ATP 1), Office 365 Enterprise E3 nebo jakýkoli Office 365 firemní předplatné.

- Účet, který používáte ke spouštění simulovaných útoků, vyžaduje globální správce nebo oprávnění správce zabezpečení a vícefaktorové ověřování (MFA). Další informace o požadavcích na simulátor útoku naleznete v [tomto tématu](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).

- Důležité věci, které je třeba vědět o simulacích útoků na **hrubou sílu hesla** :

  - Pokud má cílový účet povoleno MFA a heslo bylo uhodeno správně, účet se nezobrazí jako narušený (druhý ověřovací faktor bude neúplný).

  - Soubor s hesly nesmí být větší než 10 MB. Pro každý řádek použijte jedno heslo a za poslední heslo v seznamu zahrňte prázdný řádek (návrat vozíku).

- Důležité věci, které byste měli vědět o **útoku typu Spephishing** :

  - Podle návrhu nelze zadat vlastní hodnotu pro **adresu URL přihlašovacího serveru služby phishing**.

  - Pokud příjemce používá k hlášení zprávy jako podvodnou zprávu pomocí [doplňku povolit zprávu sestavy](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) , nebudete pravděpodobně dostávat upozornění na zprávu (protože se jedná o simulovaný útok).

- Sestavy: po dokončení simulovaného útoku můžete klepnutím na tlačítko **Podrobnosti útoku** zobrazit sestavu.

- Podrobné pokyny a nové funkce v simulátoru útoku naleznete v tématu [Attack simulátoru v sadě Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).
