---
title: 1048 5.7.750 služba není k dispozici. Klient zablokováno odesílání z registrace domén
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8cf6d70b-9a78-4f04-ac59-7ffcf44ffd22
ms.custom: 1048
ms.openlocfilehash: 06be6babc524ae0d8065355218426c695f49be66
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32365855"
---
# <a name="57750-client-blocked-from-sending-from-unregistered-domain"></a><span data-ttu-id="21a34-103">5.7.750 klient zablokováno odesílání z registrace domény</span><span class="sxs-lookup"><span data-stu-id="21a34-103">5.7.750 Client blocked from sending from unregistered domain</span></span>

<span data-ttu-id="21a34-104">K této chybě dojde, když velkou svazku zprávy jsou odesílány z domén, které nejsou zřízeny ve službách Office 365 (přidány jako přijaté domény a ověření).</span><span class="sxs-lookup"><span data-stu-id="21a34-104">The error occurs when a large volume of messages are sent from domains that aren't provisioned in Office 365 (added as accepted domains and validated).</span></span>

<span data-ttu-id="21a34-105">Chcete-li se vyhnout této chybě, můžete toku konektor pošty na základě certifikátů, kde je certifikát domény je zřízena doména nebo zřizujete všechny odesílající domény.</span><span class="sxs-lookup"><span data-stu-id="21a34-105">To avoid this error, you can use a certificate-based mail flow connector where the certificate's domain is a provisioned domain, or you can provision all sending domains.</span></span>
