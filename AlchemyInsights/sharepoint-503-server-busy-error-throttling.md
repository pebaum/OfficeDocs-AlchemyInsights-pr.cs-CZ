---
title: Omezení SharePointu Online
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931219"
---
# <a name="sharepoint-online-throttling"></a>Omezení SharePointu Online

**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí. Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování. Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.

Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin. Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech. Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.

**Chyba serveru 503 je zaneprázdněna**

Uživatelé mohou při pokusu o přechod na weby SharePointu nebo OneDrivu obdržet chybu zaneprázdněného serverem 503. 

Tato chyba může být způsobena omezením v rámci služby SharePoint. SharePoint Online používá omezení k udržení optimálního výkonu a spolehlivosti služby SharePointu Online. Omezení omezuje počet akcí uživatele nebo souběžných volání (podle skriptu nebo kódu), aby se zabránilo nadměrnému využívání prostředků. 

Další informace o omezení najdete [v tématu Vyhněte se omezení nebo zablokování v SharePointu Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).

Pokud se domníváte, že tato chyba nesouvisí s omezením, můžete zkontrolovat, zda v tenantovi dochází k aktivní údržbě, a to tak, že přejdete do [Centra zpráv](https://portal.office.com/adminportal/home#/MessageCenter).

 Nakonec se ujistěte, že jste navštívili stránku [Stav služby a](https://portal.office.com/adminportal/home#/servicehealth) zkontrolovali případné informační zpravodaje nebo incidenty.

