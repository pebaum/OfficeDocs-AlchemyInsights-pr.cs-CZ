---
title: Problémy s MFA
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: 276f6b2212c9d85df726cb46a46dee7828b34c89
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36545152"
---
# <a name="issues-with-mfa"></a>Problémy s MFA
Existuje několik věcí, chcete-li zkontrolovat, pokud uživatelé nelze přihlásit pomocí vícenásobné ověření (MFA)

1. V Azure Active Directory portálu mohou být blokovány příslušného uživatele. Pokud tomu tak je, pokusy o ověření, pro který bude uživatel automaticky zamítnut. [Postupujte podle kroků v tomto článku, chcete-li zrušit jejich blokování.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Pokud vám nepomohlo odblokování uživatele nebo uživatel nebyl blokován můžete zkusit obnovit MFA pro uživatele a přejde prostřednictvím procesu zapsat znovu. [Postupujte podle kroků v tomto článku.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

Pokud je to poprvé MFA povoleno a uživatelé se nelze se přihlásit k jiné prohlížeče klientů aplikace Outlook, Skype atd, případně ADAL (Active Directory ověřování knihovny) není povolena na předplatné O365. V takovém případě musíte se připojit k serveru Exchange Online Powershell a spustit tuto rutinu:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*