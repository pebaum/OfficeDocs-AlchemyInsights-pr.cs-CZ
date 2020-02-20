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
# <a name="mscommerce-requires-a-company-or-billing-administrator-account"></a><span data-ttu-id="55e86-102">MSCommerce vyžaduje účet správce společnosti nebo fakturace</span><span class="sxs-lookup"><span data-stu-id="55e86-102">MSCommerce requires a Company or Billing Administrator account</span></span>

<span data-ttu-id="55e86-103">Modul MSCommerce vyžaduje účet s oprávněními správce fakturace společnosti nebo fakturace.</span><span class="sxs-lookup"><span data-stu-id="55e86-103">The MSCommerce module requires an account with Company or Billing Administrator privileges.</span></span> <span data-ttu-id="55e86-104">Pokud se zobrazuje následující chyba, budete se muset znovu spojit s jiným účtem.</span><span class="sxs-lookup"><span data-stu-id="55e86-104">If you are receiving the following error, you will need to reconnect with a different account.</span></span>

<span data-ttu-id="55e86-105">*ErrorMessage - Vzdálený server vrátil chybu: (403) Zakázáno. ErrorDetails - Na C:\Program Files\WindowsPowerShell\Moduly\MSCommerce\1.2\MSCommerce.psm1:216 char:5*</span><span class="sxs-lookup"><span data-stu-id="55e86-105">*ErrorMessage - The remote server returned an error: (403) Forbidden. ErrorDetails - At C:\Program Files\WindowsPowerShell\Modules\MSCommerce\1.2\MSCommerce.psm1:216 char:5*</span></span><br>
<span data-ttu-id="55e86-106">*+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HandleError -ErrorContext $_ -CustomErrorMessage "Nepodařilo se retri ...*</span><span class="sxs-lookup"><span data-stu-id="55e86-106">*+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HandleError -ErrorContext $_ -CustomErrorMessage "Failed to retri ...*</span></span><br>
<span data-ttu-id="55e86-107">\+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</span><span class="sxs-lookup"><span data-stu-id="55e86-107">\+&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</span></span><br>
<span data-ttu-id="55e86-108">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ CategoryInfo : NotSpecified: (:) [Chyba zápisu], WriteErrorException*</span><span class="sxs-lookup"><span data-stu-id="55e86-108">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ CategoryInfo          : NotSpecified: (:) [Write-Error], WriteErrorException*</span></span><br>
<span data-ttu-id="55e86-109">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ Plně kvalifikovanýerrord : Microsoft.PowerShell.Commands.WriteErrorException,HandleError*</span><span class="sxs-lookup"><span data-stu-id="55e86-109">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*+ FullyQualifiedErrorId : Microsoft.PowerShell.Commands.WriteErrorException,HandleError*</span></span>

<span data-ttu-id="55e86-110">Pokud váš účet nemá oprávnění Správce společnosti nebo správce fakturace, obraťte se na správce IT.</span><span class="sxs-lookup"><span data-stu-id="55e86-110">If your account does not have Company or Billing Administrator privileges, contact your IT Admin.</span></span>