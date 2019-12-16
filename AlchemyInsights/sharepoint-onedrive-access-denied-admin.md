---
title: Odstraňování problémů se zprávami o odepření přístupu
ms.author: pebaum
author: pebaum
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 57919e6dbd81a5bf3b17fb067485e8eec23b7d4c
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051418"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Odstraňování problémů se zprávami o odepření přístupu v centru pro správu SharePoint/OneDrive

Pokud se při pokusu o přechod do centra pro správu služby SharePoint/OneDrive zobrazuje zpráva o odepření přístupu, ujistěte se, že jste [uživateli přiřadili licenci](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Pokud má uživatel licenci, měli byste také zajistit, aby jim byla [přidělena role správce](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) , která má přístup k centrům správy.

K tomuto problému může dojít také v případě, že je uživatel odstraněn a znovu vytvořen se stejným hlavním uživatelským jménem (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID). Když se uživatel pokusí o přístup k kolekci webů nebo k jejich objektu OneDrive, má uživatel nesprávný identifikátor PUID. Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory. Pokud se uživatelé již přihlásili ke službě SharePoint a pak jsou přesunuté do jiné organizační jednotky a znovu synchronizovány se službou SharePoint, mohou k tomuto problému dojít.

Chcete-li tento problém vyřešit, obnovte původní název UPN podle kroků v článku, [obnovte uživatele v sadě Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Poznámka: Pokud není centrum OneDrive nebo SharePoint Admin Center k dispozici pro více uživatelů, kteří měli přístup dříve, může se jednat o dočasný problém se službou.  [Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).


