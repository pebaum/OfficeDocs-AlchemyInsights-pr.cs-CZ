---
title: Poradce při potížích s odepřením přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 9430b9786b35dda9fb2604fb6ae3c39c8c258d6e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505372"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Poradce při potížích se zprávami o odepření přístupu v Centru pro správu Sharepointu/OneDrivu

Pokud se při pokusu o přechod do Centra pro správu Sharepointu/OneDrivu zobrazuje zpráva o odepření přístupu, ujistěte se, že [uživateli přiřadíte licenci](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users). Pokud má uživatel licenci, měli byste se také ujistit, že je [mu přiřazena role správce,](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) která má přístup k centrům pro správu.

K tomuto problému může dojít také při odstranění uživatele a znovu vytvořit se stejným hlavním názvem uživatele (HLAVNÍ NÁZEV UŽIVATELE). Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID). Když se uživatel pokusí o přístup k kolekci webů nebo jeho OneDrive, uživatel má nesprávné PUID. Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU). Pokud se uživatelé již přihlásili ke SharePointu a potom jsou přesunuti do jiné OU a znovu se sharepointem, může se k tomuto problému vyskytnout.

Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní hlavní číslo uživatele s postupem v článku [Obnovení uživatele v microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).

Poznámka: Pokud OneDrive nebo Centrum pro správu SharePointu není dostupné více uživatelům, kteří k nim dříve měli přístup, může se nastat problém s dočasnými službami.  [Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).


