---
title: Oprava aplikací Office Nemůžu najít přidruženou zprávu o licencích Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3421"
- "9001426"
ms.openlocfilehash: 887be4bee2bd1562bdc3b29783e9deafe47d8d57
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505860"
---
# <a name="fixing-the-office-apps-couldnt-find-office-licenses-associated-message"></a>Oprava zprávy O opravě aplikací Office "Nelze najít přidružené licence office"

Pokud se zobrazí tato zpráva, vyzkoušejte následující postup:

1. Zkontrolujte nastavení brány firewall, antivirového softwaru a proxy serveru a ověřte, zda neblokují přístup k Internetu k aplikacím Office. Viz [Microsoft 365 URL a rozsahy IP adres](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).
2. Odeberte a [znovu přiřaďte licenci Office](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) pro postiženého uživatele. 
3. Otevřete aplikaci Office a [odhlaste se od](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) všech existujících uživatelských účtů.
4. Přejděte na Nastavení systému Windows > **účty**  >  **e-mail & účtů**a odeberte všechny pracovní účty kromě ovlivněného účtu.
5. Přejděte na Nastavení systému Windows > **Accounts**  >  **účty Přístup k práci nebo škole**a odpojte všechny pracovní účty kromě ovlivněného účtu.
6. Resetujte stav aktivace Office. [Přečtěte si, jak](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).
7. [Přihlaste se](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) pomocí ovlivněného uživatelského účtu.

Další řešení potíží najdete [v tématu Chyby nelicencovaného produktu a aktivace v Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).