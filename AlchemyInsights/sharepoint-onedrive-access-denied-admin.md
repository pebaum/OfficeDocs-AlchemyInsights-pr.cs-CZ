---
title: Poradce při potížích s zprávy o odepření přístupu
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 0a885e15d54c9337711f2528628789dfcb903264
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36503520"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Odstranit chyby odepření přístupu v Centru pro správu služby Sharepoint nebo OneDrive

Pokud se zobrazuje zpráva o odepření při pokusu o procházení k Centru správy služby Sharepoint nebo OneDrive přístupu, zkontrolujte, že je [přiřazení licence uživateli](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One). Pokud uživatel má licenci, jste měli také ujistěte se, že je [přiřazen roli správce](https://docs.microsoft.com/office365/admin/add-users/about-admin-roles?view=o365-worldwide) , můžete získat přístup k admin Center.

Tomuto problému může dojít také v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport). Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID. Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU). Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.

Chcete-li tento problém vyřešit, obnovte původní název UPN pomocí kroků popsaných v následujícím článku [obnovení uživatele ve službách Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).

Poznámka: Pokud OneDrive nebo SharePoint Admin center není k dispozici pro více uživatelů, kteří dříve měl přístup, může existovat problém dočasnou službu.  [Kontrola řídicí panel stavu služeb](https://portal.office.com/adminportal/home#/servicehealth).


