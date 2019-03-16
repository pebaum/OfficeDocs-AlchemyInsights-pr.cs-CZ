---
title: Stolní Odvolaná zpráva aplikace Outlook nebo nahradit e-mailové zprávě
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: aced684777ef82860b969aea8825699b78b04c5a
ms.sourcegitcommit: aad9f863bc9fd7d5522c480bd1a7d15f3a80ff4f
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/15/2019
ms.locfileid: "30657037"
---
# <a name="recall-or-replace-an-email-message"></a>Odvolat nebo nahradit e-mailové zprávě

- Jako admin můžete **odvolat zpráv jménem uživatelů pomocí prostředí PowerShell**. Zprávy z středisku pro správce nemůže odvolat.
- Můžete **pouze odvolání zprávy, které jsou odesílány uživatelům ve vaší organizaci**. Pokud byla zpráva odeslána na adresu služby Gmail, například nelze odvolat ji.
- Můžete **pouze odvolání zprávy odeslané z aplikace Outlook 2016 v počítači**. Pokud uživatel odešle zprávu pomocí aplikace Outlook for Mac nebo aplikace Outlook na webu, nelze ji odvolat.

Chcete-li odvolat nebo nahradit e-mailové zprávy:

1. V podokně složek na levé straně okna aplikace Outlook vyberte složku Odeslaná pošta.
1. Poklepejte na zprávu, kterou chcete odvolat ji otevřete.
1. Klepněte na kartu **zprávy** a potom vyberte **Akce** > **Odvolat zprávu**.
1. Vyberte **Odstranit nepřečtené kopie zprávy** nebo **Odstranit nepřečtené kopie a nahradit novou zprávu**a potom klepněte na tlačítko **OK**.
1. Pokud posíláte zprávu náhradní, napsat zprávu a pak vyberte **Odeslat**.
1. Úspěšnost odvolání zprávy závisí na nastavení příjemce v aplikaci Outlook. Kroky ke kontrole odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Vyhledání a odstranění e-mailových zpráv v organizaci

- Pokud nejste globální správce, musí být váš účet přidán do role správce služba eDiscovery nebo řídící role shody hledání k vyhledání zpráv. Chcete-li odstranit zprávy, musíte připojit ke skupině rolí Správa organizace nebo řídící role hledání a vymazat. V [Centrum zabezpečení a dodržování předpisů](https://go.microsoft.com/fwlink/?linkid=2083731)jsou přiřazena oprávnění pro tyto role.
- [Hledání obsahu vytvořit](https://docs.microsoft.com/office365/securitycompliance/content-search) zprávu odstranit.
- [Připojit se k zabezpečení a centra kompatibility prostředí PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Pokud používáte vícenásobné ověření, viz [připojení k Office 365 zabezpečení a soulad Centrum PowerShell pomocí vícenásobné ověření](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).