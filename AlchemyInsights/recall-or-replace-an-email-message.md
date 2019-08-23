---
title: Odvolat nebo nahradit e-mailové zprávě
ms.author: daeite
author: daeite
manager: joallard
ms.date: 05/15/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1860"
- "9000260"
ms.assetid: ''
ms.openlocfilehash: d5952041f6f2fd736e975abf06cc22880d21a089
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36553425"
---
# <a name="recall-or-replace-an-email-message-in-office-365"></a>Odvolat nebo nahradit e-mailové zprávy ve službách Office 365

- Můžete **pouze odvolání zprávy, které jsou odesílány uživatelům ve vaší organizaci**. Pokud byla zpráva odeslána na adresu služby Gmail, například nelze odvolat ji.
- Můžete **pouze odvolání zprávy odeslané z aplikace Outlook 2016 pro PC**. Pokud uživatel odešle zprávu pomocí aplikace Outlook for Mac nebo aplikace Outlook na webu, nelze ji odvolat.
- Pokud jste správce, můžete **odvolat zpráv jménem uživatelů pomocí prostředí PowerShell**. Zprávy z středisku pro správce nemůže odvolat. Posuňte zobrazení dolů k "Hledání a odstranění e-mailových zpráv v organizaci" Další informace.

**Odvolat nebo nahradit e-mailové zprávy, které jste odeslali**

1. V podokně složek na levé straně okna aplikace Outlook vyberte složku Odeslaná pošta.
2. Otevřete zprávu, kterou chcete odvolat. Chcete-li zprávu otevřít, poklepejte na položku. Odeslanou zprávu, zobrazí se v podokně čtení nebude možné odvolat zprávu.
3. Na kartě zprávy vyberte **Akce** > **Odvolat zprávu**.
4. Zvolte **Odstranit nepřečtené kopie zprávy** nebo **Odstranit nepřečtené kopie a nahradit novou zprávu**a potom klepněte na tlačítko **OK**.
5. Pokud posíláte zprávu náhradní, napsat zprávu a pak vyberte příkaz **Odeslat**.
6. Úspěšnost odvolání zprávy závisí na nastavení příjemců v aplikaci Outlook.

Další informace včetně Kontrola odvolání, [odvolání](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0)nebo nahrazení e-mailové zprávy, které jste odeslali.

***Vyhledání a odstranění e-mailových zpráv v organizaci*** Vyhledání a odstranění e-mailových zpráv v organizaci, je nejjednodušší Pokud jste globální správce. Pokud si nejste globální správce, musí váš účet přidán do skupiny rolí správce služba eDiscovery nebo řídící role hledání shody. Chcete-li odstranit zprávy, musíte připojit ke skupině rolí Správa organizace nebo řídící role hledání a vymazat. Do [centra kompatibility & zabezpečení](https://protection.office.com/)jsou přiřazena oprávnění k těmto rolím.

1. [Hledání obsahu vytvořit](https://docs.microsoft.com/office365/securitycompliance/content-search) zprávu odstranit.
2. [Připojení k prostředí PowerShell centra kompatibility & zabezpečení](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps). 

Pokud používáte MFA, naleznete v tématu [připojit k zabezpečení Office 365 & PowerShell Centrum kompatibility pomocí vícenásobné ověření](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps). 
