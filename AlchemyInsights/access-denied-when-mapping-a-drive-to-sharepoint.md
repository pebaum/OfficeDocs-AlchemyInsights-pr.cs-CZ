---
title: Přístup byl odepřen při mapování jednotky na SharePoint
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b7da3918-969f-40bb-acb3-fbc762605504
ms.openlocfilehash: 23ee86df5404b6f20f3a4b605038b31b6f9fd731
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687359"
---
# <a name="fix-problems-with-sharepoint-libraries-mapped-to-network-drives"></a><span data-ttu-id="31e98-102">Řešení problémů s knihovnami SharePointu namapovanými na síťové jednotky</span><span class="sxs-lookup"><span data-stu-id="31e98-102">Fix problems with SharePoint libraries mapped to network drives</span></span>

<span data-ttu-id="31e98-103">Při přechodu na namapovanou síťovou jednotku se může zobrazit jedna z následujících zpráv:</span><span class="sxs-lookup"><span data-stu-id="31e98-103">When you browse to a mapped network drive, you may see one of the following messages:</span></span>
  
- <span data-ttu-id="31e98-104">**\\Cesta není přístupná. Pravděpodobně nemáte oprávnění k použití tohoto síťového prostředku. Obraťte se na správce tohoto serveru a zjistěte, zda máte přístupová oprávnění.**</span><span class="sxs-lookup"><span data-stu-id="31e98-104">**\\Path is not accessible. You might not have permission to use this network resource. Contact the administrator of this server to find out if you have access permissions.**</span></span>

- <span data-ttu-id="31e98-105">**Přístup byl odepřen. Před otevřením souborů v tomto umístění je nutné nejprve přidat web do seznamu důvěryhodných webů, přejít na web a vybrat možnost automatického přihlášení.**</span><span class="sxs-lookup"><span data-stu-id="31e98-105">**Access Denied. Before opening files in this location, you must first add the web site to your trusted site list, browse to the web site, and select the option to login automatically.**</span></span>

<span data-ttu-id="31e98-106">[Nápovědu k řešení potíží s namapokami síťových jednotek](https://docs.microsoft.com/sharepoint/support/administration/troubleshoot-mapped-network-drives).</span><span class="sxs-lookup"><span data-stu-id="31e98-106">[Get help troubleshooting mapped network drives](https://docs.microsoft.com/sharepoint/support/administration/troubleshoot-mapped-network-drives).</span></span>
  
<span data-ttu-id="31e98-107">Mapování knihovny jako síťové jednotky je dočasné a je podporováno pouze v aplikaci Internet Explorer.</span><span class="sxs-lookup"><span data-stu-id="31e98-107">Mapping a library as a network drive is temporary and supported only in Internet Explorer.</span></span> <span data-ttu-id="31e98-108">Místo toho [synchronizujte sharepointové soubory s novým klientem synchronizace OneDrivu,](https://support.office.com/article/6de9ede8-5b6e-4503-80b2-6190f3354a88.aspx) který obsahuje [soubory na vyžádání](https://support.office.com/article/0e6860d3-d9f3-4971-b321-7092438fb38e.aspx).</span><span class="sxs-lookup"><span data-stu-id="31e98-108">Instead, [sync SharePoint files with the new OneDrive sync client](https://support.office.com/article/6de9ede8-5b6e-4503-80b2-6190f3354a88.aspx) which includes [Files On-Demand](https://support.office.com/article/0e6860d3-d9f3-4971-b321-7092438fb38e.aspx).</span></span> <span data-ttu-id="31e98-109">Získejte přístup ke všem souborům na OneDrivu bez použití místního úložného prostoru.</span><span class="sxs-lookup"><span data-stu-id="31e98-109">Access all your files in OneDrive without using local storage space.</span></span>
  