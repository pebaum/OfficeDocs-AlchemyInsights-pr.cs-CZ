---
title: Povolení office 365 ATP pro SharePoint, OneDrive a Microsoft Teams
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
ms.openlocfilehash: 564a7f1f6a37e64dbd7d679878ebadbbe35f3fa0
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506911"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="232b7-102">Povolení rozšířené ochrany před internetovými hrozbami Office 365 pro SharePoint Online, OneDrive a Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="232b7-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="232b7-103">Přejděte https://protection.office.com a přihlaste se.</span><span class="sxs-lookup"><span data-stu-id="232b7-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="232b7-104">Zvolte Bezpečné **Threat management**  >  **přílohy zásad**  >  **správy hrozeb**.</span><span class="sxs-lookup"><span data-stu-id="232b7-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="232b7-105">Vyberte **Zapnout ATP pro SharePoint, OneDrive a Microsoft Teams a**klikněte na **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="232b7-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="232b7-106">(Doporučeno) Jako globální správce nebo správce SharePointu Online spusťte rutinu [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrem **DeallowInfectedFileDownload** nastaveným na *hodnotu true*.</span><span class="sxs-lookup"><span data-stu-id="232b7-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="232b7-107">(Doporučeno) [Nastavte výstrahy](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) pro zjištěné soubory.</span><span class="sxs-lookup"><span data-stu-id="232b7-107">(Recommended) [Set up alerts](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="232b7-108">ATP bude nto skenování každý soubor v SharePoint Online, OneDrive nebo Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="232b7-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="232b7-109">Soubory jsou kontrolovány asynchronně, prostřednictvím procesu, který používá sdílení a události aktivity hosta, spolu s inteligentní heuristiky a signály hrozeb k identifikaci škodlivých souborů.</span><span class="sxs-lookup"><span data-stu-id="232b7-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="232b7-110">Viz [OCHRANA ATP pro SharePoint, OneDrive a Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="232b7-110">See [ATP for SharePoint, OneDrive, and Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span></span>