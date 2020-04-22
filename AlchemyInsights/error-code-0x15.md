---
title: Kód chyby 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Pokud se při aktivaci nasazení Office 2013 ve vzdálené ploše (RDS) zobrazuje chyba, zvažte povolení adalu úpravou registru.
ms.openlocfilehash: 566d63cbe37d295b3546b9d7d5b14dfc8e8fe0ec
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703131"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Chyba při aktivaci Office 2013 ve Službě Vzdálená plocha

Pokud se při aktivaci nasazení Office 2013 ve vzdálené ploše (RDS) zobrazuje chyba, zvažte povolení adalu úpravou registru.
  
|**Klíč registru**|**Typ**|**Hodnota**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |Reg_dword  <br/> |1  <br/> |

Další informace najdete [v tématu Povolení moderního ověřování pro Office 2013 na zařízeních s Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je ve výchozím nastavení povolen v Aplikacích Microsoft365 pro podniky a Office 2016. Služba Vzdálená plocha (RDS) byla dříve pojmenována Terminálová služba.
  