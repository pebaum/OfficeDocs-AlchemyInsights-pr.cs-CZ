---
title: Poradce při potížích s odezírem zpráv o přístupu na weby OneDrivu pro firmy
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a83936acf969926c113b28ceb22b006cdb96e2b4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692794"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Poradce při potížích s odezírem zpráv o přístupu na weby OneDrivu pro firmy

K tomuto problému nejčastěji dochází při odstranění uživatele a znovu vytvořit se stejným hlavním jménem uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID). Když se uživatel pokusí o přístup k kolekci webů nebo k jejich OneDrivu, má nesprávný PUID. Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU). Pokud se uživatelé už přihlásili ke SharePointu a potom jsou přesunuti do jiné oua nové ou a znovu synchronizováni se službou SharePoint, může se u nich vyskytnout tento problém.

1. Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní název uživatele s kroky v [článku, Obnovení uživatele v Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).
2. Pokud nemůžete obnovit původního uživatele, měli byste starého uživatele odebrat z webu OneDrivu pomocí těchto kroků, [odebrat uživatele ze seznamu uživatelských informací](). 
3. Po dokončení můžete ověřit, že uživatel má práva správce webu OneDrive podle pokynů k [přidání správce pro OneDrive uživatele.](https://docs.microsoft.com/sharepoint/manage-user-profiles)

Další informace o úrovních oprávnění najdete v článku [Principy úrovní oprávnění v SharePointu](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
