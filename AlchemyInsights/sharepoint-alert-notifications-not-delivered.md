---
title: Oznámení s výstrahami SharePointu, která nebyla doručena
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: a422805d11a128909e1be7bf5d08b24efc132e23
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742040"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="5a83e-102">Oznámení s výstrahami SharePointu, která nebyla doručena</span><span class="sxs-lookup"><span data-stu-id="5a83e-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="5a83e-103">Zkontrolujte složku JUNK ve svém e-mailu, protože někdy mohou být výstrahy tam.</span><span class="sxs-lookup"><span data-stu-id="5a83e-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="5a83e-104">Zjistěte, zda **nejsou doručeny všechny výstrahy** nebo zda není **doručena jednotlivá výstraha** z určitého souboru nebo knihovny.</span><span class="sxs-lookup"><span data-stu-id="5a83e-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="5a83e-105">**Jednotlivé výstrahy se nedoručují**: Pokud není doručena jednotlivá výstraha z určitého souboru nebo knihovny, můžete se pokusit ji odstranit a znovu vytvořit.</span><span class="sxs-lookup"><span data-stu-id="5a83e-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="5a83e-106">Viz [Správa, zobrazení nebo odstranění sharepointových výstrah](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) a opětovné vytvoření výstrahy.</span><span class="sxs-lookup"><span data-stu-id="5a83e-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>
- <span data-ttu-id="5a83e-107">**Všechny výstrahy nejsou doručeny**: Pokud nejsou doručeny všechny výstrahy z více souborů nebo knihoven, navštivte [řídicí panel Stav služby](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) a zkontrolujte, zda se u SharePointu nebo Exchange nevyskytují informační zpravodaje nebo incidenty.</span><span class="sxs-lookup"><span data-stu-id="5a83e-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="5a83e-108">Problém může být s funkcí upozornění SharePoint nebo zpoždění v e-mailech prostřednictvím serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="5a83e-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="5a83e-109">Bude také důležité si uvědomit, zda jsou doručovány další e-maily, a pokud ne, problém je pravděpodobně se zpožděním serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="5a83e-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="5a83e-110">Nejčastější dotazy týkající se výstrah:</span><span class="sxs-lookup"><span data-stu-id="5a83e-110">FAQ on alerts:</span></span>

- <span data-ttu-id="5a83e-111">Není možné odesílat výstrahy do distribuční skupiny, jsou podporovány pouze skupiny Zabezpečení a O365.</span><span class="sxs-lookup"><span data-stu-id="5a83e-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="5a83e-112">Šablony e-mailů s výstrahami nelze přizpůsobit. k jejich dosažení je třeba použít pracovní postup Microsoft FLOW nebo SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="5a83e-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

<span data-ttu-id="5a83e-113">Více informací:</span><span class="sxs-lookup"><span data-stu-id="5a83e-113">More Information:</span></span>

- <span data-ttu-id="5a83e-114">**Nastavení výstrah**: Další informace o nastavení výstrah najdete [v tématu Vytvoření výstrahy, která bude upozorněna na změny souboru nebo složky v SharePointu](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span><span class="sxs-lookup"><span data-stu-id="5a83e-114">**Alert setup**: For more information about setting up alerts, see [Create an alert to get notified when a file or folder changes in SharePoint](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span></span>
- <span data-ttu-id="5a83e-115">**Poradce při potížích s výstrahami**: Další informace o upozorněních na řešení potíží najdete [v tématu Uživatelé nedostávají oznámení o výstražných upozorněních SharePointu Online](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications).</span><span class="sxs-lookup"><span data-stu-id="5a83e-115">**Troubleshoot alerts**: For more information about troubleshooting alerts, see [Users don't receive SharePoint Online alert notifications](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications).</span></span>
- <span data-ttu-id="5a83e-116">**Pokročilé zásady upozornění na dodržování předpisů O365**: Další informace o nastavení těchto výstrah naleznete v [tématu Zásady upozornění na dodržování předpisů](https://docs.microsoft.com/office365/securitycompliance/alert-policies).</span><span class="sxs-lookup"><span data-stu-id="5a83e-116">**Advanced O365 Compliance Alert Policies**: For more information about setting up these alerts, see [Compliance Alert Policies](https://docs.microsoft.com/office365/securitycompliance/alert-policies).</span></span>
- <span data-ttu-id="5a83e-117">**Protokoly auditu Služby SharePoint a OneDrive**: Další informace o tom, jak tyto události načíst, najdete [v tématu Hledání v protokolu auditu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="5a83e-117">**SharePoint and OneDrive Audit Logs**: For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
- <span data-ttu-id="5a83e-118">**Výstrahy odeslané pokročilou ochranou před internetovými hrozbami**: Viz [ochrana ATP pro SharePoint a OneDrive](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="5a83e-118">**Alerts sent by Advanced Threat Protection**: See [ATP for SharePoint and OneDrive](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>
- <span data-ttu-id="5a83e-119">**Upozornění odeslaná zásadami prevence ztráty dat**: Viz [E-mailová oznámení pro zásady ochrany před únikem dat](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span><span class="sxs-lookup"><span data-stu-id="5a83e-119">**Alerts sent by Data Loss Prevention polices**: See [Email notifications for DLP policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

## <a name="related-topics"></a><span data-ttu-id="5a83e-120">Příbuzná témata</span><span class="sxs-lookup"><span data-stu-id="5a83e-120">Related Topics</span></span>

<span data-ttu-id="5a83e-121">Chcete vyzkoušet Microsoft Flow na SharePointu Online?</span><span class="sxs-lookup"><span data-stu-id="5a83e-121">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="5a83e-122">Vytvořit tok</span><span class="sxs-lookup"><span data-stu-id="5a83e-122">Create Flow</span></span>](https://support.office.com/article/a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="5a83e-123">SharePoint a tok</span><span class="sxs-lookup"><span data-stu-id="5a83e-123">SharePoint and Flow</span></span>](https://flow.microsoft.com//blog/sharepoint-and-flow/)
