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
ms.openlocfilehash: 574a8a43d8264e98c6af2bfeb1bb472475e6e334
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977431"
---
# <a name="dlp-not-working-as-expected"></a>DLP nefunguje podle očekávání

**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)

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
