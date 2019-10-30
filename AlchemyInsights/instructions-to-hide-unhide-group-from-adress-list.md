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
# <a name="hide-office-365-group-from-address-list-gal"></a><span data-ttu-id="a0676-102">Skrýt skupinu Office 365 ze seznamu adres (GAL)</span><span class="sxs-lookup"><span data-stu-id="a0676-102">Hide Office 365 group from address list (GAL)</span></span>

<span data-ttu-id="a0676-103">Chcete-li skrýt skupinu sady Office 365 ze seznamu adres klientů serveru Exchange (například aplikace Outlook nebo OWA), použijte v prostředí EXO následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="a0676-103">To hide an Office 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="a0676-104">Chcete-li skrýt skupinu Office 365 před tím, než se zobrazí klientům serveru Exchange, použijte v prostředí EXO následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="a0676-104">To hide the Office 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

