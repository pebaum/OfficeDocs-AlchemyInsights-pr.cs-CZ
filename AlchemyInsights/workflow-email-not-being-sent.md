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
ms.openlocfilehash: 783bf0a5721aa5db7088432c71e06cac6dc90513
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059597"
---
# <a name="workflow-email-is-not-being-sent"></a>E-mailu pracovního postupu nebyla odeslána.

1. E-mailu z pracovní postupy nejsou odeslány všem uživatelům nebo pouze pro určité uživatele nebo zobrazí že chybová **e-mailovou zprávu nelze odeslat. Ujistěte se, e-mailu je platný příjemce**.

Zkontrolujte, zda uživatel existuje ve skupině oprávnění **Všem uživatelům** (seznam informací o uživatelích) pro danou kolekci webů.  Ukázka přímé URL: https://<tenant>.sharepoint.com/sites/<sitename>/_layouts/15/people.aspx? MembershipGroupId = 0

- Pokud uživatel neexistuje, zkontrolujte, zda že uživatel je přihlášen do stránky. 
- Pokud je externí uživatel, ujistěte se, že jejich pozvání byla přijata.
- Pokud uživatel neexistuje ve skupině oprávnění, zkontrolujte, zda že e-mailová adresa je správná.
- Pokud zde není nastavena e-mailová adresa uživatele, vytvořte ukázkové oznámení pro uživatele vynutí synchronizaci s uživatelským účtem z uživatelské profily služby SharePoint do této kolekce webů.
 
2. E-mailu z pracovních postupů jsou odesílány správci kolekce webů, ale nikoli pro ostatní uživatele a zobrazí chyba **Zakázáno HTTP <spam> <spam> ** <spam> <spam>.
 

V části [Přístup odepřen při odeslaných e-mailů do skupiny](https://docs.microsoft.com/sharepoint/support/server-admin/access-denied-when-send-an-email-to-groups).

Ověřte také, zda není aktivní funkce kolekce webů **režim uzamčení oprávnění uživatele omezený přístup** .

## <a name="related-topics"></a>Související témata
- [Vytvoření toku](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint a toku](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


