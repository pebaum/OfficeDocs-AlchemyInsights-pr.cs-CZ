---
title: Pomocí nástroje pro nasazení sady Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: c7e0e96f225030590fdd516eaf3115c93a6335b6
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29898639"
---
# <a name="using-the-office-deployment-tool-odt"></a>Pomocí nástroj Office Deployment Tool (ODT)

Nasazení služeb Office 365 verzích sady Office pomocí Office Deployment Tool (ODT). Nástroj pro nasazení sady Office (setup.exe) je spouštěn z příkazového řádku a konfiguračního souboru XML používá k určení nastavení, které chcete použít při nasazení sady Office.
  
1. Stáhněte nejnovější verzi nástroje pro nasazení sady Office z [Webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).
    
2. Pomocí [Nástroje pro přizpůsobení sady Office (OCT)](https://config.office.com) vyberte předvolby nasazení a vytvoření konfiguračního souboru XML. Export konfiguračního souboru a jeho umístění místně do stejné složky, kde je umístěn setup.exe. 
    
    **Poznámka:** Instalace sady Office problémy běžně dochází k vyřízení na nesprávně nakonfigurovaný nebo malformatted konfigurační soubory. Chcete-li zabránit tyto problémy, doporučujeme použít nástroj pro přizpůsobení sady Office k vytvoření konfiguračního souboru. Můžete také importovat existující konfigurační soubory v nástroj pro přizpůsobení sady Office. 
    
3. Z příkazového řádku se zvýšenými oprávněními přejděte do umístění, kde je umístěn setup.exe a spusťte nástroj pro nasazení sady Office v režimu stahování a zadat konfigurační soubor, který jste právě uložili. V tomto příkladu je název konfiguračního souboru Configuration.xml:
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Spusťte nástroj pro nasazení sady Office v konfiguraci režimu a zadat konfigurační soubor.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **Poznámka:** Z klientského počítače, na kterém chcete nainstalovat sadu Office a musí mít oprávnění místního správce na tomto počítači je třeba spustit tento krok. 
    
Další informace o použití nástroje pro nasazení sady Office pro Office 365 ProPlus scénářů nasazení, naleznete v tématu [Přehled nástroje pro nasazení sady Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Další informace o tom, jak použít nástroj pro přizpůsobení sady Office naleznete v tématu [Přehled nástroje pro přizpůsobení sady Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).
  

