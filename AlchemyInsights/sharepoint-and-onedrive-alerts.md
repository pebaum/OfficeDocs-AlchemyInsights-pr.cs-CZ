---
title: Nepřijímají se výstrahy služby SharePoint a OneDrive
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/25/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 80423791ad558fc414d50608c73f823036432e14
ms.sourcegitcommit: 5e6a805fb0b41d714ca1cf90e23b8e2daa90f90e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/26/2019
ms.locfileid: "37205511"
---
# <a name="not-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="46be9-102">Nepřijímají se výstrahy služby SharePoint a OneDrive</span><span class="sxs-lookup"><span data-stu-id="46be9-102">Not receiving SharePoint and OneDrive alerts</span></span>

<span data-ttu-id="46be9-103">Nejprve zkontrolujte e-mailovou složku Nevyžádaná pošta nebo spam.</span><span class="sxs-lookup"><span data-stu-id="46be9-103">First check the Junk or Spam folder in your email.</span></span>

<span data-ttu-id="46be9-104">Potom zjistěte, zda nejsou **doručeny všechny výstrahy** nebo zda není doručena **jednotlivá výstraha** z určitého souboru nebo knihovny.</span><span class="sxs-lookup"><span data-stu-id="46be9-104">Then determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="46be9-105">Nejsou-li **doručena všechna oznámení z více souborů nebo knihoven**, navštivte [řídicí panel stavu služby](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) a zkontrolujte, zda nedochází k jakýmkoli událostem nebo incidentům, ke kterým může dojít ve službě SharePoint nebo Exchange.</span><span class="sxs-lookup"><span data-stu-id="46be9-105">If **all alerts from multiple files or libraries are not delivered**, visit the [Service Health dashboard](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fadmin.microsoft.com%2FAdminPortal%2FHome%23%2Fservicehealth&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=35FUOTleK0Sc0z%2B7N7Vm0tOgXplyeOe3LcIzqRziGXc%3D&reserved=0) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="46be9-106">Problém může být s výstrahou služby SharePoint nebo prodlevám v e-mailech prostřednictvím serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="46be9-106">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="46be9-107">Všimněte si také, zda jsou doručovány další e-maily, a pokud ne, problém je pravděpodobně zpožděna Exchange.</span><span class="sxs-lookup"><span data-stu-id="46be9-107">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="46be9-108">Pokud není **doručena jednotlivá výstraha z určitého souboru nebo knihovny**, pokuste se jej odstranit a znovu vytvořit.</span><span class="sxs-lookup"><span data-stu-id="46be9-108">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="46be9-109">Chcete-li výstrahu znovu vytvořit [, viz Správa, zobrazení nebo odstranění výstrah služby SharePoint](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) .</span><span class="sxs-lookup"><span data-stu-id="46be9-109">See [Manage, view, or delete SharePoint alerts](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsupport.office.com%2Farticle%2Fmanage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2%3Fui%3Den-US%26rs%3D%26ad%3DUS%23ID0EAADAAA%3DOnline&data=02%7C01%7Cv-todmc%40microsoft.com%7C2cd2037aa7304711d2bc08d741fae254%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C637050418099632638&sdata=AkE%2BjiG6%2BA59llp2DGcg4uHHUjaUDUnAlK5ax%2Fepn3E%3D&reserved=0) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="46be9-110">Oznámení nelze odeslat do distribuční skupiny.</span><span class="sxs-lookup"><span data-stu-id="46be9-110">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="46be9-111">Jsou podporovány pouze skupiny zabezpečení a O365.</span><span class="sxs-lookup"><span data-stu-id="46be9-111">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="46be9-112">Šablony e-mailů výstrah nelze přizpůsobit.</span><span class="sxs-lookup"><span data-stu-id="46be9-112">You cannot customize alert email templates.</span></span> <span data-ttu-id="46be9-113">K dosažení těchto cílů je nutné použít program Microsoft Flow nebo pracovní postup aplikace SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="46be9-113">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
