---
title: Povolení služby Atp Office 365 pro SharePoint, OneDrive a Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: fdfdc97a198898051a3388672d01994d96dd5e97
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703419"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="1f12d-102">Povolení rozšířené ochrany před hrozbami Pro SharePoint Online, OneDrive a Microsoft Teams v Office 365</span><span class="sxs-lookup"><span data-stu-id="1f12d-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="1f12d-103">Jděte https://protection.office.com a přihlaste se.</span><span class="sxs-lookup"><span data-stu-id="1f12d-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="1f12d-104">Zvolte**Bezpečné přílohy**pro > **správu** >  **hrozeb**.</span><span class="sxs-lookup"><span data-stu-id="1f12d-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="1f12d-105">Vyberte **Zapnout ATP pro SharePoint, OneDrive a Microsoft Teams**a klikněte na **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="1f12d-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="1f12d-106">(Doporučeno) Jako globální správce nebo správce SharePointu Online spusťte rutinu [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrem **DisallowInfectedFileDownload** nastaveným na *hodnotu true*.</span><span class="sxs-lookup"><span data-stu-id="1f12d-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="1f12d-107">(Doporučeno) [Nastavte výstrahy](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) pro zjištěné soubory.</span><span class="sxs-lookup"><span data-stu-id="1f12d-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="1f12d-108">Atp prohledá každý jednotlivý soubor v SharePointu Online, OneDrivu nebo Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="1f12d-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="1f12d-109">Soubory jsou kontrolovány asynchronně, prostřednictvím procesu, který používá sdílení a události aktivity hosta, spolu s inteligentní heuristiky a signály hrozeb k identifikaci škodlivých souborů.</span><span class="sxs-lookup"><span data-stu-id="1f12d-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="1f12d-110">Další informace najdete v článku [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="1f12d-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>