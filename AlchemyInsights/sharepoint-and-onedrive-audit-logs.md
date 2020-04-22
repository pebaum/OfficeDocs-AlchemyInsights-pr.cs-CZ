---
title: Klasické sestavy protokolu auditu sharepointového oddělení
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
ms.openlocfilehash: 3270f1ab03bacb235cbdc3d710053c858f0a5183
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741958"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="e8b35-102">Protokoly auditu SharePointu a OneDrivu</span><span class="sxs-lookup"><span data-stu-id="e8b35-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="e8b35-103">Klasické protokoly auditu sharepointu</span><span class="sxs-lookup"><span data-stu-id="e8b35-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="e8b35-104">Provádění starších auditů SPO bylo migrováno do protokolu jednotného auditu (UAL).</span><span class="sxs-lookup"><span data-stu-id="e8b35-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="e8b35-105">Všechny starší zprávy o auditu SPO budou nyní napájeny prostřednictvím ual a starší signály auditu byly přeneseny na UAL.</span><span class="sxs-lookup"><span data-stu-id="e8b35-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="e8b35-106">Klíčové změny:</span><span class="sxs-lookup"><span data-stu-id="e8b35-106">Key changes:</span></span>

* <span data-ttu-id="e8b35-107">Oříznutí není k dispozici jako schopnost.</span><span class="sxs-lookup"><span data-stu-id="e8b35-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="e8b35-108">Výběr konkrétních událostí k auditu není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="e8b35-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="e8b35-109">Úplný seznam auditovaných událostí, které jsou k dispozici ve výchozím nastavení, naleznete v [tomto dokumentu.](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)</span><span class="sxs-lookup"><span data-stu-id="e8b35-109">Refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="e8b35-110">Možnost **Umístění** v části **Vlastní sestavy** není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="e8b35-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="e8b35-111">Možnost **Otevření nebo stahování dokumentů** není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="e8b35-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="e8b35-112">Konfigurace nastavení auditu pro kolekci webů</span><span class="sxs-lookup"><span data-stu-id="e8b35-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="e8b35-113">Protokoly moderního jednotného auditu SharePointu a OneDrivu s dodržováním předpisů</span><span class="sxs-lookup"><span data-stu-id="e8b35-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="e8b35-114">Zapnutí/vypnutí jednotného protokolování auditu</span><span class="sxs-lookup"><span data-stu-id="e8b35-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="e8b35-115">V SharePointu nebo OneDrivu není potřeba žádná další konfigurace.</span><span class="sxs-lookup"><span data-stu-id="e8b35-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="e8b35-116">Pomocí hledání protokolování auditu zkontrolujte aktivitu souborů, oprávnění složek, uživatelů:</span><span class="sxs-lookup"><span data-stu-id="e8b35-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="e8b35-117">Aktivity souborů a stránek</span><span class="sxs-lookup"><span data-stu-id="e8b35-117">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="e8b35-118">Aktivity složek</span><span class="sxs-lookup"><span data-stu-id="e8b35-118">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="e8b35-119">Sdílení a přístup k aktivitám žádostí</span><span class="sxs-lookup"><span data-stu-id="e8b35-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="e8b35-120">Synchronizační aktivity</span><span class="sxs-lookup"><span data-stu-id="e8b35-120">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="e8b35-121">Aktivity správy lokality</span><span class="sxs-lookup"><span data-stu-id="e8b35-121">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="e8b35-122">Další informace o tom, jak načíst tyto události, naleznete [v tématu Hledání protokolu auditu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="e8b35-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
