---
title: Plocha aplikace Outlook odvolání nebo nahrazení e-mailové zprávy
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 3d3a6c253317137b7069a978b907c97d61bf7313
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36496104"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Odvolání nebo nahrazení e-mailové zprávy aplikace Outlook

- Jako správce můžete **odvolat zprávy jménem uživatelů používajících prostředí PowerShell**. Nelze odvolat zprávy z centra pro správu.
- Můžete **odvolat pouze zprávy, které jsou odeslány osobám v organizaci**. Pokud byla zpráva odeslána například na adresu Gmail, nemůžete ji odvolat.
- Můžete **odvolat pouze zprávy odesílané z aplikace Outlook 2016 v počítači**. Pokud uživatel odešle zprávu pomocí aplikace Outlook pro Mac nebo Outlook na webu, nemůžete ji odvolat.

Odvolání nebo nahrazení e-mailové zprávy:

1. V podokně složek v levé části okna aplikace Outlook vyberte složku Odeslaná pošta.
1. Poklepejte na zprávu, kterou chcete odvolat.
1. Vyberte kartu **zpráva** a pak vyberte **Akce** > **odvolání této zprávy**.
1. Vyberte možnost **Odstranit nepřečtené kopie zprávy** nebo **odstraňte nepřečtené kopie zprávy a nahraďte je novou zprávou**a pak klepněte na **tlačítko OK**.
1. Pokud posíláte náhradní zprávu, vytvořte ji a pak klepněte na **Odeslat**.
1. Úspěch nebo neúspěch navrácení zprávy závisí na nastavení příjemce v aplikaci Outlook. Postup kontroly odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Hledání a odstraňování e-mailových zpráv v organizaci

- Pokud nejste globálním správcem, musí být váš účet přidán do role správce eDiscovery nebo do role správy hledání podle požadavků a vyhledávat zprávy. Chcete-li zprávy odstranit, je nutné se připojit ke skupině rolí Správa organizace nebo pro správu hledání a čištění. Oprávnění pro tyto role jsou přiřazovány v [Centru zabezpečení a kompatibility](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Vytvořte hledání obsahu](https://docs.microsoft.com/office365/securitycompliance/content-search) , abyste našli zprávu, kterou chcete odstranit.
- [Připojte se k prostředí PowerShell zabezpečení a kompatibility](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Používáte-li vícefaktorové ověřování, naleznete další informace v tématu [připojení k sadě Office 365 Security and Compliance Center PowerShell s využitím vícefaktorového ověřování](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).