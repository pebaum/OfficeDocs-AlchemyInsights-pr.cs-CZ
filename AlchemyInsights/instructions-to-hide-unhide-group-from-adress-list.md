---
title: Pokyny pro skrytí nebo zobrazení seznamu adres skupiny
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
ms.openlocfilehash: d0e0285701f1a5f308bdc682abaddf5cc2d34120
ms.sourcegitcommit: defe2c412567b596fa8c3ab52111bde712ebb314
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/29/2019
ms.locfileid: "37768908"
---
# <a name="hide-office-365-group-from-address-list-gal"></a>Skrýt skupinu Office 365 ze seznamu adres (GAL)

Chcete-li skrýt skupinu sady Office 365 ze seznamu adres klientů serveru Exchange (například aplikace Outlook nebo OWA), použijte v prostředí EXO následující příkaz:

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

Chcete-li skrýt skupinu Office 365 před tím, než se zobrazí klientům serveru Exchange, použijte v prostředí EXO následující příkaz:

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

