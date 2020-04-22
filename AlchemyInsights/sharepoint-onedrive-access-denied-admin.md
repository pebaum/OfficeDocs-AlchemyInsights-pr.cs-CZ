---
title: Poradce při potížích se zprávami o odepření přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 82e11458529b8a49e583b1a6963a51e2a466bfd6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758382"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Poradce při potížích se zprávami o odepření přístupu v Centru pro správu Sharepointu/OneDrivu

Pokud se při pokusu o procházení Centra pro správu služby Sharepoint/OneDrive zobrazuje zpráva o odepření přístupu, ujistěte se, že jste [uživateli přiřadili licenci](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Pokud má uživatel licenci, měli byste se také ujistit, že je [mu přiřazena role správce,](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) která má přístup ke centrům pro správu.

K tomuto problému může dojít také při odstranění uživatele a znovu vytvořit se stejným hlavním jménem uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID). Když se uživatel pokusí o přístup k kolekci webů nebo k jejich OneDrivu, má nesprávný PUID. Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU). Pokud se uživatelé už přihlásili ke SharePointu a potom jsou přesunuti do jiné oua nové ou a znovu synchronizováni se službou SharePoint, může se u nich vyskytnout tento problém.

Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní název uživatele s kroky v článku [Obnovení uživatele v Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Poznámka: Pokud centrum pro správu OneDrivu nebo SharePointu není dostupné pro více uživatelů, kteří měli dříve přístup, může se napodobuje problém s dočasnou službou.  [Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).


