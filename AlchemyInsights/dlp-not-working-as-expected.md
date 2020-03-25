---
title: DLP nefunguje podle očekávání
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: a56e18ddadef3a2f9056978b8542c1dba8f29665
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932615"
---
# <a name="dlp-not-working-as-expected"></a>DLP nefunguje podle očekávání

**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí. Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování. Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.

Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin. Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech. Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.

 **Nastavení ochrany před únikem a ochrany před únikem**

Máte problémy s **prevencí před ztrátou dat (DLP)** v Office 365 nefunguje podle očekávání? Pokud ano, ujistěte se, že **vaše zásady ochrany před únikem informací** jsou správně nastaveny a že data obsahují to, co **zásady ochrany před únikem informací** hledají při vyhodnocování.
  
Zásady ochrany před únikem informací umožňují identifikovat a chránit citlivé informace ve vaší organizaci. Chcete-li nastavit zásady ochrany před únikem informací, použijte informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).
  
 **Co zásady ochrany před únikem a ochrany údajů**
  
Při použití **předdefinovaných typů citlivých informací** v Centru zabezpečení a dodržování předpisů Office 365 hledají zásady ochrany před únikem informací konkrétní vzory a prvky při zjišťování těchto citlivých typů.
  
- **Předdefinované typy citlivých informací**

    Informace o předdefinovaných typech Sensitive a o tom, co zásady ochrany před únikem informací hledají při zjišťování typu Sensitive, naleznete v [tématu What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).

- **Vlastní typy citlivých informací**

    Pokud se pokoušíte vytvořit vlastní typy citlivých informací, použijte následující článek, kde naleznete informace o vytvoření vlastního citlivého typu: [Vytvoření vlastního typu citlivých informací](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).

**Testování zásad ochrany před únikem a ochrany údajů**

Chcete-li data otestovat pomocí předdefinovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Klasifikace** > **Typy citlivých informací**. Další informace naleznete v [tématu Test vlastní chod citlivých informací typy](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).

 **Sestavy**
  
- Získejte přehledy citlivých dat pomocí [přehledů ochrany před únikem informací.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)

- Podívejte se na konkrétní podrobnosti události pomocí [zprávy o incidentu](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).
