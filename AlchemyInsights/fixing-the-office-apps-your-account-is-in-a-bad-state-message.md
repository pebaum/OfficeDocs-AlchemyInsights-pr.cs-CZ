---
title: Oprava aplikací Office Váš účet je ve špatné zprávě o stavu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969319"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a>Oprava chyby aplikací Office "Váš účet je ve špatném stavu"

Chcete-li tuto chybu opravit, vyzkoušejte v ohroženém počítači následující možnosti:

- Otevřete aplikaci Office a vyberte **Souborový** > **účet** > **Odhlásit ze všech účtů**. Znovu se přihlaste pomocí uživatelského účtu s platnou licencí. Podrobné informace naleznete v tématu [Účty v Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).
- [Vymazání přihlašovacích údajů sady Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.<br>
  **Poznámka:** Cesty registru pro Office 2016 se změnily na 16.0. Například \Software\Microsoft\Office\16.0\Common\Identity\
- V ohroženém počítači nastavte enableadal = 0 pomocí následujících kroků:  
     1. Klepněte pravým tlačítkem myši na tlačítko Windows a vyberte **Spustit**. Do pole **Otevřít** zadejte **příkaz regedit**a vyberte **OK**.
     2. Vyberte **Ano,** pokud budete vyzváni, aby editor registru mohl v zařízení provádět změny.
    3. V Editoru registru přidejte hodnotu DWORD enableadal s nastavením 0 v části HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.
- Pokud k chybě dojde při připojování k Office 365 pomocí Office 2013, [povolte moderní ověřování](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) pro klienta Office.

Další informace najdete v tématu [Řešení potíží s aplikacemi, které nepoužívají prohlížeče a které se nemohou přihlásit k Office 365, Azure nebo Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).

