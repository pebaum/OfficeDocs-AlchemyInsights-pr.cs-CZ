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
ms.openlocfilehash: 01ccc6bc28148f397fb6cd2b7a0eaaeb5b51973f
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511537"
---
# <a name="sharepoint-designer-connection-issues"></a>Problémy s připojením aplikace SharePoint Designer 

Pokud se SharePoint Designer potýká s problémy s připojením k webům Služby SharePoint, vyzkoušejte následující běžná řešení.

Krok 1: Ověřte, zda je SharePoint Designer 2013 aktualizován [aktualizací SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) a [aktualizací ze srpna 2016 pro SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).



Krok 2: Vymazání místních souborů mezipaměti:

1. Zavřít SharePoint Designer 2013.

2. V místním počítači odeberte všechny soubory nalezené v každé z následujících složek.

    - %APPDATA%\Microsoft\Rozšíření webového serveru\Mezipaměť
    - %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache
    - %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache

3. Otevřete SharePoint Designer 2013 a znovu zadejte účet, abyste zjistili, jestli funguje.

Krok 3: [Povolení moderního ověřování pro Office 2013 na zařízeních s Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).

Krok 4: Správci budou muset **povolit vlastní skript** v nastavení Centra pro správu SharePointu, aby povolili připojení k SharePoint Designeru. Další informace najdete [v tématu Povolení nebo zabránění vlastnímu skriptu.](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)


