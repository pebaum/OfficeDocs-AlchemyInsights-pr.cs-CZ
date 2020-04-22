---
title: 1048 5.7.750 Služba není k dispozici. Klientovi bylo zablokováno odesílání z neregistrovaných domén
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom:
- "1048"
- "3100026"
ms.openlocfilehash: 48b9c2de27f8d7f52215c3a3d547bdf746a3a4cd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43676706"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a><span data-ttu-id="6d5de-103">5.7.750 Klient zablokoval odesílání z neregistrované domény</span><span class="sxs-lookup"><span data-stu-id="6d5de-103">5.7.750 Client blocked from sending from unregistered domain</span></span>

<span data-ttu-id="6d5de-104">K chybě dochází, když se velký objem zpráv odesílá z domén, které nejsou zřízeny ve vašem tenantovi (přidány jako přijaté domény a ověřeny).</span><span class="sxs-lookup"><span data-stu-id="6d5de-104">The error occurs when a large volume of messages are sent from domains that aren't provisioned in your tenant (added as accepted domains and validated).</span></span>

<span data-ttu-id="6d5de-105">Chcete-li se této chybě vyhnout, můžete použít konektor toku pošty založené na certifikátu, kde doména certifikátu je zřízená doména, nebo můžete zřídit všechny odesílající domény.</span><span class="sxs-lookup"><span data-stu-id="6d5de-105">To avoid this error, you can use a certificate-based mail flow connector where the certificate's domain is a provisioned domain, or you can provision all sending domains.</span></span>
