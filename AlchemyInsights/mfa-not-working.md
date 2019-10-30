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
ms.openlocfilehash: a415116b9ba437cb13426896119cd1b40d9ab491
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768830"
---
# <a name="issues-with-azure-mfa"></a>Problémy s Azure MFA
Existuje několik možností, jak zkontrolovat, zda se uživatelé nemohou přihlásit pomocí vícefaktorového ověřování (MFA).

1. Ohrožený uživatel může být blokován na portálu Azure Active Directory Portal. V takovém případě budou pokusy o ověření pro tohoto konkrétního uživatele automaticky odepřeny. [Chcete-li je odblokovat, postupujte podle kroků v tomto článku.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. Pokud odblokování uživateli nepomůže nebo uživatel není blokován, můžete se pokusit resetovat MFA pro uživatele a znovu projít procesem zápisu. [Postupujte prosím podle pokynů v tomto článku.](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

V případě, že jste poprvé povolili službu MFA a uživatelé se nemohou přihlásit k jiným klientům než prohlížečům, jako je například aplikace Outlook, Skype atd., není v odběru O365 pravděpodobně povolena služba AD Al (Active Directory Authentication Library). V takovém případě se budete muset připojit k serveru Exchange Online PowerShell a spustit tuto rutinu:  *set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*