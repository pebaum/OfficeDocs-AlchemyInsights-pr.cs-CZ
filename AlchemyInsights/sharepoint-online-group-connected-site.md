---
title: Přidání skupiny na web služby SharePoint
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f7d730bf-0d6e-424c-970c-6137c71cb50b
ms.openlocfilehash: 423db4e5bbb85e75aee3548d5b6b46a64ebc6fa0
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36750513"
---
# <a name="issues-when-creating-or-group-connected-sites-in-sharepoint-online"></a>Problémy při vytváření nebo seskupování připojených sítí ve službě SharePoint Online

Při vytváření nebo vytváření nového serveru připojeného ke skupině došlo k několika běžným problémům.

 Pokud jste odstranili skupinu a její připojený web a chcete vytvořit další web se stejnou adresou URL, bude nutné trvale odebrat předchozí Web.

Stáhnout [prostředí správy spo](https://support.office.com/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429)

 Další informace o zahájení v prostředí PowerShell naleznete v tématu Začínáme [s prostředím SharePoint Online Management Shell](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps)

Odebrání webu z odstraněných serverů pomocí rutiny pro [Odebrání-SPODeletedSite](https://docs.microsoft.com/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps) PowerShell

Pokud vytváříte připojený skupinový web a přijímáte upozornění jiná skupina se stejným alias již existuje, zkontrolujte existující skupiny z [webu Office 365 z centra pro správu](https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups). Chcete-li tento problém vyřešit, odstraňte existující skupinu, pokud již není potřebná, nebo vytvořte web s přiřazeným jiným aliasem.

Existují různé způsoby, jak vytvořit a používat moderní skupiny se službou SharePoint.

Existující weby můžete připojit ke skupině Office 365. Další informace naleznete v tématu [připojení skupiny Office 365 pomocí neexistujícího uživatele služby SharePoint](https://docs.microsoft.com/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface).

Chcete-li vytvořit připojený web sady Office 365, je třeba vytvořit týmový Web. Další informace naleznete v tématu [vytvoření týmového webu ve službě SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d).

