---
title: Poradce při potížích s odepřením zpráv accessu na weby OneDrivu pro firmy
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 95bd46e8b7a6006f3735612d9a5602fb2b2a283b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511177"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Poradce při potížích s odepřením zpráv accessu na weby OneDrivu pro firmy

K tomuto problému nejčastěji dochází, když je uživatel odstraněn a znovu vytvořen se stejným hlavním názvem uživatele (HLAVNÍ NÁZEV UŽIVATELE). Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID). Když se uživatel pokusí o přístup k kolekci webů nebo jeho OneDrive, uživatel má nesprávné PUID. Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU). Pokud se uživatelé již přihlásili ke SharePointu a potom jsou přesunuti do jiné OU a znovu se sharepointem, může se k tomuto problému vyskytnout.

1. Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní hlavní číslo uživatele s postupem v článku [Obnovení uživatele v microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).
2. Pokud nemůžete obnovit původního uživatele, měli byste odebrat starého uživatele z webu OneDrive pomocí těchto kroků, [odebrat uživatele ze seznamu s informacemi o uživateli](). 
3. Po dokončení můžete ověřit, že uživatel má práva správce na web OneDrivu podle pokynů k [přidání správce pro OneDrive uživatele.](https://docs.microsoft.com/sharepoint/manage-user-profiles)

Další informace o úrovních oprávnění naleznete v článku [Principy úrovní oprávnění v SharePointu](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
