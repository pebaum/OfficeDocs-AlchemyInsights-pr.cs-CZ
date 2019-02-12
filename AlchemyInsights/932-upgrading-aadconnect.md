---
title: 932 AADConnect inovace
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/8/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 8f43f36c-9722-43a4-b0de-c5341c06dac5
ms.openlocfilehash: 8038d5ef768d6ee228db7d038ad71d926f4047f3
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29937937"
---
# <a name="upgrade-azure-ad-connect"></a>Inovace Azure AD připojit

Standardně je povoleno automatické inovace pro Azure AD připojit, což pomůže zajistit, že používáte nejnovější verzi. Chcete-li ověřit nastavení automatického upgradu, použijte rutiny **Get-ADSyncAutoUpgrade** v prostředí PowerShell Azure AD. Rutiny vrátí jednu z následujících hodnot: 
  
- **Povoleno**: je povolen automatický upgrade. 
    
- **Zakázáno**: automatický upgrade je zakázáno. 
    
- **Suspended**: systém je již oprávněni přijímat automatické upgrady. Nelze nastavit tuto hodnotu; systém je nastaven. 
    
Další informace naleznete v tématu [automatické inovace](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-feature-automatic-upgrade).
  
Chcete-li stáhnout nejnovější verzi Azure AD připojit, přejděte na [https://www.microsoft.com/download/details.aspx?id=47594](https://www.microsoft.com/download/details.aspx?id=47594).
  

