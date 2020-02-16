---
title: Project Online je ve stavu jen pro čtení.
ms.author: pebaum
author: pebaum
manager: pamg
ms.date: 4/10/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1776"
- "9000205"
ms.openlocfilehash: 34fecf93f39659cbd26998697090957c6af45aa0
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "41969317"
---
# <a name="project-online-is-in-a-read-only-state"></a><span data-ttu-id="f4d89-102">Project Online je ve stavu jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="f4d89-102">Project Online is in a read-only state</span></span>

<span data-ttu-id="f4d89-103">Existují tři běžné důvody, proč může Project Online dosáhnout stavu jen pro čtení:</span><span class="sxs-lookup"><span data-stu-id="f4d89-103">There are three common reasons why Project Online may reach a read-only state:</span></span>

1. <span data-ttu-id="f4d89-104">Organizace mají pouze licenci (licence) Project Online Essentials.</span><span class="sxs-lookup"><span data-stu-id="f4d89-104">Organizations have a Project Online Essentials license(s) only.</span></span> <span data-ttu-id="f4d89-105">To nestačí, aby místo naživu, a to bude nakonec dostat de-provisioned.</span><span class="sxs-lookup"><span data-stu-id="f4d89-105">This isn't enough to keep the site alive and it will eventually get de-provisioned.</span></span><span data-ttu-id="f4d89-106">Umístíme stránky do stavu jen pro čtení, aby správci věděli, že je něco špatně a mohou získat správné licence.</span><span class="sxs-lookup"><span data-stu-id="f4d89-106"> We place the site in a read-only state so that Admins know something is wrong and can acquire the correct licenses.</span></span> <span data-ttu-id="f4d89-107">Správci budou muset přidat licenci Project Online Professional a/nebo Premium.</span><span class="sxs-lookup"><span data-stu-id="f4d89-107">Admins will need to add a Project Online Professional and/or Premium license.</span></span> <span data-ttu-id="f4d89-108">Místo vyjde z jen pro čtení v tomto bodě.</span><span class="sxs-lookup"><span data-stu-id="f4d89-108">The site will come out of read-only at that point.</span></span> <span data-ttu-id="f4d89-109">Další informace naleznete v tématu [Porovnání řešení řízení projektů](https://products.office.com/project/compare-microsoft-project-management-software?tab=1).</span><span class="sxs-lookup"><span data-stu-id="f4d89-109">For more info, see [Compare Project Management Solutions](https://products.office.com/project/compare-microsoft-project-management-software?tab=1).</span></span>
2. <span data-ttu-id="f4d89-110">Bylo dosaženo přidělené kvóty.</span><span class="sxs-lookup"><span data-stu-id="f4d89-110">Assigned quota has been reached.</span></span> <span data-ttu-id="f4d89-111">Další informace najdete v [tématu Kvóta Project Web Appu](https://docs.microsoft.com/projectonline/tune-project-online-performance#project-web-app-quota).</span><span class="sxs-lookup"><span data-stu-id="f4d89-111">For more info, see [Project Web App Quota](https://docs.microsoft.com/projectonline/tune-project-online-performance#project-web-app-quota).</span></span> <span data-ttu-id="f4d89-112">Zkontrolujte, zda [nakonfigurujte souhrn dat časově uspořádaného vykazování v Projectu Online](https://docs.microsoft.com/ProjectOnline/configure-rollup-of-timephased-reporting-data-in-project-online?redirectSourcePath=%252fen-us%252farticle%252fConfigure-rollup-of-timephased-reporting-data-in-Project-Online-da8487fe-899e-4510-a264-e2ebc948928c) a zjistěte, jak může mít podrobné hlášení dopad na využití kvót.</span><span class="sxs-lookup"><span data-stu-id="f4d89-112">Check [Configure rollup of timephased reporting data in Project Online](https://docs.microsoft.com/ProjectOnline/configure-rollup-of-timephased-reporting-data-in-project-online?redirectSourcePath=%252fen-us%252farticle%252fConfigure-rollup-of-timephased-reporting-data-in-Project-Online-da8487fe-899e-4510-a264-e2ebc948928c) to see how reporting granularity may impact quota usage.</span></span>
3. <span data-ttu-id="f4d89-113">Jen pro čtení může být velmi dočasný stav, který může nastat během údržby.</span><span class="sxs-lookup"><span data-stu-id="f4d89-113">Read-only can be a very temporary condition that can occur during maintenance.</span></span> <span data-ttu-id="f4d89-114">Většina údržby není ani všiml našich zákazníků a nebudete často vidět, ale tam jsou časy, kdy krátké období jen pro čtení jsou zkušení.</span><span class="sxs-lookup"><span data-stu-id="f4d89-114">Most maintenance is not even noticed by our customers and you will not often see this, but there are times when short periods of read-only are experienced.</span></span>
