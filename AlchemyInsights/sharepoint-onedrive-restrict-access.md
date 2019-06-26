---
title: Omezení přístupu v serveru SharePoint nebo OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: db84f77208dca60c6dee98cdb0c7f1ea7fa8fe17
ms.sourcegitcommit: 204c8fadd59a597a18ebde24b3c63fbb656ec1b6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/25/2019
ms.locfileid: "35223705"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Omezení přístupu v serveru SharePoint nebo OneDrive

Existuje mnoho způsobů, jak omezit přístup k služby SharePoint Online nebo OneDrive. Tyto různé metody omezení přístupu jsou uvedeny níže. 

**Omezení oprávnění**

V SharePoint Online a OneDrive pro firmy můžeme omezit přístup k položky, jako jsou weby, soubory a složky pouze poskytnutím přístupu k skupiny nebo uživatelé, kteří mají mít přístup.

- [Upravit oprávnění pro knihovnu nebo seznam SharePoint](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Upravit oprávnění pro web služby SharePoint](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Změnit oprávnění pro podsložky](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Řízení přístupu z nespravovaných zařízení](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

Jako SharePoint nebo globálního správce ve službách Office 365, můžete blokovat nebo omezit přístup k obsahu služby SharePoint nebo OneDrive z nespravovaných zařízení (tyto hybridní AD spojených nebo kompatibilní v Intune).

**Omezení umístění v síti**

Jako IT správce můžete řídit přístup k prostředkům služby SharePoint a OneDrive založené na definované síťové umístění, které považujete za důvěryhodné. Je také známý jako zásady založené na umístění. Další informace naleznete v tématu [řízení přístupu k serveru SharePoint Online a OneDrive data v závislosti na umístění v síti](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)

**Omezení uzamčení webu** 

V rámci služby SharePoint Online máte možnost Uzamknout kolekci webů, tak nemá nikdo přístup. Tato hodnota je nastavena pomocí prostředí PowerShell a [Prostředí Online správy služby SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) pomocí vlastnosti [Sady SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) - LockState.

**Uživatelé nemohli vytvářet weby nebo podřízené weby**

Jako správce serveru SharePoint nebo globálního správce služeb Office 365, umožníte uživatelům vytvářet a spravovat své vlastní weby služby SharePoint, zjistit, jaké weby mohou vytvořit a určete umístění serverů. Další informace naleznete v tématu [Správa vytváření webu v Online služby SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation)

