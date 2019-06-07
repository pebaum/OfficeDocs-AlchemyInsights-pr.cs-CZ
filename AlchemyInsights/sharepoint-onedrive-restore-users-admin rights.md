---
title: Udělit uživatelům přístup k webu služby SharePoint a OneDrive
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a689769dab24e12832ddc0937bc5ddc3d71dbee3
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34759249"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Udělit uživatelům přístup k webu služby SharePoint a OneDrive

Tento problém nastává nejčastěji v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport). Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID. Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU). Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.

Chcete-li vyřešit tento problém by mělo obnovit původní hlavní název uživatele pomocí kroků popsaných v následujícím článku[obnovení uživatele ve službách Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Po dokončení se můžete ověřit, zda že má uživatel práva správce k webu OneDrive pomocí následujícího postupu chcete-li [Přidat admin je pro uživatele OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)

Další informace o úrovních oprávnění naleznete v článku [Principy úrovněmi oprávnění služby SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).
