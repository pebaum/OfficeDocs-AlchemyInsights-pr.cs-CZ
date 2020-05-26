---
title: Uvítací zpráva ve skupinách Microsoft 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "5685"
ms.openlocfilehash: d82931ae6978a09e674b00640d1dd413bcce7cfd
ms.sourcegitcommit: b196100759b29aecd62b693a2bfedbbd25a697c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/19/2020
ms.locfileid: "44357391"
---
# <a name="welcome-message-in-microsoft-365-groups"></a>Uvítací zpráva ve skupinách Microsoft 365

Noví uživatelé, kteří se připojí ke skupině Microsoft 365, obdrží uvítací e-mail, pokud je vlastnost "UnifiedGroupWelcomeMessageEnabled" True.

V případě, že chcete uvítací zprávu zakázat, použijte následující příkaz [EXO PowerShell:](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps)

`
Set-UnifiedGroup <groupname> -UnifiedGroupWelcomeMessageEnabled:$False
`
