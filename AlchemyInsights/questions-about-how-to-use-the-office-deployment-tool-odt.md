---
title: Otázky týkající se použití nástroje ODT (Office Deployment Tool)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36553533"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Otázky týkající se použití nástroje ODT (Office Deployment Tool)

Stáhněte nástroj pro nasazení sady Office z [webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Po stažení souboru spusťte samorozbalovací spustitelný soubor, který obsahuje spustitelný program nástroje pro nasazení sady Office (Setup. exe) a ukázkový konfigurační soubor (Configuration. XML).
  
 **Vyloučení nebo odebrání produktů sady Office 365 ProPlus z klientských počítačů:**
  
Při instalaci sady Office 365 ProPlus můžete vyloučit určité produkty. Chcete-li tak učinit, postupujte podle kroků pro instalaci sady Office s ODT, ale do konfiguračního souboru zahrňte element ExcludeApp. Tento konfigurační soubor například nainstaluje všechny produkty sady Office 365 ProPlus s výjimkou aplikace Publisher:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Přehled nástroje pro nasazení sady Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

