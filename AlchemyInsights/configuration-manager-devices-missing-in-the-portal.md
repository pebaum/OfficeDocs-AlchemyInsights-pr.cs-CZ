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
# <a name="configuration-manager-devices-missing-in-the-portal"></a>Zařízení v Configuration Manageru chybí na portálu

Pro fungování synchronizace je nutné, aby [požadované internetové koncové body](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) byly dostupné z místního serveru, který je hostitelem role Bod připojení služby. Pokud potřebujete vyřešit potíže se synchronizací zařízení, nahlédněte prosím do souboru **CMGatewaySyncUploadWorker.log**, který se nachází u bodu připojení služby.

Přečtěte si další informace o [připojení tenanta v Microsoft Endpoint Manageru](https://docs.microsoft.com/configmgr/tenant-attach/).
