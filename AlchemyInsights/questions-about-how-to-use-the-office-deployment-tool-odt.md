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
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36553533"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="cbd22-102">Otázky týkající se použití Office Deployment Tool (ODT)</span><span class="sxs-lookup"><span data-stu-id="cbd22-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="cbd22-103">Nástroj pro nasazení sady Office stáhněte z [Webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="cbd22-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="cbd22-104">Po stažení souboru, spusťte samorozbalovací spustitelný soubor, který obsahuje nástroj Office Deployment Tool spustitelný (setup.exe) a ukázkový konfigurační soubor (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="cbd22-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="cbd22-105">**Vyloučit nebo odebrání produktů Office 365 ProPlus z klientských počítačů:**</span><span class="sxs-lookup"><span data-stu-id="cbd22-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="cbd22-106">Při instalaci sady Office 365 ProPlus, můžete vyloučit konkrétní produkty.</span><span class="sxs-lookup"><span data-stu-id="cbd22-106">When installing Office 365 ProPlus, you can exclude specific products.</span></span> <span data-ttu-id="cbd22-107">Chcete-li to provést, postupujte podle pokynů pro instalaci sady Office s ODT, ale zahrnují ExcludeApp element v konfiguračním souboru.</span><span class="sxs-lookup"><span data-stu-id="cbd22-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="cbd22-108">Tento soubor nainstaluje například Office 365 ProPlus produkty s výjimkou vydavatele:</span><span class="sxs-lookup"><span data-stu-id="cbd22-108">For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="cbd22-109">Přehled nástroje pro nasazení sady Office</span><span class="sxs-lookup"><span data-stu-id="cbd22-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

