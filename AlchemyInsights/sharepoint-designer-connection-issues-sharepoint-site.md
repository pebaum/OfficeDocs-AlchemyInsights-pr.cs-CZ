---
title: SharePoint Online úrovně oprávnění
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760686"
---
# <a name="sharepoint-designer-connection-issues"></a>Problémy s připojením aplikace SharePoint Designer 

Pokud aplikace SharePoint Designer dochází k problémy s připojením k webům služby SharePoint, prosím o následující společné řešení.

Krok 1: Ověřte aktualizaci SharePoint Designer.

- [Aplikace SharePoint Designer 2013](https://www.microsoft.com/download/details.aspx?id=35491)

- [Aplikace SharePoint Designer Service Pack 1 (SP1)](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [Aktualizace SharePoint Designer 2013 (KB3114721)](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

Krok 2: Vymazat místní mezipaměť souborů

- Zavřete aplikaci SharePoint Designer 2013.

- Vyhledejte následující složky odeberte soubory uložené v mezipaměti místního počítače.

- Klepněte na tlačítko Start, spustit a odstranit všechny soubory nalezeny v každé pod umístění.

%APPDATA%\Microsoft\Web server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

Otevřete aplikaci SharePoint Designer 2013 a zadejte účet zjistíte, zda funguje.

Krok 3: [Povolit moderní ověřování Office 2013 na zařízení systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)

Krok 4: Administrators bude nutné povolit vlastní skript k povolení připojení aplikace SharePoint Designer.

Podrobné kroky, příklady a důležité informace naleznete v [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).


