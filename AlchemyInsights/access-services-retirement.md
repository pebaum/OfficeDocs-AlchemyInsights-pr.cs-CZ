---
title: Přístup ke službě odchodu do důchodu
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "9000356"
- "2009"
ms.assetid: ''
ms.openlocfilehash: 977bd5887ef58b328463a9befcd6b47ac55f5a85
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687251"
---
# <a name="access-services-retirement"></a>Přístup ke službě odchodu do důchodu

Jak jsme původně oznámili v MC97576, v březnu 2017, a pokračovali v komunikaci v uplynulém roce, přístupové služby jsou vyřazeny. Další fází tohoto procesu bude odebrání webových databází aplikace Access, které používají seznamy služby SharePoint jako základní úložiště dat.

**Jak to ovlivní mě?**

Od června 2019 přestaneme vytvářet nové databáze Accessu v SharePointu Online a do dubna 2020 službu a všechny zbývající aplikace vypneme.

**Co musím udělat, abych se na tuto změnu připravil?**

Doporučujeme vytvořit plán přechodu pro webové databáze accessu vaší organizace. Správci můžou pomocí [skeneru aplikací pro SharePoint Access](https://github.com/SharePoint/PnP-Tools/tree/master/Solutions/SharePoint.AccessApp.Scanner) získat inventář aplikací pro Access, které weby používají.

Data webových databází aplikace Access lze migrovat několika způsoby:

- Import do místní databáze aplikace Access (. ACCDB) nebo do souboru aplikace Excel.
- Doporučujeme také prozkoumat Microsoft PowerApps jako alternativní platformu pro vytvoření bezkódových obchodních řešení pro web a mobilní zařízení.