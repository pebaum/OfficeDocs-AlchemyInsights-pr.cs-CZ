---
title: Klasické sestavy protokolu auditu sharepointového oddělení
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
ms.openlocfilehash: 3270f1ab03bacb235cbdc3d710053c858f0a5183
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741958"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a>Protokoly auditu SharePointu a OneDrivu

## <a name="sharepoint-classic-audit-logs"></a>Klasické protokoly auditu sharepointu

Provádění starších auditů SPO bylo migrováno do protokolu jednotného auditu (UAL). Všechny starší zprávy o auditu SPO budou nyní napájeny prostřednictvím ual a starší signály auditu byly přeneseny na UAL.

Klíčové změny:

* Oříznutí není k dispozici jako schopnost.
* Výběr konkrétních událostí k auditu není k dispozici. Úplný seznam auditovaných událostí, které jsou k dispozici ve výchozím nastavení, naleznete v [tomto dokumentu.](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* Možnost **Umístění** v části **Vlastní sestavy** není k dispozici.
* Možnost **Otevření nebo stahování dokumentů** není k dispozici.

[Konfigurace nastavení auditu pro kolekci webů](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a>Protokoly moderního jednotného auditu SharePointu a OneDrivu s dodržováním předpisů

* [Zapnutí/vypnutí jednotného protokolování auditu](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

V SharePointu nebo OneDrivu není potřeba žádná další konfigurace.

Pomocí hledání protokolování auditu zkontrolujte aktivitu souborů, oprávnění složek, uživatelů:

* [Aktivity souborů a stránek](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [Aktivity složek](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [Sdílení a přístup k aktivitám žádostí](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [Synchronizační aktivity](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [Aktivity správy lokality](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

Další informace o tom, jak načíst tyto události, naleznete [v tématu Hledání protokolu auditu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
