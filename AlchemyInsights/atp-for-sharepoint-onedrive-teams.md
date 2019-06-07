---
title: ATP pro SharePoint, OneDrive a týmy společnosti Microsoft
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: b304f6c7d9959e49a8152c03f11c6c864a154ea5
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34764926"
---
# <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="23f8c-102">ATP pro SharePoint, OneDrive a týmy společnosti Microsoft</span><span class="sxs-lookup"><span data-stu-id="23f8c-102">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="23f8c-103">Postupujte takto Chcete-li povolit rozšířené ochranu před hrozbami:</span><span class="sxs-lookup"><span data-stu-id="23f8c-103">Follow these steps to enable Advanced Threat Protection:</span></span>

1. <span data-ttu-id="23f8c-104">Přejít na [https://protection.office.com](https://protection.office.com) a přihlaste se pod účtem globálního správce nebo správce účtů zabezpečení.</span><span class="sxs-lookup"><span data-stu-id="23f8c-104">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

2. <span data-ttu-id="23f8c-105">V levém navigačním podokně v části **Správa ohrožení**, vyberte **zásad** \> **Bezpečné přílohy**.</span><span class="sxs-lookup"><span data-stu-id="23f8c-105">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Attachments**.</span></span>

3. <span data-ttu-id="23f8c-106">Vyberte **Zapnout ATP pro SharePoint, OneDrive a týmy společnosti Microsoft**.</span><span class="sxs-lookup"><span data-stu-id="23f8c-106">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**.</span></span>

4. <span data-ttu-id="23f8c-107">[Vytvoření zásady činnosti výstrahy](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts) přijímat upozornění při můžeme rozpoznat škodlivé soubory.</span><span class="sxs-lookup"><span data-stu-id="23f8c-107">[Create an activity alert policy](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts) to receive notifications when we detect malicious files.</span></span>

<span data-ttu-id="23f8c-108">Úplné pokyny najdete v tomto [tématu](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="23f8c-108">For complete instructions, see this [topic](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams).</span></span>

<span data-ttu-id="23f8c-109">**Poznámka**: podle návrhu, ATP neprohlíží každý soubor v SharePoint Online, OneDrive pro obchodní nebo Teams společnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="23f8c-109">**Note**: By design, ATP doesn't scan every single file in SharePoint Online, OneDrive for Business, or Microsoft Teams.</span></span> <span data-ttu-id="23f8c-110">Soubory jsou prohledávány asynchronně pomocí procesu, který používá sdílení aktivity, aktivita hosta, a signalizuje ohrožení identifikovat škodlivé soubory.</span><span class="sxs-lookup"><span data-stu-id="23f8c-110">Files are scanned asynchronously by a process that uses sharing activity, guest activity, and threat signals to identify malicious files.</span></span> <span data-ttu-id="23f8c-111">Další informace najdete v tomto [tématu](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="23f8c-111">For more information, see this [topic](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>
