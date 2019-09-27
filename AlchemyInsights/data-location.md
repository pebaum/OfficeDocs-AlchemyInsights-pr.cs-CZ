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
ms.openlocfilehash: 0e683c8266d425be95e87c590d4cb5d56108721a
ms.sourcegitcommit: 71978e2bb779b5955fd113f84512b83321b26912
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/26/2019
ms.locfileid: "37207254"
---
# <a name="data-location"></a>Umístění dat

Umístění klienta sady Office 365 můžete zobrazit v centru pro správu nebo připojením k serveru Exchange Online prostřednictvím prostředí PowerShell.


**Centrum pro správu:**
1. Přihlaste se do [centra pro správu](https://admin.microsoft.com/Adminportal/Home).
2. Vyberte **Nastavení** > **profilu organizace**.
3. V části **umístění dat**vyberte **Podrobnosti zobrazení**.


**Powershell:**
1. Připojení k serveru Exchange Online pomocí prostředí Windows PowerShell
2. Spuštěním rutiny [Get-OrganizationalUnit](https://docs.microsoft.com/en-us/powershell/module/exchange/active-directory/get-organizationalunit) zobrazíte seznam vlastností vašeho klienta. 
3. Podívejte se na vlastnost OrganizationId.

Pokud máte datové umístění pro EXO a SPO, můžete určit umístění dat pro jiné služby, které můžete použít z [místa, kde jsou data umístěna](https://products.office.com/where-is-your-data-located).