---
title: Přístup ke službám v důchodu
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 197366882468ebc87fc26f2fe2733371790d1871
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36747777"
---
# <a name="access-services-retirement"></a>Přístup ke službám v důchodu

Jak jsme původně oznámili v roce MC97576, v březnu 2017 a pokračovali v komunikaci v uplynulém roce služby Access Services jsou vyřazeny z úřadu 365. Další fází tohoto procesu bude odebrání webových databází aplikace Access, které používají seznamy služby SharePoint jako své podkladové úložiště dat.

**Jak mě to ovlivňuje?**

Počínaje červnem 2019 se zastaví vytváření nových databází aplikace Access na webu služby SharePoint Online a ukončení služby a všech zbývajících aplikací do dubna 2020.

**Co je třeba udělat, aby se připravila na tuto změnu?**

Doporučujeme vytvořit plán přechodu pro webové databáze aplikace Access vaší organizace. Správci mohou pomocí [skeneru aplikací služby SharePoint Access](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) získat soupis aplikací Access, které weby používají.

Data webových databází aplikace Access lze migrovat několika způsoby:

- Import do místní databáze aplikace Access (. ACCDB) nebo do souboru aplikace Excel.
- Doporučujeme také prozkoumat aplikaci Microsoft PowerApps jako alternativní platformu pro tvorbu bezkódových podnikových řešení pro webové a mobilní zařízení.