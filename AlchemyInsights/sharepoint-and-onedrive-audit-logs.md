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
ms.openlocfilehash: af5b3c76b82db13bc89c917247e41fa1d8779b68
ms.sourcegitcommit: d5bf97a0bf0547f36b6da9684ce9f16a13a7749e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068016"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="81cff-102">Protokoly auditu služby SharePoint a OneDrive</span><span class="sxs-lookup"><span data-stu-id="81cff-102">SharePoint and OneDrive audit logs</span></span>

<span data-ttu-id="81cff-103">**Služby SharePoint a OneDrive moderní sjednocené záznamy auditu z souladu**</span><span class="sxs-lookup"><span data-stu-id="81cff-103">**SharePoint and OneDrive Modern Unified Audit logs from compliance**</span></span>

- [<span data-ttu-id="81cff-104">Zapnutí a vypnutí protokolování pro sjednocený audit</span><span class="sxs-lookup"><span data-stu-id="81cff-104">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="81cff-105">V rámci služby SharePoint nebo OneDrive není vyžadována žádná další konfigurace.</span><span class="sxs-lookup"><span data-stu-id="81cff-105">No additional configuration is required within SharePoint or OneDrive.</span></span>

- <span data-ttu-id="81cff-106">Pomocí vyhledávání protokolování auditu Zkontrolujte činnost souborů, složek, uživatelů, oprávnění:</span><span class="sxs-lookup"><span data-stu-id="81cff-106">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

    - [<span data-ttu-id="81cff-107">Aktivity souborů a stránek</span><span class="sxs-lookup"><span data-stu-id="81cff-107">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
    - [<span data-ttu-id="81cff-108">Aktivity složek</span><span class="sxs-lookup"><span data-stu-id="81cff-108">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
    - [<span data-ttu-id="81cff-109">Aktivity související se sdílením a přístupem</span><span class="sxs-lookup"><span data-stu-id="81cff-109">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
    - [<span data-ttu-id="81cff-110">Synchronizační aktivity</span><span class="sxs-lookup"><span data-stu-id="81cff-110">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
    - [<span data-ttu-id="81cff-111">Činnosti správy webu</span><span class="sxs-lookup"><span data-stu-id="81cff-111">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)
- <span data-ttu-id="81cff-112">Další informace o tom, jak tyto události načíst, naleznete v tématu [hledání v protokolu auditování](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="81cff-112">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>

<span data-ttu-id="81cff-113">**Klasické protokoly auditu služby SharePoint**</span><span class="sxs-lookup"><span data-stu-id="81cff-113">**SharePoint classic Audit logs**</span></span>

<span data-ttu-id="81cff-114">Migrovali jsme starší verze auditování SPO do protokolu Unified auditovací protokol (UAL).</span><span class="sxs-lookup"><span data-stu-id="81cff-114">We migrated SPO legacy auditing to Unified Audit Log (UAL).</span></span> <span data-ttu-id="81cff-115">To v podstatě znamená, že všechny starší zprávy o auditu SPO budou nyní napájeny prostřednictvím UAL a starší signály auditu byly migrovány do UAL.</span><span class="sxs-lookup"><span data-stu-id="81cff-115">This essentially means that all SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="81cff-116">Klíčové změny:</span><span class="sxs-lookup"><span data-stu-id="81cff-116">Key changes:</span></span>

- <span data-ttu-id="81cff-117">Oříznutí jako funkce není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="81cff-117">Trimming as a capability is NOT available.</span></span>
- <span data-ttu-id="81cff-118">Oddíl, ve kterém vyberete konkrétní události k auditování, není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="81cff-118">The section where you choose specific events to audit is NOT available.</span></span> <span data-ttu-id="81cff-119">Úplný seznam auditovaných událostí, které jsou ve výchozím nastavení k dispozici, naleznete v [tomto dokumentu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) .</span><span class="sxs-lookup"><span data-stu-id="81cff-119">Please refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
- <span data-ttu-id="81cff-120">Možnost umístění ve **vlastních SESTAVÁCH** není k dispozici.</span><span class="sxs-lookup"><span data-stu-id="81cff-120">The "Location" option under **Customized reports** is NOT available.</span></span> 
- <span data-ttu-id="81cff-121">Události otevírání nebo stahování dokumentů nejsou k dispozici.</span><span class="sxs-lookup"><span data-stu-id="81cff-121">“Opening or downloading documents” events is NOT available.</span></span> 

