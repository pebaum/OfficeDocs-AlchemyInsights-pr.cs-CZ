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
description: Pokud se při aktivaci nasazení Office 2013 ve službě Vzdálená plocha (RDS) zobrazuje chyba, zvažte povolení ADAL úpravou registru.
ms.openlocfilehash: 468d13e59602cf173ed2e17af44c66babfc28703
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506839"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Chyba při aktivaci Office 2013 ve službě Vzdálená plocha

Pokud se při aktivaci nasazení Office 2013 ve službě Vzdálená plocha (RDS) zobrazuje chyba, zvažte povolení ADAL úpravou registru.
  
|**Klíč registru**|**Typ**|**Hodnota**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Další informace najdete v tématu [Povolení moderního ověřování pro Office 2013 na zařízeních s Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je ve výchozím nastavení povolena v Aplikacích Microsoft 365 pro podniky a Office 2016. Služba Vzdálená plocha (RDS) byla dříve pojmenována Terminálová služba.
  