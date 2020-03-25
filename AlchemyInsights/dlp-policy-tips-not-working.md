---
title: Tipy pro zásady ochrany před únikem informací nefungují
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932579"
---
# <a name="dlp-policy-tip-issues"></a>Problémy s tipem na zásady ochrany před únikem

**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí. Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování. Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.

Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin. Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech. Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.

**Tipy pro zásady ochrany před únikem informací**

Při použití **zásad ochrany před únikem informací**mohou být uživatelé upozorněni na porušení zásad pomocí tipů **zásad**. Správci mohou nakonfigurovat tipy zásad k zobrazení při testování zásad ochrany před únikem informací nebo při úplném vynucování.
  
Chcete-li nakonfigurovat tipy pro zásady ochrany před únikem informací v centru zabezpečení a dodržování předpisů v režimu úplného vynucení, postupujte takto:
  
- Ujistěte se, že byly **povoleny** tipy zásad na pravidlo ochrany před únikem informací pomocí [kroků zde](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).

- Ujistěte se, že váš **obsah odpovídá tomu,** co je **nutné** k aktivaci pravidla uvedeného v tomto článku [zde](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).

- Tipy pro zásady se zobrazují v aplikaci OWA i v aplikaci Outlook. Pokud však používáte **Outlook 2013 nebo novější**, zobrazí se tipy zásad pouze za určitých podmínek. Zde jsou uvedeny tyto podmínky: [Podporované podmínky pro Outlook 2013 nebo novější pro zobrazení tipů zásad](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)

Další informace o tipech pro zásady ochrany před únikem informací naleznete v [tématu: Zobrazit tipy zásad pro zásady ochrany před únikem informací](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)
  