---
title: Povolení služby SharePoint, OneDrive a týmy společnosti Microsoft Office 365 ATP
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: ae2f574663ae3233a056589c2d5a578171f3b2f4
ms.sourcegitcommit: 601aec31e6556286fe5e0fd62827a037cbb6fe17
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/02/2019
ms.locfileid: "31030918"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="0525b-102">Povolit ochranu Office 365 rozšířené hrozbu pro SharePoint Online, OneDrive a týmy společnosti Microsoft</span><span class="sxs-lookup"><span data-stu-id="0525b-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="0525b-103">Přejít na https://protection.office.com a přihlaste se.</span><span class="sxs-lookup"><span data-stu-id="0525b-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="0525b-104">Zvolte **Threat management** > **zásad** > **Bezpečné přílohy**.</span><span class="sxs-lookup"><span data-stu-id="0525b-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="0525b-105">Vyberte možnost **Zapnout ATP pro SharePoint, OneDrive a týmy společnosti Microsoft**a klepněte na tlačítko **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="0525b-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="0525b-106">(Doporučeno) Jako globální správce nebo správce služby SharePoint Online spusťte rutinu [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrem **DisallowInfectedFileDownload** nastavena na *hodnotu true*.</span><span class="sxs-lookup"><span data-stu-id="0525b-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="0525b-107">(Doporučeno) Zjištěné soubory [Nastavení výstrah](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) .</span><span class="sxs-lookup"><span data-stu-id="0525b-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="0525b-108">ATP se nChcete-li prohledat každý soubor v SharePoint Online, OneDrive nebo Teams společnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="0525b-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="0525b-109">Soubory jsou prohledávány asynchronně pomocí procesu, který používá sdílení a Host události aktivity inteligentní heuristiky a signály ohrožení identifikovat škodlivé soubory.</span><span class="sxs-lookup"><span data-stu-id="0525b-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="0525b-110">Další informace najdete v článku [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="0525b-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>