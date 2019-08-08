---
title: Poradce při potížích s přístup odepřen zprávy OneDrive pro obchodní sítě
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: d47ce80bdd07a25d9724057edf0289808a00a3db
ms.sourcegitcommit: 8a83b508785c96c19648ed574f442bbef2c2dff9
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/07/2019
ms.locfileid: "36232513"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a>Poradce při potížích s přístup odepřen zprávy OneDrive pro obchodní sítě

Tento problém nastává nejčastěji v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport). Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID. Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU). Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.

1. Chcete-li vyřešit tento problém by mělo obnovit původní hlavní název uživatele pomocí kroků popsaných v následujícím článku[obnovení uživatele ve službách Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).
2. Pokud nemůžete obnovit původní uživatele byste měli odebrat staré uživatele z webu OneDrive pomocí těchto kroků [Odebrat uživatele ze seznamu informací o uživatelích](). 
3. Po dokončení se můžete ověřit, zda že má uživatel práva správce k webu OneDrive pomocí následujícího postupu chcete-li [Přidat admin je pro uživatele OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)

Další informace o úrovních oprávnění naleznete v článku [Principy úrovněmi oprávnění služby SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
