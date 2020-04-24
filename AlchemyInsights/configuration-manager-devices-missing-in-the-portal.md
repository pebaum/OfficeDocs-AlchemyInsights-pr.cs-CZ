---
title: Zařízení v Configuration Manageru chybí na portálu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: 7a11ad3c6970be2c52a7cf0696bd3810b9bd665a
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789702"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a><span data-ttu-id="2bd2d-102">Zařízení v Configuration Manageru chybí na portálu</span><span class="sxs-lookup"><span data-stu-id="2bd2d-102">Configuration Manager devices missing in the portal</span></span>

<span data-ttu-id="2bd2d-103">Pro fungování synchronizace je nutné, aby [požadované internetové koncové body](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) byly dostupné z místního serveru, který je hostitelem role Bod připojení služby.</span><span class="sxs-lookup"><span data-stu-id="2bd2d-103">For device sync to work, [required internet endpoints](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) must be reachable from the on-premise server hosting the Service Connection Point role.</span></span> <span data-ttu-id="2bd2d-104">Pokud potřebujete vyřešit potíže se synchronizací zařízení, nahlédněte prosím do souboru **CMGatewaySyncUploadWorker.log**, který se nachází u bodu připojení služby.</span><span class="sxs-lookup"><span data-stu-id="2bd2d-104">To troubleshoot device sync, please review the **CMGatewaySyncUploadWorker.log** located on the service connection point.</span></span>

<span data-ttu-id="2bd2d-105">Přečtěte si další informace o [připojení tenanta v Microsoft Endpoint Manageru](https://docs.microsoft.com/configmgr/tenant-attach/).</span><span class="sxs-lookup"><span data-stu-id="2bd2d-105">Learn more about [Tenant attach in Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).</span></span>
