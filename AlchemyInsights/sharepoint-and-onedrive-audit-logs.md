---
title: Klasické sestavy protokolu auditování služby SharePoint
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: be95034bea3c58a4fde96cfb0f9ba525e810758e
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/05/2019
ms.locfileid: "37992611"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="6ffde-102">Protokoly auditu služby SharePoint a OneDrive</span><span class="sxs-lookup"><span data-stu-id="6ffde-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="6ffde-103">Klasické protokoly auditu služby SharePoint</span><span class="sxs-lookup"><span data-stu-id="6ffde-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="6ffde-104">Starší verze auditu SPO byla přenesena do protokolu jednotného auditu (UAL).</span><span class="sxs-lookup"><span data-stu-id="6ffde-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="6ffde-105">Všechny starší verze zpráv o auditu SPO budou nyní napájeny prostřednictvím UAL a starší signály auditu byly migrovány do UAL.</span><span class="sxs-lookup"><span data-stu-id="6ffde-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="6ffde-106">Klíčové změny:</span><span class="sxs-lookup"><span data-stu-id="6ffde-106">Key changes:</span></span>

* <span data-ttu-id="6ffde-107">Oříznutí není dostupné jako možnost.</span><span class="sxs-lookup"><span data-stu-id="6ffde-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="6ffde-108">Výběr konkrétních událostí k auditování není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="6ffde-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="6ffde-109">Úplný seznam auditovaných událostí, které jsou ve výchozím nastavení k dispozici, naleznete v [tomto dokumentu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) .</span><span class="sxs-lookup"><span data-stu-id="6ffde-109">Refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="6ffde-110">Možnost **umístění** ve **vlastních sestavách** není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="6ffde-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="6ffde-111">Možnosti **otevírání nebo stahování dokumentů** nejsou k dispozici.</span><span class="sxs-lookup"><span data-stu-id="6ffde-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="6ffde-112">Konfigurace nastavení auditu pro kolekci webů</span><span class="sxs-lookup"><span data-stu-id="6ffde-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="6ffde-113">Služby SharePoint a OneDrive moderní sjednocené záznamy auditu z souladu</span><span class="sxs-lookup"><span data-stu-id="6ffde-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="6ffde-114">Zapnutí a vypnutí protokolování pro sjednocený audit</span><span class="sxs-lookup"><span data-stu-id="6ffde-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="6ffde-115">V rámci služby SharePoint nebo OneDrive není vyžadována žádná další konfigurace.</span><span class="sxs-lookup"><span data-stu-id="6ffde-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="6ffde-116">Pomocí vyhledávání protokolování auditu Zkontrolujte činnost souborů, složek, uživatelů, oprávnění:</span><span class="sxs-lookup"><span data-stu-id="6ffde-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="6ffde-117">Aktivity souborů a stránek</span><span class="sxs-lookup"><span data-stu-id="6ffde-117">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="6ffde-118">Aktivity složek</span><span class="sxs-lookup"><span data-stu-id="6ffde-118">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="6ffde-119">Aktivity související se sdílením a přístupem</span><span class="sxs-lookup"><span data-stu-id="6ffde-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="6ffde-120">Synchronizační aktivity</span><span class="sxs-lookup"><span data-stu-id="6ffde-120">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="6ffde-121">Činnosti správy webu</span><span class="sxs-lookup"><span data-stu-id="6ffde-121">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="6ffde-122">Další informace o tom, jak tyto události načíst, naleznete v tématu [hledání v protokolu auditování](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="6ffde-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
