---
title: Oprava aplikací Office Nemohla najít zprávu přidruženou k licencím office
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
ms.openlocfilehash: 565df0a05baa974a6cbac58ac6be8d78470dbc5d
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43715625"
---
# <a name="fixing-the-office-apps-couldnt-find-office-licenses-associated-message"></a>Oprava zprávy Ohledání aplikací Office "Nelze najít přidružené licence office"

Pokud se zobrazí tato zpráva, vyzkoušejte následující postup:

1. Zkontrolujte bránu firewall, antivirový software a nastavení proxy serveru a ověřte, zda neblokují přístup k Internetu aplikacím Office. Viz [Adresy URL a rozsahy IP adres společnosti Microsoft 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).
2. Odeberte a [znovu přiřaďte licenci Office](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users) pro postiženého uživatele. 
3. Otevřete aplikaci Office a [odhlaste se od](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) všech existujících uživatelských účtů.
4. Přejděte na Nastavení **systému** > Windows > účty**E-mailové účty &** a odeberte všechny pracovní účty kromě ovlivněného účtu.
5. Přejděte na nastavení **systému** > Windows > účty**přístup k práci nebo do školy**a odpojte všechny pracovní účty kromě ovlivněného účtu.
6. Resetujte stav aktivace Office. [Přečtěte si, jak](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).
7. [Přihlaste se](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) pomocí ovlivněného uživatelského účtu.

Další řešení řešení potíží naleznete v tématu [Nelicencovaný produkt a chyby aktivace v Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).