---
title: Mikrozpoždění a omezování v Exchange Online PowerShellu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/30/2020
ms.locfileid: "43947796"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Mikrozpoždění a omezování v Exchange Online PowerShellu

Když spustíte skripty a rutiny v Exchangi Online, mohou se zobrazit upozornění „Použito mikrozpoždění“ nebo se objevit zpoždění. Tady jsou dva návrhy, které se toho týkají:

- Můžete zkusit použít [modul Exchange Online v2 PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), který obsahuje rutiny založené na rozhraní REST API a je výrazně výkonnější. Může to být skvělé řešení pro velké množství často používaných rutin Get-.
- Pokud potřebujete použít rutiny, které ještě nejsou zavedené v modulu v2, přečtěte si téma [Spuštění rutin PowerShellu pro velké počty uživatelů v Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), které se zabývá tím, jak obejít očekávané limity omezování PowerShellu v Exchangi Online.
