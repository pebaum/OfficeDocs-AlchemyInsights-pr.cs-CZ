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
ms.openlocfilehash: e7bfabe1555bb94e915f8544d460deecce6171be
ms.sourcegitcommit: 317eeed39c7777a922442992d67733726c41d9e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/04/2020
ms.locfileid: "41770344"
---
# <a name="issues-when-creating-a-group-connected-site-in-sharepoint"></a>Problémy při vytváření skupinového připojeného webu v SharePointu

1. Při vytváření nebo opětovném vytvoření propojeného webu skupiny se vyskytly některé běžné problémy.
Pokud jste odstranili skupinu a její připojený web a chcete vytvořit jiný web se stejnou adresou URL, budete muset předchozí web trvale odebrat.

   - Stažení [prostředí SPO Management Shell](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)
   - Další informace o tom, jak začít s Powershellem, najdete v tématu [Začínáme s prostředím SharePointu Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite).
   - Odeberte web z odstraněných webů pomocí rutiny Prostředí Powershell [Remove-SPODeletedSite.](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) Prostředí Powershell je nutné trvale odstranit weby skupin.

1. Pokud vytváříte skupinový propojený web a obdržíte upozornění: **Jiná skupina se stejným aliasem již existuje**, zkontrolujte existující skupiny z Centra pro správu office [365](https://admin.microsoft.com/AdminPortal/Home#/groups). Chcete-li problém vyřešit, odstraňte existující skupinu, pokud již není potřeba, nebo vytvořte web s jiným přiřazeným aliasem.

1. Existují různé způsoby vytváření a používání moderních skupin se Službou SharePoint.

   - Existující weby můžete propojit se skupinou Office 365. Další informace najdete v [tématu Připojení skupiny Office 365 pomocí uživatelského rozhraní SharePointu](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).
   - Chcete-li vytvořit propojený web skupiny Office 365, budete muset vytvořit [týmový web](https://admin.microsoft.com/sharepoint).
