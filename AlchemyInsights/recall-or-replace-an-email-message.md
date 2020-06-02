---
title: Odvolání nebo nahrazení e-mailové zprávy
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: e958dab159e4dcc11f9c068bded3aa06ccd65c15
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509449"
---
# <a name="recall-or-replace-an-email-message-in-microsoft-365"></a>Odvolání nebo nahrazení e-mailové zprávy v Microsoftu 365

- Můžete **vyvolat pouze zprávy, které jsou odesílány lidem ve vaší organizaci**. Pokud byla například zpráva odeslána na adresu Gmailu, nemůžete si ji vzpomenout.
- Můžete **vyvolat jenom zprávy odeslané z Outlooku 2016 pro PC**. Pokud uživatel odešle zprávu pomocí Outlooku for Mac nebo Outlooku na webu, nemůžete si ji vzpomenout.
- Pokud jste správce, můžete **odvolat zprávy jménem uživatelů pomocí Prostředí PowerShell**. Zprávy z Centra pro správu si nemůžete naspojovat. Další informace získáte posuňte dolů na "Vyhledat a odstranit e-mailové zprávy ve vaší organizaci".

**Odvolání nebo nahrazení odeslané e-mailové zprávy**

1. V podokně složek vlevo od okna Outlooku zvolte složku Odeslaná pošta.
2. Otevřete zprávu, kterou chcete odvolat. Chcete-li zprávu otevřít, je nutné poklepáním. Výběrem zprávy tak, aby se zobůzvu byla v podokně čtení, zpráva se nezobrazí.
3. Na kartě Zpráva vyberte **Akce**  >  **navrácení této zprávy**.
4. Zvolte **Odstranit nepřečtené kopie této zprávy** nebo Odstranit **nepřečtené kopie a nahradit novou zprávou**a pak vyberte **OK**.
5. Pokud odesíláte náhradní zprávu, vytvořte zprávu a pak vyberte **Odeslat**.
6. Úspěch nebo neúspěch odvolání zprávy závisí na nastavení příjemců v aplikaci Outlook.

Další informace, včetně kontroly odvolání, najdete v tématu [Odvolání nebo nahrazení odeslané e-mailové zprávy](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

***Hledání a odstraňování e-mailových zpráv ve vaší organizaci*** Pokud chcete ve vaší organizaci vyhledávat a odstraňovat e-mailové zprávy, je to nejjednodušší, pokud jste globální správce. Pokud nejste globální správce, musí být váš účet přidán do skupiny rolí správce eDiscovery nebo do role správy vyhledávání dodržování předpisů. Chcete-li odstranit zprávy, musíte se připojit ke skupině rolí Správa organizace nebo k roli správy Hledání a čištění. Oprávnění k těmto rolím jsou přiřazena v [Centru dodržování předpisů & zabezpečení](https://protection.office.com/).

1. [Vytvořte hledání obsahu](https://docs.microsoft.com/microsoft-365/compliance/content-search) a najděte zprávu, kterou chcete odstranit.
2. [Připojte se k prostředí PowerShell Centra pro zabezpečení & dodržování předpisů](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Pokud používáte vícefaktorové ověřování, přečtěte si přečtěte si informace [o připojení k Microsoftu 365 security & Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
