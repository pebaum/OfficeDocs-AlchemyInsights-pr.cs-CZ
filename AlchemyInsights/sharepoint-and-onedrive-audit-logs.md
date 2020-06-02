---
title: Klasické sestavy protokolu auditu služby SharePoint
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 0aedb549f11db54d3cd480671fb0767c60680ad3
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44509593"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="c3080-102">Protokoly auditu SharePointu a OneDrivu</span><span class="sxs-lookup"><span data-stu-id="c3080-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="c3080-103">Klasické protokoly auditu sharepointu</span><span class="sxs-lookup"><span data-stu-id="c3080-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="c3080-104">Starší auditování SPO bylo migrováno do jednotného protokolu auditu (UAL).</span><span class="sxs-lookup"><span data-stu-id="c3080-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="c3080-105">Všechny starší zprávy o auditu SPO budou nyní napájeny přes UAL a starší signály auditu byly migrovány do UAL.</span><span class="sxs-lookup"><span data-stu-id="c3080-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="c3080-106">Klíčové změny:</span><span class="sxs-lookup"><span data-stu-id="c3080-106">Key changes:</span></span>

* <span data-ttu-id="c3080-107">Ořezávání není k dispozici jako funkce.</span><span class="sxs-lookup"><span data-stu-id="c3080-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="c3080-108">Výběr konkrétních událostí k auditování není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="c3080-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="c3080-109">Úplný seznam auditovaných událostí, které jsou ve výchozím nastavení k dispozici, naleznete v [tomto dokumentu.](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)</span><span class="sxs-lookup"><span data-stu-id="c3080-109">Refer to [this document](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="c3080-110">Možnost **Umístění** v části **Přizpůsobené sestavy** NENÍ k dispozici.</span><span class="sxs-lookup"><span data-stu-id="c3080-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="c3080-111">Možnost **Otevření nebo stažení událostí dokumentů** není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="c3080-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="c3080-112">Konfigurace nastavení auditu pro kolekci webů</span><span class="sxs-lookup"><span data-stu-id="c3080-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="c3080-113">Protokoly sharepointového a onedriveového moderního jednotného auditu z dodržování předpisů</span><span class="sxs-lookup"><span data-stu-id="c3080-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="c3080-114">Zapnutí nebo vypnutí jednotného protokolování auditu</span><span class="sxs-lookup"><span data-stu-id="c3080-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="c3080-115">V SharePointu nebo OneDrivu se nevyžaduje žádná další konfigurace.</span><span class="sxs-lookup"><span data-stu-id="c3080-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="c3080-116">Pomocí vyhledávání protokolování auditu zkontrolujte aktivitu souborů, složek, uživatelů, oprávnění:</span><span class="sxs-lookup"><span data-stu-id="c3080-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="c3080-117">Aktivity souborů a stránek</span><span class="sxs-lookup"><span data-stu-id="c3080-117">File and page activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="c3080-118">Aktivity složek</span><span class="sxs-lookup"><span data-stu-id="c3080-118">Folder activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="c3080-119">Aktivity pro sdílení a přístup k žádosti</span><span class="sxs-lookup"><span data-stu-id="c3080-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="c3080-120">Aktivity synchronizace</span><span class="sxs-lookup"><span data-stu-id="c3080-120">Synchronization activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="c3080-121">Činnosti správy webu</span><span class="sxs-lookup"><span data-stu-id="c3080-121">Site administration activities</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="c3080-122">Další informace o načtení těchto událostí naleznete [v tématu Hledání v protokolu auditu](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="c3080-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
