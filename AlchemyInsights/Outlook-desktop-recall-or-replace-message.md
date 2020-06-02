---
title: Vyvolání nebo nahrazení e-mailové zprávy v Outlooku Desktop
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: bb84363ae7d3c91750d5de789c091c7cebbbedc2
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44502312"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Odvolání nebo nahrazení e-mailové zprávy Outlooku

- Jako správce můžete **vyvolat zprávy jménem uživatelů používajících Prostředí PowerShell**. Zprávy z Centra pro správu si nemůžete naspojovat.
- Můžete **vyvolat pouze zprávy, které jsou odesílány lidem ve vaší organizaci**. Pokud byla například zpráva odeslána na adresu Gmailu, nemůžete si ji vzpomenout.
- Můžete **vyvolat pouze zprávy odeslané z Outlooku 2016 na PC**. Pokud uživatel odešle zprávu pomocí Outlooku for Mac nebo Outlooku na webu, nemůžete si ji vzpomenout.

Vyvolání nebo nahrazení e-mailové zprávy:

1. V podokně složek vlevo od okna Outlooku vyberte složku Odeslaná pošta.
1. Poklepáním na zprávu, kterou chcete odvolat, ji otevřete.
1. Vyberte kartu **Zpráva** a pak vyberte Akce **Actions**  >  **Navrácení této zprávy**.
1. Vyberte **Odstranit nepřečtené kopie této zprávy** nebo Odstranit **nepřečtené kopie a nahradit novou zprávou**a pak vyberte **OK**.
1. Pokud odesíláte náhradní zprávu, vytvořte zprávu a pak vyberte **Odeslat**.
1. Úspěch nebo neúspěch odvolání zprávy závisí na nastavení příjemce v aplikaci Outlook. Postup kontroly odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Hledání a odstraňování e-mailových zpráv ve vaší organizaci

- Pokud nejste globální správce, musí být váš účet přidán do role správce eDiscovery nebo role správy vyhledávání dodržování předpisů, aby bylo možné vyhledávat zprávy. Chcete-li odstranit zprávy, musíte se připojit ke skupině rolí Správa organizace nebo k roli správy Hledání a čištění. Oprávnění pro tyto role jsou přiřazena v [Centru zabezpečení a dodržování předpisů](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Vytvořte hledání obsahu](https://docs.microsoft.com/microsoft-365/compliance/content-search) a najděte zprávu, kterou chcete odstranit.
- [Připojte se k PowerShellu Centra zabezpečení a dodržování předpisů](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Pokud používáte vícefaktorové ověřování, přečtěte [si přečtěte si přečtěte si tématu Připojení k Microsoft 365 security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).