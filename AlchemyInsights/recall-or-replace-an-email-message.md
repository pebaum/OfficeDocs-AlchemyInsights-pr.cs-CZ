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
ms.openlocfilehash: e541620a499b02a7206579ffcc505ceb4e632a4c
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742748"
---
# <a name="recall-or-replace-an-email-message-in-microsoft-365"></a>Odvolání nebo nahrazení e-mailové zprávy v Microsoftu 365

- Můžete **vyvolat pouze zprávy, které jsou odesílány lidem ve vaší organizaci**. Pokud byla například zpráva odeslána na adresu Gmailu, nemůžete si ji odvolat.
- Můžete **vyvolat jenom zprávy odeslané z Outlooku 2016 pro pc**. Pokud uživatel odešle zprávu pomocí Outlooku for Mac nebo Outlooku na webu, nemůžete si ji odvolat.
- Pokud jste správce, můžete **odvolat zprávy jménem uživatelů pomocí Prostředí PowerShell**. Zprávy z Centra pro správu nelze odvolat. Další informace získáte posunutím dolů k možnosti Vyhledat a odstranit e-mailové zprávy ve vaší organizaci.

**Odvolání nebo nahrazení odeslané e-mailové zprávy**

1. V podokně složek nalevo od okna Outlooku zvolte složku Odeslané položky.
2. Otevřete zprávu, kterou chcete odvolat. Chcete-li zprávu otevřít, musíte poklepat. Výběr zprávy tak, aby se zobrazila v podokně čtení, vám neumožní zprávu odvolat.
3. Na kartě Zpráva vyberte **akce** > **Odvolat tuto zprávu**.
4. Zvolte **Odstranit nepřečtené kopie této zprávy** nebo Odstranit **nepřečtené kopie a nahradit novou zprávou**, pak vyberte **OK**.
5. Pokud odesíláte náhradní zprávu, nastavte ji a pak vyberte **Odeslat**.
6. Úspěch nebo neúspěch odvolání zprávy závisí na nastavení příjemců v aplikaci Outlook.

Další informace, včetně způsobu kontroly na odvolání, naleznete v [tématu Odvolat nebo nahradit e-mailovou zprávu, kterou jste odeslali](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

***Hledání a odstraňování e-mailových zpráv ve vaší organizaci*** Pokud chcete v yomické organizaci vyhledávat a odstraňovat e-mailové zprávy, je to nejjednodušší, pokud jste globální správce. Pokud nejste globální správce, musí být váš účet přidán do skupiny rolí správce eDiscovery nebo do role Správa vyhledávání dodržování předpisů. Chcete-li odstranit zprávy, budete se muset připojit ke skupině rolí Správa organizace nebo ke správě hledání a vymazání. Oprávnění k těmto rolím jsou přiřazena v [Centru dodržování předpisů & zabezpečení](https://protection.office.com/).

1. [Vytvořte hledání obsahu a](https://docs.microsoft.com/office365/securitycompliance/content-search) vyhledejte zprávu, kterou chcete odstranit.
2. [Připojte se k prostředí PowerShell centra dodržování předpisů & zabezpečení](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Pokud používáte vícefaktorovou amaf, [přečtěte si informace o připojení k zabezpečení Microsoft u 365 & Prostředí PowerShell centra dodržování předpisů pomocí vícefaktorového ověřování](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
