---
title: Přidání skupiny na sharepointový web
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 8ef33cbd44b01deaf0e45813d019f7696ef5def0
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/27/2020
ms.locfileid: "43912959"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a>Problémy při vytváření připojeného webu skupiny v SharePointu

1. Při vytváření nebo opětovném vytváření připojeného webu skupiny došlo k některým běžným problémům.
Pokud jste odstranili skupinu a její připojený web a chcete vytvořit jiný web se stejnou adresou URL, budete muset trvale odebrat předchozí web.

   - Stáhnout [prostředí pro správu SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)
   - Další informace o tom, jak začít s Powershellem, najdete [v tématu Začínáme s SharePointem Online Management Shellem](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).
   - Odeberte web z odstraněných webů pomocí rutiny [Remove-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Powershell. Powershell je nutné trvale odstranit stránky skupiny.

1. Pokud vytváříte skupinový připojený web a zobrazí se upozornění: **Jiná skupina se stejným aliasem již existuje**, zkontrolujte existující skupiny z Centra pro [správu Microsoftu 365](https://admin.microsoft.com/AdminPortal/Home#/groups). Chcete-li tento problém vyřešit, odstraňte existující skupinu, pokud již není potřeba, nebo vytvořte web s přiřazeným jiným aliasem.

1. Existují různé způsoby, jak vytvářet a používat moderní skupiny se SharePointem.

   - Existující weby můžete připojit ke skupině Microsoft 365. Další informace najdete [v tématu Připojení skupiny Microsoft 365 pomocí uživatelského rozhraní SharePointu](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).
   - Chcete-li vytvořit propojený web skupiny Microsoft 365, budete muset vytvořit [týmový web](https://admin.microsoft.com/sharepoint).
