---
title: Otázky týkající se použití nástroje pro nasazení sady Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 96d3f70f554f71c43d6458ec8debc099cd9fb040
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43698051"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Otázky týkající se použití nástroje pro nasazení sady Office (ODT)

Stáhněte nástroj pro nasazení sady Office ze [služby Stažení softwaru](https://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Po stažení souboru spusťte samorozbalovací spustitelný soubor, který obsahuje spustitelný soubor nástroje pro nasazení sady Office (setup.exe) a ukázkový konfigurační soubor (configuration.xml).
  
 **Vyloučení nebo odebrání aplikací Microsoft 365 pro podnikové produkty z klientských počítačů:**
  
Při instalaci aplikací Microsoft 365 pro podniky můžete vyloučit konkrétní produkty. Chcete-li tak učinit, postupujte podle pokynů pro instalaci Office s ODT, ale zahrnout ExcludeApp prvek v konfiguračním souboru. Tento konfigurační soubor například nainstaluje všechny aplikace Microsoft 365 pro podnikové produkty s výjimkou aplikace Publisher:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Přehled nástroje pro nasazení Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

