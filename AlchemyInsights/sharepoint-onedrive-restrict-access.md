---
title: Omezení přístupu na SharePointu nebo OneDrivu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: 39aa8cd6e649eca4a1e196eeb589a825364d0977
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692758"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Omezení přístupu na SharePointu nebo OneDrivu

Přístup ke službám SharePointu Online/OneDrive můžete omezit mnoha způsoby. Tyto různé metody omezení přístupu jsou uvedeny níže. 

**Omezení oprávnění**

V SharePointu Online a OneDrivu pro firmy omezujeme přístup k položkám, jako jsou weby, soubory a složky, tím, že udělujeme přístup jenom těm skupinám nebo jednotlivcům, kteří by k nim měli mít přístup.

- [Přizpůsobení oprávnění pro sharepointový seznam nebo knihovnu](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Přizpůsobení oprávnění sharepointového webu](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Změna oprávnění v podsložce](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Řízení přístupu z nespravovaných zařízení](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

Jako sharepointový nebo globální správce můžete blokovat nebo omezit přístup k obsahu SharePointu a OneDrivu z nespravovaných zařízení (těch, která v Intune nehybridní ad připojili nebo nedodržují předpisy).

**Omezení umístění v síti**

Jako správce IT můžete řídit přístup k prostředkům SharePointu a OneDrivu na základě definovaných síťových umístění, kterým důvěřujete. To se také označuje jako zásady založené na poloze. Další informace najdete v [tématu Řízení přístupu k sharepointovým online a onedrivem dat na základě umístění v síti.](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)

**Omezení uzamčení webu** 

V SharePointu Online můžete uzamknout kolekci webů, aby k ní neměl nikdo přístup. To se nastavuje přes PowerShell a [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) pomocí [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState vlastnost.

**Omezení vytváření webů nebo podřízených webů uživateli**

Jako správce SharePointu nebo globální správce můžete uživatelům udělit vlastní sharepointové weby, určit, jaký typ webů můžou vytvářet, a určit umístění webů. Další informace najdete v tématu [Správa vytváření webů v SharePointu Online.](https://docs.microsoft.com/sharepoint/manage-site-creation)

