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
ms.openlocfilehash: 352bad1b8fe219f95a37c9ac268c6c4dd8801dfc
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719475"
---
# <a name="create-group-connected-site-in-sharepoint-online"></a>Vytvořit připojenou síť skupiny v Online služby SharePoint

<p><strong>Existuje několik běžných problémů při vytváření nebo znovu vytvořit skupinu připojení webu.&nbsp;</strong></p>  <p>1.Pokud jste odstranili skupinu a její připojenou síť a chtějí vytvořit jiného webu se stejnou adresou URL, budete muset trvale odebrat předchozí Web.</p>  <ul>  <li>Stáhnout <a title="SPO Management Shell" href="https://support.office.com/en-ie/article/introduction-to-the-sharepoint-online-management-shell-c16941c3-19b4-4710-8056-34c034493429">Správa prostředí SPO</a> - Další informace o Začínáme s powershell naleznete v tématu <a title="Začínáme s Online prostředí správy služby SharePoint" href="https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps">Začínáme s Online prostředí správy SharePoint</a>. <br /><br /></li>  <li>Odstranění webu z webů odstraněny pomocí <a title="SPODeletedSite odebrat" href="https://docs.microsoft.com/en-us/powershell/module/sharepoint-online/remove-sposite?view=sharepoint-ps">Odebrat SPODeletedSite</a> rutiny prostředí powershell.</li>  </ul>  <p>Pokud vytváříte skupinu připojenou síť a zobrazí se upozornění na <strong>jiné skupiny s stejný alias již existuje</strong>, zkontrolujte, zda existující skupiny z <a title="Office 365 Admin Center" href="https://admin.microsoft.com/Adminportal/Home?source=applauncher#/groups">Office 365 Admin Center</a>. Chcete-li tento problém vyřešit, odstraňte existující skupiny, pokud již není potřeba nebo vytvořit web s jiný alias přiřazen.&nbsp;</p>  <p><strong>Vytvoření a použití moderních skupin se službou SharePoint různými způsoby.&nbsp;</strong></p>  <ol>  <li>Existující weby můžete připojit do skupiny Office 365. Další informace naleznete v tématu <a title="připojit skupinu Office 365 pomocí ineterface uživatelů služby SharePoint" href="https://docs.microsoft.com/en-us/sharepoint/dev/transform/modernize-connect-to-office365-group#connect-an-office-365-group-using-the-sharepoint-user-interface">Skupinu Office 365 pomocí ineterface uživatele služby SharePoint připojit</a>.</li>  <li>Vytvořit web připojené skupiny Office 365, musíte vytvořit týmový web. Další informace naleznete v tématu <a title="vytvořit týmový web služby SharePoint" href="https://support.office.com/en-us/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d">Vytvořte týmový web služby SharePoint.</a></li>  </ol>

