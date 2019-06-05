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
ms.openlocfilehash: ae4d2c00be6387744bdc84e1d8a021530f80f8fa
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/04/2019
ms.locfileid: "34715205"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a>Udělit uživatelům přístup k webu služby SharePoint a OneDrive

<p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Tento problém nastává nejčastěji v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport). Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID. Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU). Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.</span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">K vyřešení tohoto problému by mělo obnovit původní hlavní název uživatele pomocí kroků popsaných v následujícím článku <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">obnovení uživatele ve službách Office 365.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Po dokončení se můžete ověřit má uživatel práva správce k webu OneDrive pomocí následujících kroků k <a href="https://docs.microsoft.com/en-us/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive">Přidat admin uživatele pro uživatele OneDrive.</a></span></p> <p><span style="mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;">Další informace o úrovních oprávnění, naleznete v článku <a href="https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels">Principy úrovní oprávnění ve službě SharePoint.</a>&nbsp;</span></p>
