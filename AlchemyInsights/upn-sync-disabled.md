---
title: Zakázat synchronizaci UPN
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 2a03ac64d92c07b523b015850251b33c58bb76f8
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32423536"
---
# <a name="upn-sync-disabled"></a>Zakázat synchronizaci UPN

Je-li spuštěna synchronizace Azure AD před 30. března 2016, spusťte následující rutiny prostředí PowerShell Azure AD Povolit porovnávání měkké UPN pro organizace pouze:
  
 **Sada MsolDirSyncFeature-funkce EnableSoftMatchOnUpn-povolit $True**
  
Rozlišovat měkké UPN je automaticky zapnuta pro organizace, které je spuštěna synchronizace Azure AD, nebo po 30. března 2016.
  
Další informace o povolení měkké shoda na UPN a další funkce synchronizace naleznete v [funkce služby synchronizace Azure AD připojit](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).
  

