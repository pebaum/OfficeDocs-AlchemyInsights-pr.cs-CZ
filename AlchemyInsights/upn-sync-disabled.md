---
title: Zakázat synchronizaci UPN
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 027782bb2a6b892df6201f3c3bf55151ef7b9db7
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/30/2019
ms.locfileid: "29657964"
---
# <a name="upn-sync-disabled"></a>Zakázat synchronizaci UPN

Je-li spuštěna synchronizace Azure AD před 30. března 2016, spusťte následující rutiny prostředí PowerShell Azure AD Povolit porovnávání měkké UPN pro organizace pouze:
  
 **Sada MsolDirSyncFeature-funkce EnableSoftMatchOnUpn-povolit $True**
  
Rozlišovat měkké UPN je automaticky zapnuta pro organizace, které je spuštěna synchronizace Azure AD, nebo po 30. března 2016.
  
Další informace o povolení měkké shoda na UPN a další funkce synchronizace naleznete v [funkce služby synchronizace Azure AD připojit](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).
  

