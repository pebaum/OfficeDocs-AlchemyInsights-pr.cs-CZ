---
title: Připojení k modulu MSCommerce
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3529"
ms.openlocfilehash: 10ef2e8fa7c564d53177a52136eb48cd709e5c55
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158490"
---
# <a name="mscommerce-requires-a-company-or-billing-administrator-account"></a>MSCommerce vyžaduje účet správce společnosti nebo fakturace

Modul MSCommerce vyžaduje účet s oprávněními správce fakturace společnosti nebo fakturace. Pokud se zobrazuje následující chyba, budete se muset znovu spojit s jiným účtem.

*ErrorMessage - Vzdálený server vrátil chybu: (403) Zakázáno. ErrorDetails - Na C:\Program Files\WindowsPowerShell\Moduly\MSCommerce\1.2\MSCommerce.psm1:216 char:5*<br>
*+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HandleError -ErrorContext $_ -CustomErrorMessage "Nepodařilo se retri ...*<br>
\+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ CategoryInfo : NotSpecified: (:) [Chyba zápisu], WriteErrorException*<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ Plně kvalifikovanýerrord : Microsoft.PowerShell.Commands.WriteErrorException,HandleError*

Pokud váš účet nemá oprávnění Správce společnosti nebo správce fakturace, obraťte se na správce IT.
