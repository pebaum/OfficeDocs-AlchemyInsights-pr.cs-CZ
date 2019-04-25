---
title: Otázky týkající se použití Office Deployment Tool (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: e91d40f872dd401ee210ac05eb39d64b6fb88027
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32371761"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Otázky týkající se použití Office Deployment Tool (ODT)

Nástroj pro nasazení sady Office stáhněte z [Webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Po stažení souboru, spusťte samorozbalovací spustitelný soubor, který obsahuje nástroj Office Deployment Tool spustitelný (setup.exe) a ukázkový konfigurační soubor (configuration.xml).
  
 **Vyloučit nebo odebrání produktů Office 365 ProPlus z klientských počítačů:**
  
Při instalaci sady Office 365 ProPlus, můžete vyloučit konkrétní produkty. Chcete-li to provést, postupujte podle pokynů pro instalaci sady Office s ODT, ale zahrnují ExcludeApp element v konfiguračním souboru. Tento soubor nainstaluje například Office 365 ProPlus produkty s výjimkou vydavatele:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Přehled nástroje pro nasazení sady Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

