---
title: Pomocí nástroje pro nasazení sady Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: 874bb7883bca4f062e85963a6828a771cd2dad9b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36531568"
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
