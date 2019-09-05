---
title: Povolit auditování poštovní schránky
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 73517f46935a67a4a8a3e4770090ac897fe67979
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736246"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="d9b3a-102">Povolit auditování poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="d9b3a-102">Enable mailbox auditing</span></span>

<span data-ttu-id="d9b3a-103">Chcete-li povolit auditování poštovní schránky pro jednoho nebo celou organizaci, musí být z prostředí vzdáleného napájení spuštěny následující rutiny:</span><span class="sxs-lookup"><span data-stu-id="d9b3a-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="d9b3a-104">**Jeden uživatel**</span><span class="sxs-lookup"><span data-stu-id="d9b3a-104">**Single User**</span></span>
  
<span data-ttu-id="d9b3a-105">Set-Mailbox-identita "Jane Dow"-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="d9b3a-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="d9b3a-106">**Organizace**</span><span class="sxs-lookup"><span data-stu-id="d9b3a-106">**Organization**</span></span>
  
<span data-ttu-id="d9b3a-107">Get-Mailbox-ResultSize neomezený-filtr {RecipientTypeDetails-EQ "UserMailbox"} | Set-poštovní schránka-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="d9b3a-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="d9b3a-108">Víc se uč</span><span class="sxs-lookup"><span data-stu-id="d9b3a-108">Learn more</span></span>](https://docs.microsoft.com/office365/securitycompliance/enable-mailbox-auditing)
  

