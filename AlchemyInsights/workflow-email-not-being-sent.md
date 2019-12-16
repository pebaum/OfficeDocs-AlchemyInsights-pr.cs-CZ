---
title: E-mail pracovního postupu není odeslán.
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: 76b64323c9d34d49e9c6bd77c2cc7eff6d7c5402
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049366"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>E-mail pracovního postupu není odeslán pro seznam nebo knihovnu SharePoint.

1. E-maily z pracovních postupů nejsou odesílány všem uživatelům nebo pouze určitým uživatelům nebo se zobrazí chyba, **kterou e-mailovou zprávu nelze odeslat. Zkontrolujte, zda e-mail obsahuje platného příjemce**.

    Zkontrolujte, zda uživatel existuje ve skupině oprávnění pro **všechny osoby** (seznam informací o uživatelích) pro danou kolekci webů.  Ukázka přímé adresy URL:<tenant>https://.<sitename>SharePoint.com/sites//_layouts/15/People.aspx? MembershipGroupId = 0

    - Pokud uživatel neexistuje, ujistěte se, že je uživatel přihlášen na stránku. 
    - Pokud se jedná o externího uživatele, ujistěte se, že pozvání bylo přijato.
    - Pokud uživatel existuje ve skupině oprávnění, zkontrolujte správnost e-mailové adresy.
    - Pokud zde není nastavena e-mailová adresa uživatele, vytvořte vzorovou výstrahu pro tohoto uživatele, který vynutí synchronizaci tohoto uživatelského účtu z uživatelských profilů služby SharePoint do této kolekce webů.
 
2. E-maily z pracovních postupů jsou odesílány správcům kolekcí webů, ale nikoli jiným uživatelům a zobrazí se chyba **http zakázána pro <span>https:</span>//URL/_vti_bin/Client.XVC.SP.Utilities.Utility.SendEmail**.
 

    Informace [o odepření přístupu při odeslání e-mailu skupině SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Ověřte také, zda není aktivní funkce kolekce webů v **režimu uzamčení omezeného přístupu** .


## <a name="related-topics"></a>Související témata
Chcete vyzkoušet program Microsoft Flow ve službě SharePoint Online?
- [Vytvořit tok](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [Služba SharePoint a tok](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


