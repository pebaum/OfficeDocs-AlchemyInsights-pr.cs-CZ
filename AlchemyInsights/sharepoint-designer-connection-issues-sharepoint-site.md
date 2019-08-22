---
title: Problémy s připojením aplikace SharePoint Designer
ms.author: efrene
author: efrene
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: a4aeaeaea5743c276b907c78317ff30f5610be81
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36508416"
---
# <a name="sharepoint-designer-connection-issues"></a>Problémy s připojením aplikace SharePoint Designer 

Pokud aplikace SharePoint Designer dochází k problémy s připojením k webům služby SharePoint, zkuste následující společné řešení.

Krok 1: Ověřte, zda aplikace SharePoint Designer 2013 aktualizován pomocí [aktualizace Service Pack 1 pro SharePoint Designer](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) a [2 srpen 2016 aktualizace pro aplikaci SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



Krok 2: Vymažte místní mezipaměť souborů:

1. Zavřete aplikaci SharePoint Designer 2013.

2. V místním počítači odeberte všechny soubory nacházející se v každém z následujících složek.

    - %APPDATA%\Microsoft\Web server Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Otevřete aplikaci SharePoint Designer 2013 a zadejte účet zjistíte, zda funguje.

Krok 3: [Povolit moderní ověřování Office 2013 na zařízení systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).

Krok 4: Administrators bude nutné **Povolit vlastní skript** v nastavení Centra správy služby SharePoint umožníte připojení služby SharePoint Designer. Viz [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) pro další informace.


