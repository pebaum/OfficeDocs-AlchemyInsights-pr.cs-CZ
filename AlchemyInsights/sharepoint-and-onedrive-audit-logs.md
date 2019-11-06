---
title: Klasické sestavy protokolu auditování služby SharePoint
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: be95034bea3c58a4fde96cfb0f9ba525e810758e
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/05/2019
ms.locfileid: "37992611"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>Protokoly auditu služby SharePoint a OneDrive

## <a name="sharepoint-classic-audit-logs"></a>Klasické protokoly auditu služby SharePoint

Starší verze auditu SPO byla přenesena do protokolu jednotného auditu (UAL). Všechny starší verze zpráv o auditu SPO budou nyní napájeny prostřednictvím UAL a starší signály auditu byly migrovány do UAL.

Klíčové změny:

* Oříznutí není dostupné jako možnost.
* Výběr konkrétních událostí k auditování není k dispozici. Úplný seznam auditovaných událostí, které jsou ve výchozím nastavení k dispozici, naleznete v [tomto dokumentu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) .
* Možnost **umístění** ve **vlastních sestavách** není k dispozici.
* Možnosti **otevírání nebo stahování dokumentů** nejsou k dispozici.

[Konfigurace nastavení auditu pro kolekci webů](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>Služby SharePoint a OneDrive moderní sjednocené záznamy auditu z souladu

* [Zapnutí a vypnutí protokolování pro sjednocený audit](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

V rámci služby SharePoint nebo OneDrive není vyžadována žádná další konfigurace.

Pomocí vyhledávání protokolování auditu Zkontrolujte činnost souborů, složek, uživatelů, oprávnění:

* [Aktivity souborů a stránek](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [Aktivity složek](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [Aktivity související se sdílením a přístupem](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [Synchronizační aktivity](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [Činnosti správy webu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

Další informace o tom, jak tyto události načíst, naleznete v tématu [hledání v protokolu auditování](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
