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
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="dbb8e-102">Otázky týkající se použití Office Deployment Tool (ODT)</span><span class="sxs-lookup"><span data-stu-id="dbb8e-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="dbb8e-103">Nástroj pro nasazení sady Office stáhněte z [Webu služby Stažení softwaru](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="dbb8e-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="dbb8e-104">Po stažení souboru, spusťte samorozbalovací spustitelný soubor, který obsahuje nástroj Office Deployment Tool spustitelný (setup.exe) a ukázkový konfigurační soubor (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="dbb8e-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="dbb8e-105">**Vyloučit nebo odebrání produktů Office 365 ProPlus z klientských počítačů:**</span><span class="sxs-lookup"><span data-stu-id="dbb8e-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="dbb8e-106">Při instalaci sady Office 365 ProPlus, můžete vyloučit konkrétní produkty.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-106">When installing Office 365 ProPlus, you can exclude specific products.</span></span> <span data-ttu-id="dbb8e-107">Chcete-li to provést, postupujte podle pokynů pro instalaci sady Office s ODT, ale zahrnují ExcludeApp element v konfiguračním souboru.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="dbb8e-108">Tento soubor nainstaluje například Office 365 ProPlus produkty s výjimkou vydavatele:</span><span class="sxs-lookup"><span data-stu-id="dbb8e-108">For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="dbb8e-109">Přehled nástroje pro nasazení sady Office</span><span class="sxs-lookup"><span data-stu-id="dbb8e-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

