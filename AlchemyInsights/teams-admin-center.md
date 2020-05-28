---
title: Centrum pro správu Teams
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002890"
- "5542"
ms.openlocfilehash: d504a26ee6532ec291eae797b1c81d86a05414b0
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/23/2020
ms.locfileid: "44354081"
---
# <a name="teams-admin-center"></a>Centrum pro správu Teams

Přečtěte si informace o správě Teams pomocí [centra pro správu Teams](https://docs.microsoft.com/microsoftteams/manage-teams-skypeforbusiness-admin-center).

Pokud nemůžete získat přístup k centru pro správu Teams, zkontrolujte následující položky:

- Zkontrolujte, jestli jste povolili příslušné [IP adresy a adresy URL Office 365](https://docs.microsoft.com/Office365/Enterprise/office-365-ip-web-service) na hraničních zařízeních (bráně firewall atd.) nebo v pravidlech brány firewall na místním počítači.
- Zkontrolujte, jestli přihlašovací jméno, které používáte pro přístup k portálu pro správu Teams, odpovídá vašemu uživatelskému jménu uvedenému na [portálu pro správu Microsoft 365](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/users).

Pokud se v centru pro správu Teams neobjevují uživatelé, zkontrolujte následující položky:

- Vytvořili jste v posledních 24 hodinách uživatele nebo přiřazovali licence? Než otevřete lístek podpory, počkejte alespoň 24 hodin.
- Ověřte, že jste přiřadili správné licence.
- Pokud máte místní službu Active Directory, ověřte, zda [je hodnota adresy msRTCSIP-PrimaryUserAddress nebo adresy SIP v poli ProxyAddresses v místní službě Active Directory jedinečná a formát odpovídá](https://docs.microsoft.com/skypeforbusiness/troubleshoot/online-configuration/msrtcsip-primaryuseraddress-proxyaddaddress) sip: Uživatelské**jméno** uživatele z Centra [pro správu společnosti Microsoft 365](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/users).
- Pokud chcete zachovat nasazení serveru Skypu pro firmy a mít uživatele v místním prostředí a online: postupujte podle **pokynů "Nastavení hybridu s týmy a Online Skype pro firmy"** v ovládacím panelu serveru Skypu pro firmy a přesuňte uživatele online.
