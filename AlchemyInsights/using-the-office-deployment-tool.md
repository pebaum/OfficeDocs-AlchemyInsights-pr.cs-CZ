---
title: Použití nástroje pro nasazení Office
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: fa40fef0de9b2e0e1fc329269c24e8bca9ed4146
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43726241"
---
# <a name="using-the-office-deployment-tool-odt"></a>Použití nástroje pro nasazení sady Office (ODT)

You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office. Nástroj pro nasazení sady Office (setup.exe) je spuštěn z příkazového řádku a používá konfigurační soubor XML k určení nastavení, která mají být použita při nasazování Sady Office.
  
1. Stáhněte si nejnovější verzi nástroje Pro nasazení sady Office ze [služby Stažení softwaru](https://go.microsoft.com/fwlink/p/?LinkID=626065).

2. Pomocí [Nástroje pro přizpůsobení Office (OCT)](https://config.office.com) vyberte předvolby nasazení a vytvořte konfigurační soubor XML. Exportujte konfigurační soubor a umístěte jej místně do stejné složky, ve které se nachází soubor setup.exe.

    **Poznámka:** K problémům s instalací sady Office obvykle dochází z důvodu chybně nakonfigurovaných nebo neformátovaných konfiguračních souborů. Chcete-li se těmto problémům vyhnout, doporučujeme k vytvoření konfiguračního souboru použít nástroj pro přizpůsobení sady Office. Do Nástroje pro vlastní nastavení Office můžete také importovat existující konfigurační soubory.

3. Z příkazového řádku se zvýšenými oprávněními přepněte do umístění, kde se nachází soubor setup.exe, a spusťte nástroj pro nasazení sady Office v režimu stahování a zadejte konfigurační soubor, který jste právě uložili. V tomto příkladu se konfigurační soubor nazývá Configuration.xml:
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. Spusťte nástroj pro nasazení sady Office v režimu konfigurace a určete konfigurační soubor.
    
  ```
  setup.exe /configure Configuration.xml
  ```

    **Poznámka:** Tento krok je nutné spustit z klientského počítače, do kterého chcete nainstalovat sadu Office, a musíte mít v tomto počítači oprávnění místního správce.

Další informace o používání Nástroje pro nasazení Office pro scénáře nasazení aplikací Microsoft 365 pro podnikové nasazení najdete [v tématu Přehled Nástroje pro nasazení Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Další podrobnosti o použití Nástroje pro přizpůsobení Office naleznete v [tématu Přehled nástroje pro přizpůsobení Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).
