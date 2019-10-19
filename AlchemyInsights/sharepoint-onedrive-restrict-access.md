---
title: Omezení přístupu ve službě SharePoint nebo OneDrive
ms.author: pebaum
author: Techwriter40
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: bef0612903b9bb455aa34e90d35d6b7b9093b4e0
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36750657"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Omezení přístupu ve službě SharePoint nebo OneDrive

Přístup ke službám služby SharePoint Online/OneDrive lze omezit mnoha způsoby. Tyto různé metody omezení přístupu jsou popsány níže. 

**Omezení oprávnění**

V aplikaci SharePoint Online a OneDrive for Business omezujeme přístup k položkám, jako jsou weby, soubory a složky, tím, že udělíte přístup pouze těmto skupinám nebo jednotlivcům, kteří by měli mít přístup.

- [Přizpůsobení oprávnění pro seznam nebo knihovnu SharePoint](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Vlastní nastavení oprávnění webu služby SharePoint](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Změna oprávnění podsložky](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Řízení přístupu z nespravovaných zařízení](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

Jako server SharePoint nebo globální správce v sadě Office 365 můžete blokovat nebo omezit přístup k obsahu služby SharePoint a OneDrive z nespravovaných zařízení (které nejsou spojeny s křížovým přístupem nebo jsou kompatibilní v Intune).

**Omezení umístění v síti**

Jako správce IT můžete řídit přístup k prostředkům SharePoint a OneDrive na základě definovaných síťových umístění, kterým důvěřujete. Toto je označováno také jako zásada založená na umístění. Další informace naleznete v tématu [řízení přístupu k datům služby SharePoint Online a OneDrive na základě umístění v síti](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location) .

**Omezení uzamčení webu** 

V rámci služby SharePoint Online máte možnost Uzamknout kolekci webů, takže k ní nikdo nemá přístup. Tato vlastnost je nastavena prostřednictvím prostředí PowerShell a [prostředí SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) pomocí vlastnosti [set-sposite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState.

**Omezení uživatelů na vytváření webů nebo podřízených webů**

Jako správce serveru SharePoint nebo Office 365 Global admin můžete uživatelům dovolit vytvářet a spravovat vlastní weby služby SharePoint, určovat, jaký druh webů mohou vytvořit, a určit umístění webů. Další informace naleznete [v tématu Správa vytváření webů na webu služby SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation)

