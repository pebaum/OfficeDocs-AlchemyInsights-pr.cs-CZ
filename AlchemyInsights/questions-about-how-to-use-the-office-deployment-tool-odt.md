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
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="4eedb-102">Otázky týkající se použití nástroje ODT (Office Deployment Tool)</span><span class="sxs-lookup"><span data-stu-id="4eedb-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="4eedb-103">Stáhněte nástroj pro nasazení sady Office z [webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="4eedb-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="4eedb-104">Po stažení souboru spusťte samorozbalovací spustitelný soubor, který obsahuje spustitelný program nástroje pro nasazení sady Office (Setup. exe) a ukázkový konfigurační soubor (Configuration. XML).</span><span class="sxs-lookup"><span data-stu-id="4eedb-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="4eedb-105">**Vyloučení nebo odebrání produktů sady Office 365 ProPlus z klientských počítačů:**</span><span class="sxs-lookup"><span data-stu-id="4eedb-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="4eedb-106">Při instalaci sady Office 365 ProPlus můžete vyloučit určité produkty.</span><span class="sxs-lookup"><span data-stu-id="4eedb-106">When installing Office 365 ProPlus, you can exclude specific products.</span></span> <span data-ttu-id="4eedb-107">Chcete-li tak učinit, postupujte podle kroků pro instalaci sady Office s ODT, ale do konfiguračního souboru zahrňte element ExcludeApp.</span><span class="sxs-lookup"><span data-stu-id="4eedb-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="4eedb-108">Tento konfigurační soubor například nainstaluje všechny produkty sady Office 365 ProPlus s výjimkou aplikace Publisher:</span><span class="sxs-lookup"><span data-stu-id="4eedb-108">For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="4eedb-109">Přehled nástroje pro nasazení sady Office</span><span class="sxs-lookup"><span data-stu-id="4eedb-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

