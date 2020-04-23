---
title: E-mail pracovního postupu se neodesílá
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 391d3a2dcc2676a405065115f375c802d2492119
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766126"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>E-mail pracovního postupu se neodesílá pro sharepointový seznam nebo knihovnu.

1. E-maily z pracovních postupů nejsou odesílány všem uživatelům nebo pouze konkrétním uživatelům nebo se zobrazí chyba **E-mailovou zprávu nelze odeslat. Zkontrolujte, zda má e-mail platného příjemce**.

    Zkontrolujte, zda uživatel pro tuto kolekci webů existuje ve skupině Oprávnění **Všichni lidé** (seznam informací o uživateli).  Ukázka přímé<tenant>adresy<sitename>URL: https:// .sharepoint.com/sites/ /_layouts/15/people.aspx? ČlenstvíGroupId=0

    - Pokud uživatel neexistuje, ujistěte se, že je uživatel přihlášen ke stránce. 
    - Pokud se jedná o externího uživatele, ujistěte se, že jeho pozvání bylo přijato.
    - Pokud uživatel existuje ve skupině oprávnění, ujistěte se, že e-mailová adresa je správná.
    - Pokud zde není nastavena e-mailová adresa uživatelů, vytvořte pro tohoto uživatele ukázkovou výstrahu, která vynutí synchronizaci tohoto uživatelského účtu z uživatelských profilů služby SharePoint do této kolekce webů.
 
2. E-maily z pracovních postupů jsou odesílány správcům kolekce webů, ale ne ostatním uživatelům a zobrazí se chyba **HTTP Forbidden to <span>https:</span>//URL/_vti_bin/client.xvc.sp.utilities.utility.SendEmail**.
 

    Viz [Přístup byl odepřen při odeslání e-mailu skupině SharePointu](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Ověřte také, zda funkce kolekce webů **režimu uzamčení uživatelských oprávnění s omezeným přístupem** není aktivní.


## <a name="related-topics"></a>Související témata
Chcete vyzkoušet Microsoft Flow na SharePointu Online?
- [Vytvořit tok](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint a tok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


