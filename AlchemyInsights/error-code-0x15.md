---
title: Kód chyby 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Pokud se zobrazuje chyba při aktivaci sady Office 2013 na nasazení služby Remote Desktop Services (RDS), zvažte povolení ADAL úpravou registru.
ms.openlocfilehash: 4ef2943e5a529368fa2c614e4431cf180924fbb8
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36526975"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Chyba při aktivaci sady Office 2013 na vzdálené ploše

Pokud se zobrazuje chyba při aktivaci sady Office 2013 na nasazení služby Remote Desktop Services (RDS), zvažte povolení ADAL úpravou registru.
  
|**Klíč registru**|**Typ**|**Hodnota**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Další informace naleznete v tématu [Povolení moderní ověřování Office 2013 na zařízení systému Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL je povolena ve výchozím nastavení sady Office 365 ProPlus a Office 2016. Remote Desktop Services (RDS) se dříve nazývala Terminálové služby.
  