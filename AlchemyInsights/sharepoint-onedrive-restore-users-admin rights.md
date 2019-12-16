---
title: Odstraňování problémů s odepřeným přístupem k serverům OneDrive pro podnikové weby
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 9d8aba4e53a1e0505a430296bb1c11713ea2ce7b
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051598"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Odstraňování problémů s odepřeným přístupem k serverům OneDrive pro podnikové weby

K tomuto problému nejčastěji dochází, když je uživatel odstraněn a znovu vytvořen se stejným hlavním uživatelským jménem (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID). Když se uživatel pokusí o přístup k kolekci webů nebo k jejich objektu OneDrive, má uživatel nesprávný identifikátor PUID. Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory. Pokud se uživatelé již přihlásili ke službě SharePoint a pak jsou přesunuté do jiné organizační jednotky a znovu synchronizovány se službou SharePoint, mohou k tomuto problému dojít.

1. Chcete-li tento problém vyřešit, obnovte původní název UPN podle kroků v článku, [obnovte uživatele v sadě Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).
2. Pokud původní uživatel nelze obnovit, měli byste odebrat původního uživatele z webu OneDrive pomocí těchto kroků, a [Odebrat uživatele ze seznamu informací o uživateli](). 
3. Po provedení této funkce můžete ověřit, zda má uživatel oprávnění správce k webu OneDrive, a to podle kroků, které slouží k [Přidání správce na server OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive) .

Další informace o úrovních oprávnění naleznete v článku s [Principy úrovní oprávnění ve službě SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
