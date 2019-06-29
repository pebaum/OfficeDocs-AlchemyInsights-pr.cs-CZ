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
ms.openlocfilehash: 998f914f38fa9d1925f7003e634d7f11550f47da
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35365518"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="6d3a6-102">Pomocí nástroj Office Deployment Tool (ODT)</span><span class="sxs-lookup"><span data-stu-id="6d3a6-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="6d3a6-103">Nasazení služeb Office 365 verzích sady Office pomocí Office Deployment Tool (ODT).</span><span class="sxs-lookup"><span data-stu-id="6d3a6-103">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office.</span></span> <span data-ttu-id="6d3a6-104">Nástroj pro nasazení sady Office (setup.exe) je spouštěn z příkazového řádku a konfiguračního souboru XML používá k určení nastavení, které chcete použít při nasazení sady Office.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-104">The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="6d3a6-105">Stáhněte nejnovější verzi nástroje pro nasazení sady Office z [Webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="6d3a6-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>

2. <span data-ttu-id="6d3a6-106">Pomocí [Nástroje pro přizpůsobení sady Office (OCT)](https://config.office.com) vyberte předvolby nasazení a vytvoření konfiguračního souboru XML.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-106">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file.</span></span> <span data-ttu-id="6d3a6-107">Export konfiguračního souboru a jeho umístění místně do stejné složky, kde je umístěn setup.exe.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-107">Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span>

    <span data-ttu-id="6d3a6-108">**Poznámka:** Instalace sady Office problémy běžně dochází k vyřízení na nesprávně nakonfigurovaný nebo malformatted konfigurační soubory.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-108">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files.</span></span> <span data-ttu-id="6d3a6-109">Chcete-li zabránit tyto problémy, doporučujeme použít nástroj pro přizpůsobení sady Office k vytvoření konfiguračního souboru.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-109">To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file.</span></span> <span data-ttu-id="6d3a6-110">Můžete také importovat existující konfigurační soubory v nástroj pro přizpůsobení sady Office.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-110">You can also import existing configuration files into the Office Customization Tool.</span></span>

3. <span data-ttu-id="6d3a6-111">Z příkazového řádku se zvýšenými oprávněními přejděte do umístění, kde je umístěn setup.exe a spusťte nástroj pro nasazení sady Office v režimu stahování a zadat konfigurační soubor, který jste právě uložili.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-111">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved.</span></span> <span data-ttu-id="6d3a6-112">V tomto příkladu je název konfiguračního souboru Configuration.xml:</span><span class="sxs-lookup"><span data-stu-id="6d3a6-112">In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="6d3a6-113">Spusťte nástroj pro nasazení sady Office v konfiguraci režimu a zadat konfigurační soubor.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="6d3a6-114">**Poznámka:** Z klientského počítače, na kterém chcete nainstalovat sadu Office a musí mít oprávnění místního správce na tomto počítači je třeba spustit tento krok.</span><span class="sxs-lookup"><span data-stu-id="6d3a6-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span>

<span data-ttu-id="6d3a6-115">Další informace o použití nástroje pro nasazení sady Office pro Office 365 ProPlus scénářů nasazení, naleznete v tématu [Přehled nástroje pro nasazení sady Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="6d3a6-115">To learn more about using Office Deployment Tool for your Office 365 ProPlus deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span> <span data-ttu-id="6d3a6-116">Další informace o tom, jak použít nástroj pro přizpůsobení sady Office naleznete v tématu [Přehled nástroje pro přizpůsobení sady Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="6d3a6-116">For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
