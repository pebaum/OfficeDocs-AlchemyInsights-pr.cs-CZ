---
title: Odstraňování problémů s výkonem OneDrive
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1977"
- "9000343"
ms.openlocfilehash: 222f818c3fd78a19b9952d4703755498bc080910
ms.sourcegitcommit: 8864b5789d9905916039081b53530c7e6d8bc529
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/10/2019
ms.locfileid: "36822191"
---
# <a name="troubleshoot-onedrive-performance"></a><span data-ttu-id="acab3-102">Odstraňování problémů s výkonem OneDrive</span><span class="sxs-lookup"><span data-stu-id="acab3-102">Troubleshoot OneDrive performance</span></span>

<span data-ttu-id="acab3-103">Pokud u funkce OneDrive dochází k pomalejší synchronizaci nebo k podobným problémům s výkonem:</span><span class="sxs-lookup"><span data-stu-id="acab3-103">If you’re experiencing a slower than expected sync, or similar performance issues with OneDrive:</span></span>

- <span data-ttu-id="acab3-104">Potvrďte, že v [řídicím panelu stavu služby](https://portal.office.com/adminportal/home?ref=/servicehealth)nejsou známy žádné problémy.</span><span class="sxs-lookup"><span data-stu-id="acab3-104">Confirm there are no known issues using the [Service Health Dashboard](https://portal.office.com/adminportal/home?ref=/servicehealth).</span></span>

- <span data-ttu-id="acab3-105">[Povolit soubory na požádání](https://support.office.com/article/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e?ui=en-US&rs=en-US&ad=US) , abyste mohli přistupovat ke všem souborům v aplikaci OneDrive, aniž byste museli stahovat všechny soubory a používat úložný prostor v zařízení.</span><span class="sxs-lookup"><span data-stu-id="acab3-105">[Enable Files On Demand](https://support.office.com/article/save-disk-space-with-onedrive-files-on-demand-for-windows-10-0e6860d3-d9f3-4971-b321-7092438fb38e?ui=en-US&rs=en-US&ad=US) so that you can access all your files in OneDrive without having to download all of them and use storage space on your device.</span></span>

- <span data-ttu-id="acab3-106">[Seznamte se s osvědčenými postupy](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance) pro plánování a výkon sítě.</span><span class="sxs-lookup"><span data-stu-id="acab3-106">[Review best practices](https://docs.microsoft.com/office365/enterprise/network-planning-and-performance) for network planning and performance.</span></span>

- <span data-ttu-id="acab3-107">[Maximalizovat rychlost odesílání a stahování](https://support.office.com/article/maximize-upload-and-download-speed-8eeadfb8-501f-406d-997b-98ab6ff67f43), zejména pokud synchronizujete zařízení poprvé.</span><span class="sxs-lookup"><span data-stu-id="acab3-107">[Maximize upload and download speed](https://support.office.com/article/maximize-upload-and-download-speed-8eeadfb8-501f-406d-997b-98ab6ff67f43), especially if you’re syncing a device for the first time.</span></span>

- <span data-ttu-id="acab3-108">Pokud synchronizujete knihovnu s více než 100 000 položkami, synchronizace OneDrive se může jevit dlouhou dobu, nebo se zobrazí stav zpracování 0KB xMB.</span><span class="sxs-lookup"><span data-stu-id="acab3-108">If you’re syncing a library with more than 100,000 items, OneDrive sync may seem stuck for a long time, or the status shows Processing 0KB of xMB."</span></span> <span data-ttu-id="acab3-109">Další [informace o synchronizaci více než 100 000 souborů](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa) a také [podporovaného limitu 300 000 souborů OneDrive](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa)</span><span class="sxs-lookup"><span data-stu-id="acab3-109">[Learn more about syncing more than 100,000 files](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa) as well as [OneDrive’s supported limit of 300,000 files](https://support.office.com/article/invalid-file-names-and-file-types-in-onedrive-onedrive-for-business-and-sharepoint-64883a5d-228e-48f5-b3d2-eb39e07630fa).</span></span>

- <span data-ttu-id="acab3-110">Pokud uživatel překročí omezení použití, omezí služba SharePoint Online Další požadavky tohoto uživatelského účtu na krátkou dobu.</span><span class="sxs-lookup"><span data-stu-id="acab3-110">When a user exceeds usage limits, SharePoint Online throttles any further requests from that user account for a short period.</span></span> <span data-ttu-id="acab3-111">Všechny uživatelské akce jsou při platnosti akcelerátoru omezené.</span><span class="sxs-lookup"><span data-stu-id="acab3-111">All user actions are throttled while the throttle is in effect.</span></span>
