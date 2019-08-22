---
title: E-mailu pracovního postupu nebyla odeslána.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 261fe1b1bc815dd4ad568051cfefad1e214b957e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530859"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>Pracovního e-mailu není odeslán do knihovny nebo seznamu SharePoint

1. E-mailu z pracovní postupy nejsou odeslány všem uživatelům nebo pouze pro určité uživatele nebo zobrazí že chybová **e-mailovou zprávu nelze odeslat. Ujistěte se, e-mailu je platný příjemce**.

    Zkontrolujte, zda uživatel existuje ve skupině oprávnění **Všem uživatelům** (seznam informací o uživatelích) pro danou kolekci webů.  Ukázka přímé URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0

    - Pokud uživatel neexistuje, zkontrolujte, zda že uživatel je přihlášen do stránky. 
    - Pokud je externí uživatel, ujistěte se, že jejich pozvání byla přijata.
    - Pokud uživatel neexistuje ve skupině oprávnění, zkontrolujte, zda že e-mailová adresa je správná.
    - Pokud zde není nastavena e-mailová adresa uživatele, vytvořte ukázkové oznámení pro uživatele vynutí synchronizaci s uživatelským účtem z uživatelské profily služby SharePoint do této kolekce webů.
 
2. E-mailu z pracovních postupů jsou odesílány správci kolekce webů, ale nikoli pro ostatní uživatele a zobrazí chyba **HTTP Zakázáno <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.
 

    V části [Přístup odepřen při odeslání e-mailu skupině SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Ověřte také, zda není aktivní funkce kolekce webů **režim uzamčení oprávnění uživatele omezený přístup** .


## <a name="related-topics"></a>Související témata
Chcete vyzkoušet Microsoft Flow v Online služby SharePoint?
- [Vytvoření toku](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint a toku](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


