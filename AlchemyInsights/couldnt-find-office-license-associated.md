---
title: Oprava aplikací sady Office nelze nalézt přidruženou zprávu s licencí pro sadu Office
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
ms.openlocfilehash: 1820cdb83a1adf36b4e7d0898ecdf8097eb6f0f3
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627911"
---
# <a name="fixing-the-office-apps-couldnt-find-office-licenses-associated-message"></a>Oprava aplikací sady Office "nebyla nalezena přidružená licence k sadě Office"

Zobrazí-li se tato zpráva, postupujte takto:

1. Zkontrolujte bránu firewall, antivirový software a nastavení serveru proxy, abyste potvrdili, že neblokují internetový přístup k aplikacím sady Office. Viz [adresy URL sady Office 365 a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).
2. Odeberte a [přiřaďte licenci sady Office](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users) pro ohroženého uživatele. 
3. Otevření aplikace sady Office a [Odhlásit](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) všechny existující uživatelské účty
4. Přejděte na nastavení systému Windows > **účty** > **e-mailové & účty**a odeberte všechny pracovní účty s výjimkou ovlivněných účtů.
5. Přejděte na nastavení systému Windows > **obchodní vztahy** > **nebo škola**a odpojte všechny pracovní účty kromě ovlivněných účtů.
6. Obnovte stav aktivace sady Office. [Dozvíte se jak](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).
7. [Přihlaste se](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) pomocí ovlivněných uživatelských účtů.

Další řešení potíží naleznete v části [nelicencované produkty a chyby aktivace v sadě Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).