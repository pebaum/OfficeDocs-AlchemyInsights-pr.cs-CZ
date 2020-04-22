---
title: Vyvolání nebo nahrazení e-mailové zprávy v Outlooku Desktopu
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: d64332778f9132aff6a9660bb0d522f4e16b753c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687503"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Odvolání nebo nahrazení e-mailové zprávy outlooku

- Jako správce můžete **odvolat zprávy jménem uživatelů pomocí prostředí PowerShell**. Zprávy z Centra pro správu nelze odvolat.
- Můžete **vyvolat pouze zprávy, které jsou odesílány lidem ve vaší organizaci**. Pokud byla například zpráva odeslána na adresu Gmailu, nemůžete si ji odvolat.
- Můžete **vyvolat jenom zprávy odeslané z Outlooku 2016 na počítači**. Pokud uživatel odešle zprávu pomocí Outlooku for Mac nebo Outlooku na webu, nemůžete si ji odvolat.

Odvolání nebo nahrazení e-mailové zprávy:

1. V podokně složek nalevo od okna Outlooku vyberte složku Odeslané položky.
1. Poklikáním na zprávu, kterou chcete vyvolat, ji otevřete.
1. Vyberte kartu **Zpráva** a pak vyberte **akce** > **Odvolat tuto zprávu**.
1. Vyberte **Odstranit nepřečtené kopie této zprávy** nebo Odstranit **nepřečtené kopie a nahraďte ji novou zprávou**a pak vyberte **OK**.
1. Pokud odesíláte náhradní zprávu, nastavte ji a pak vyberte **Odeslat**.
1. Úspěch nebo neúspěch odvolání zprávy závisí na nastavení příjemce v aplikaci Outlook. Postup kontroly odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Hledání a odstraňování e-mailových zpráv ve vaší organizaci

- Pokud nejste globální správce, musí být váš účet přidán do role správce eDiscovery nebo ke správě vyhledávání dodržování předpisů, abyste mohl vyhledávat zprávy. Chcete-li odstranit zprávy, budete se muset připojit ke skupině rolí Správa organizace nebo ke správě hledání a vymazání. Oprávnění pro tyto role jsou přiřazena v [Centru zabezpečení a dodržování předpisů](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Vytvořte hledání obsahu a](https://docs.microsoft.com/office365/securitycompliance/content-search) vyhledejte zprávu, kterou chcete odstranit.
- [Připojte se k prostředí PowerShell centra zabezpečení a dodržování předpisů](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Pokud používáte vícefaktorové ověřování, [přečtěte si informace o připojení k prostředí Microsoft 365 security and Compliance Center PowerShell pomocí vícefaktorového ověřování](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).