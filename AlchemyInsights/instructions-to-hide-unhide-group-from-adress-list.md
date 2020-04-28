---
title: Pokyny ke skrytí/zobrazení skupiny ze seznamu adres
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "3161"
ms.openlocfilehash: 61ba34e6d554831da712a92401f26fabb02c26b7
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908337"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a>Skrytí skupiny Microsoft 365 ze seznamu adres (GAL)

Chcete-li skrýt skupinu Microsoft 365 před seznamy adres (GAL) klientů Exchange (například Outlook nebo OWA), použijte v prostředí EXO následující příkaz:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Chcete-li skrýt, aby se skupina Microsoft 365 nezoavká pro klienty Exchange, použijte v prostředí EXO následující příkaz:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

