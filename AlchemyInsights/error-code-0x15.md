---
title: Kód chyby 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Pokud se zobrazuje chyba při aktivaci sady Office 2013 na nasazení služby Remote Desktop Services (RDS), zvažte povolení ADAL úpravou registru.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281526"
---
Pokud se zobrazuje chyba při aktivaci sady Office 2013 na nasazení služby Remote Desktop Services (RDS), zvažte povolení ADAL úpravou registru. 
  
|**Klíč registru**|**Typ**|**Value (Hodnota)**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |
   
Další informace naleznete v tématu [Povolení moderní ověřování Office 2013 na zařízení systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je povolena ve výchozím nastavení sady Office 365 ProPlus a Office 2016. > Vzdálené plochy (RDS) se dříve nazývala Terminálové služby. 
  

