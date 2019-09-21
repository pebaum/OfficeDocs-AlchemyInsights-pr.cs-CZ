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
ms.openlocfilehash: af5b3c76b82db13bc89c917247e41fa1d8779b68
ms.sourcegitcommit: d5bf97a0bf0547f36b6da9684ce9f16a13a7749e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068016"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>Protokoly auditu služby SharePoint a OneDrive

**Služby SharePoint a OneDrive moderní sjednocené záznamy auditu z souladu**

- [Zapnutí a vypnutí protokolování pro sjednocený audit](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

V rámci služby SharePoint nebo OneDrive není vyžadována žádná další konfigurace.

- Pomocí vyhledávání protokolování auditu Zkontrolujte činnost souborů, složek, uživatelů, oprávnění:

    - [Aktivity souborů a stránek](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [Aktivity složek](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [Aktivity související se sdílením a přístupem](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [Synchronizační aktivity](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [Činnosti správy webu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- Další informace o tom, jak tyto události načíst, naleznete v tématu [hledání v protokolu auditování](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).

**Klasické protokoly auditu služby SharePoint**

Migrovali jsme starší verze auditování SPO do protokolu Unified auditovací protokol (UAL). To v podstatě znamená, že všechny starší zprávy o auditu SPO budou nyní napájeny prostřednictvím UAL a starší signály auditu byly migrovány do UAL.

Klíčové změny:

- Oříznutí jako funkce není k dispozici.
- Oddíl, ve kterém vyberete konkrétní události k auditování, není k dispozici. Úplný seznam auditovaných událostí, které jsou ve výchozím nastavení k dispozici, naleznete v [tomto dokumentu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) .
- Možnost umístění ve **vlastních SESTAVÁCH** není k dispozici. 
- Události otevírání nebo stahování dokumentů nejsou k dispozici. 

