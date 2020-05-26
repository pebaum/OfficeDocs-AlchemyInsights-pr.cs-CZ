---
title: Blokovat stahování odkazů na sdílení
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000213"
- "5715"
ms.openlocfilehash: 8cb53754125cedf4a3d0426d6c3bf70297eb3d74
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/23/2020
ms.locfileid: "44357449"
---
# <a name="block-download-on-sharing-links"></a><span data-ttu-id="a0252-102">Blokovat stahování odkazů na sdílení</span><span class="sxs-lookup"><span data-stu-id="a0252-102">Block download on sharing links</span></span>

<span data-ttu-id="a0252-103">**Blokové stahování** je k dispozici pro **odkazy pouze** na dokumenty Office.</span><span class="sxs-lookup"><span data-stu-id="a0252-103">**Block download** is available for **view-only links** to Office documents.</span></span> <span data-ttu-id="a0252-104">Vyberete-li tuto možnost, neuvidí uživatelé, kteří získají přístup k souboru prostřednictvím vytvořeného odkazu, možnosti stažení, tisku nebo kopírování souboru.</span><span class="sxs-lookup"><span data-stu-id="a0252-104">When you select this option, people who gain access to the file via the link you created will not see options to download, print, or copy the file.</span></span>

<span data-ttu-id="a0252-105">Správci mohou určit, zda se nastavení "block download" zobrazí pouze pro soubory Sady Office nebo ne změnou `BlockDownloadLinksFileType` nastavení v rutinách [set-spotenantnebo](https://docs.microsoft.com/powershell/module/sharepoint-online/set-spotenant?view=sharepoint-ps) [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) PowerShell.</span><span class="sxs-lookup"><span data-stu-id="a0252-105">Administrators can control whether the "block download" setting appears only for Office files or not by changing the `BlockDownloadLinksFileType` setting in the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/set-spotenant?view=sharepoint-ps) or [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) PowerShell cmdlets.</span></span>
