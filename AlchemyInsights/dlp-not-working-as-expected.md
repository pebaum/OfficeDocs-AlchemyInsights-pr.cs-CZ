---
title: DLP nefunguje podle očekávání
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: e96904e2f0da2fe1fafb3f8722465eaf22681b71
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507471"
---
# <a name="dlp-not-working-as-expected"></a>DLP nefunguje podle očekávání

**Důležité**: V této mimořádné době přijímáme opatření, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné. Další informace najdete v článku zaměřeném na [dočasné úpravy funkcí SharePointu Online](https://aka.ms/ODSPAdjustments).

 **Nastavení DLP**

Máte problémy s **ochranou před únikem dat (DLP)** v Office 365 nefunguje podle očekávání? Pokud ano, ujistěte se, že **vaše zásady ochrany před únikem informací** je správně nastavena a že vaše data obsahují, co **zásady ochrany před únikem informací** hledá při jejich vyhodnocování.
  
Zásady ochrany před únikem informací umožňují identifikovat a chránit citlivé informace ve vaší organizaci. Chcete-li nastavit zásady ochrany před únikem informací, použijte informace [zde](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).
  
 **Co zásady ochrany před únikem let hledají**
  
Při použití **předdefinované typy citlivých informací** v centrech zabezpečení a dodržování předpisů zásady ochrany před únikem informací hledají při zjišťování těchto citlivých typů konkrétní vzory a prvky.
  
- **Vestavěné typy citlivých informací**

    Informace o předdefinované typy a co hledá zásady ochrany před únikem informací při zjišťování citlivého typu, naleznete v [tématu: Co vyhledáte typy citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).

- **Vlastní typy citlivých informací**

    Pokud se pokoušíte vytvořit vlastní typy citlivých informací, použijte následující článek pro informace o tom, jak vytvořit vlastní citlivý typ: [Vytvoření vlastního typu citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).

**Testování zásad ochrany před únikem let dlp**

Chcete-li data otestovat pomocí integrovaného nebo vlastního typu citlivých informací, použijte možnost **Typ testu** v části **Typy**  >  **citlivých informací**klasifikace . Další informace naleznete v [tématu Testování vlastních typů citlivých informací](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).

 **Sestavy**
  
- Získejte citlivé poznatky o datech pomocí [sestav ochrany před únikem informací.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)

- Podívejte se na konkrétní podrobnosti o události pomocí [hlášení incidentů](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports).
