---
title: Problémy s připojením aplikace SharePoint Designer
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 9730bd66afd494385db3de605f5fe68d0f274ed3
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051706"
---
# <a name="sharepoint-designer-connection-issues"></a>Problémy s připojením aplikace SharePoint Designer 

Pokud aplikace SharePoint Designer zažívá problémy s připojením k webům služby SharePoint, vyzkoušejte následující běžná řešení.

Krok 1: Ověřte, zda je aplikace SharePoint Designer 2013 aktualizována pomocí aktualizace [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) , a [2. srpna 2016 pro aplikaci SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



Krok 2: vymazání místních souborů mezipaměti:

1. Ukončete aplikaci SharePoint Designer 2013.

2. V místním počítači odeberte všechny soubory nalezené v následujících složkách.

    - %AppData%\microsoft\webový Server Extensions\Cache
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Spusťte aplikaci SharePoint Designer 2013 a znovu zadejte účet, aby bylo vidět, zda funguje.

Krok 3: [Povolte moderní ověřování pro sadu Office 2013 v zařízeních systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide).

Krok 4: Správci budou muset **Povolit vlastní skript** v nastavení centra pro správu služby SharePoint, aby bylo možné povolit připojení aplikace SharePoint Designer. Další informace naleznete v tématu [Povolení nebo zákaz vlastního skriptu](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .


