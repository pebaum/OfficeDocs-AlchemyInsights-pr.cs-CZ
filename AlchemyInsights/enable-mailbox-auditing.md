---
title: Povolení auditování poštovní schránky
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 2bcfb7cc174cd58b21e1bb0c82f0d7cdb25e2fdd
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506947"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="fdb1f-102">Povolení auditování poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="fdb1f-102">Enable mailbox auditing</span></span>

<span data-ttu-id="fdb1f-103">Chcete-li povolit auditování poštovních schránek pro jednoho uživatele nebo celou organizaci, je nutné spustit následující rutiny ze vzdáleného prostředí Napájení:</span><span class="sxs-lookup"><span data-stu-id="fdb1f-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="fdb1f-104">**Jeden uživatel**</span><span class="sxs-lookup"><span data-stu-id="fdb1f-104">**Single User**</span></span>
  
<span data-ttu-id="fdb1f-105">Set-Mailbox -Identita "Jane Dow" -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="fdb1f-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="fdb1f-106">**Organizace**</span><span class="sxs-lookup"><span data-stu-id="fdb1f-106">**Organization**</span></span>
  
<span data-ttu-id="fdb1f-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="fdb1f-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="fdb1f-108">Víc se uč</span><span class="sxs-lookup"><span data-stu-id="fdb1f-108">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

