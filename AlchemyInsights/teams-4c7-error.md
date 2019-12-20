---
title: Týmy 4c7 Error
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3472"
- "9001211"
ms.openlocfilehash: 0945a341c6456ee4178c0485f3bfb9232fa78a11
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796024"
---
# <a name="4c7-error-in-microsoft-teams"></a>Chyba 4c7 v týmu Microsoft

K této chybě dochází, protože týmy Microsoft vyžadují ověřování pomocí formulářů. Pokud nasadíte službu AD FS (Active Directory Federation Services), není pro síť intranet ve výchozím nastavení povoleno ověřování pomocí formulářů. Pokud se integrované ověřování systému Windows nezdaří, zobrazí se výzva k přihlášení pomocí formulářové autentizace.

Chcete-li tento problém vyřešit, povolte ověřování formulářů pomocí modulu snap-in konzoly MMC (Microsoft Management Console) služby AD FS v počítači, který má místní kopii služby Active Directory. Uděláte to takto: 

1. V navigačním podokně přejděte na **zásady ověřování**.
2. V části **Akce** v podokně podrobností vyberte možnost **Upravit globální primární ověřování**.
3. Na kartě **intranet** vyberte možnost **ověřování pomocí formulářů**.
4. Klepněte na **tlačítko OK** (nebo **použijte**).