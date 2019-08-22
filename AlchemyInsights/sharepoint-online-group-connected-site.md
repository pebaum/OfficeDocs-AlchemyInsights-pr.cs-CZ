---
title: Přidání skupiny do webu služby SharePoint
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 6aea12d44a44a3e11eaf3fb1bd47ff3e9dbfd9e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36507840"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a>Problémy při vytváření nebo skupinu připojené weby v SharePoint Online

Existuje několik běžných problémů při vytváření nebo znovu vytvořit skupinu připojení webu.

 Pokud jste odstranili skupinu a její připojenou síť a chtějí vytvořit jiného webu se stejnou adresou URL, budete muset trvale odebrat předchozí Web.

Stáhnout [prostředí Management Shell SPO](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)

 Další informace o Začínáme s powershell naleznete v tématu [Začínáme s Online prostředí správy služby SharePoint](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)

Odeberte web ze serverů odstraněny pomocí rutiny prostředí powershell [Odebrat SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) .

Pokud vytváříte skupinu připojenou síť a zobrazí upozornění, že jiné skupiny s stejný alias již existuje, zkontrolujte existující skupiny z [Office 365 Admin Center](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups). Chcete-li tento problém vyřešit, odstraňte existující skupiny, pokud již není potřeba nebo vytvořit web s jiný alias přiřazen.

Vytvoření a použití moderních skupin se službou SharePoint různými způsoby.

Existující weby můžete připojit do skupiny Office 365. Další informace získáte v části [připojení skupinu Office 365 pomocí ineterface uživatelů služby SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).

Vytvořit web připojené skupiny Office 365, musíte vytvořit týmový web. Další informace naleznete v článku [Vytvoření týmového webu služby SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).

