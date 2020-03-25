---
title: DLP může potřebovat vlastní typ
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: ''
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1647"
- "3200001"
ms.assetid: ''
ms.openlocfilehash: 890bba57bc36c034c507e6124cd6593ef4d92af8
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932651"
---
# <a name="dlp-might-need-a-custom-type"></a>DLP může potřebovat vlastní typ

**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí. Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování. Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.

Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin. Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech. Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.

**Ochrana před únikem informací může vyžadovat vlastní typ informací.**

Pomocí zásad ochrany před únikem dat (DLP) můžete identifikovat a chránit citlivá data ve vaší organizaci. V některých případech může být nutné vytvořit vlastní **typ** citlivých informací k ochraně dat vaší organizace.

Vaše organizace může například potřebovat identifikovat a chránit ID zaměstnanců nebo jiná data v nějakém formátu specifickém pro vaši organizaci. Pokud ano, naleznete další informace v následujících článcích.
  
 **Přizpůsobení integrovaného typu citlivých informací**
  
Pokud by vestavěný typ citlivých informací vyhovoval vašim potřebám pomocí několika úprav, můžete [přizpůsobit vestavěný typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/customize-a-built-in-sensitive-information-type). Můžete například přidat nebo odebrat klíčová slova nebo přidat nebo odebrat podpůrné důkazy, například datum nebo adresu.
  
 **Vytvoření vlastního typu citlivých informací**
  
Ale pokud potřebujete identifikovat a chránit jiný typ citlivých informací úplně, můžete [vytvořit vlastní typ citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type) v ui centra pro & dodržování předpisů.
  
**Vytvoření vlastního typu citlivých informací v prostředí Security & Compliance Center PowerShell**

A konečně, pokud uI neposkytuje všechny možnosti, které potřebujete, můžete [vytvořit vlastní typ citlivých informací v zabezpečení & Compliance Center PowerShell](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type-in-scc-powershell). Začněte se souborem XML a můžete použít všechny dostupné možnosti.
