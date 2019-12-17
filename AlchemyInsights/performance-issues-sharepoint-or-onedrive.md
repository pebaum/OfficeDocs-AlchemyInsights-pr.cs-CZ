---
title: Problémy s výkonem – SharePoint nebo OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1133"
- "2397"
- "2418"
- "5200018"
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: aecbf4043c6456ece73f7deed6b068040f0691a2
ms.sourcegitcommit: 0fb89d8106fe409ab1b78e50f5357ffc2252f7c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/17/2019
ms.locfileid: "40068388"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>Služba SharePoint nebo OneDrive je pomalá, nedostupná nebo nedostupná pro více uživatelů

Služba SharePoint nebo OneDrive může být pomalá, nedostupná nebo nedostupná nebo může zobrazit službu nedostupnou nebo 503 chyb, a to z několika důvodů:
  
- Pokud je web služby SharePoint nebo OneDrive pomalý nebo zpožděn pro více uživatelů, může se jednat o dočasný problém se službou, kde se uživatelům při přístupu k webům SharePoint nebo k obsahu OneDrive vyskytnou občasné prodlevy nebo chyby navigace. Zkontrolujte [řídicí panel stavu služby](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) a zjistěte, zda je v organizaci ohrožena.
  
- Při pokusu o přechod na weby služby SharePoint nebo OneDrive se uživatelům může zobrazit chybová zpráva o tom, že *server 503 je zaneprázdněn* . Tato chyba může být způsobena omezením v rámci služby SharePoint. Služba SharePoint Online používá omezení k udržování optimálního výkonu a spolehlivosti služby SharePoint Online. Omezení omezuje počet uživatelských akcí nebo souběžných volání (podle skriptu nebo kódu), aby zabránil přetížení prostředků. Další informace týkající se omezení naleznete [v tématu služby SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online), které není třeba omezením nebo zablokováno.

- Pokud dochází k pomalému výkonu na **klasickém** nebo **moderním** webu nebo stránce služby SharePoint, použijte k analýze stránek [Nástroj pro diagnostiku stránek](https://aka.ms/perftool) .
  
- Pokud stále dochází k obecnému pomalému výkonu, prostudujte si zdroje v dolní části tohoto článku: [Úvod k optimalizaci výkonu služby SharePoint Online](https://go.microsoft.com/fwlink/?linkid=2024334)
  