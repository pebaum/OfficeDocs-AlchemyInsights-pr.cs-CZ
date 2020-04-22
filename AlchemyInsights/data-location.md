---
title: Umístění dat
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "945"
- "5300023"
ms.assetid: 3bab036c-dbaa-406a-8b73-1e5f31993436
ms.openlocfilehash: c769c17796d805f88afb4d5b32adb7d4a9bb3ce0
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/21/2020
ms.locfileid: "43655275"
---
# <a name="data-location"></a>Umístění dat

Umístění vašeho tenanta můžete zobrazit v Centru pro správu nebo připojením k Exchange Online přes PowerShell.


**Centrum pro správu:**
1. Přihlaste se do [Centra pro správu](https://admin.microsoft.com/Adminportal/Home).
2. Vyberte **nastavení** > **profilu organizace**.
3. V části **Umístění dat**vyberte **Zobrazit podrobnosti**.


**Powershell:**
1. Připojte se k Exchange Online pomocí prostředí Windows PowerShell.
2. Spusťte rutinu [Get-OrganizationalUnit,](https://docs.microsoft.com/powershell/module/exchange/active-directory/get-organizationalunit) chcete-li zobrazit seznam vlastností vašeho klienta. 
3. Podívejte se na majetek Organizace id.

Pokud máte umístění dat pro EXO a SPO, můžete určit umístění dat pro další služby, které můžete použít z [místa, kde se vaše data nacházejí](https://products.office.com/where-is-your-data-located).