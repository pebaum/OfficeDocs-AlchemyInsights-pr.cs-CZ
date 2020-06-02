---
title: Klasické sestavy protokolu auditu služby SharePoint
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 0aedb549f11db54d3cd480671fb0767c60680ad3
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509593"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>Protokoly auditu SharePointu a OneDrivu

## <a name="sharepoint-classic-audit-logs"></a>Klasické protokoly auditu sharepointu

Starší auditování SPO bylo migrováno do jednotného protokolu auditu (UAL). Všechny starší zprávy o auditu SPO budou nyní napájeny přes UAL a starší signály auditu byly migrovány do UAL.

Klíčové změny:

* Ořezávání není k dispozici jako funkce.
* Výběr konkrétních událostí k auditování není k dispozici. Úplný seznam auditovaných událostí, které jsou ve výchozím nastavení k dispozici, naleznete v [tomto dokumentu.](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* Možnost **Umístění** v části **Přizpůsobené sestavy** NENÍ k dispozici.
* Možnost **Otevření nebo stažení událostí dokumentů** není k dispozici.

[Konfigurace nastavení auditu pro kolekci webů](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>Protokoly sharepointového a onedriveového moderního jednotného auditu z dodržování předpisů

* [Zapnutí nebo vypnutí jednotného protokolování auditu](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off) 

V SharePointu nebo OneDrivu se nevyžaduje žádná další konfigurace.

Pomocí vyhledávání protokolování auditu zkontrolujte aktivitu souborů, složek, uživatelů, oprávnění:

* [Aktivity souborů a stránek](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* [Aktivity složek](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [Aktivity pro sdílení a přístup k žádosti](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [Aktivity synchronizace](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [Činnosti správy webu](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

Další informace o načtení těchto událostí naleznete [v tématu Hledání v protokolu auditu](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
