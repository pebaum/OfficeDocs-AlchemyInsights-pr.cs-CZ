---
title: Identifikace aktivity pravidel doručené pošty v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: f946510539b3d28f2ceeec1546cbffce8bd352fd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716417"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="9bb5a-102">Identifikace aktivity pravidel doručené pošty v protokolech auditu</span><span class="sxs-lookup"><span data-stu-id="9bb5a-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="9bb5a-103">Pomocí hledání protokolu auditu v Centru dodržování předpisů microsoft 365 Security & Compliance Center můžete zobrazit události pravidel doručené pošty (vytváření, úpravy a odstranění pravidel doručené pošty).</span><span class="sxs-lookup"><span data-stu-id="9bb5a-103">You can use audit log search in the Microsoft 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="9bb5a-104">Přihlaste se k [Centru dodržování předpisů pro zabezpečení & microsoft 365](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="9bb5a-104">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="9bb5a-105">Přejděte na stránku**hledání protokolu auditování** **vyhledávání.** > </span><span class="sxs-lookup"><span data-stu-id="9bb5a-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="9bb5a-106">Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum.**</span><span class="sxs-lookup"><span data-stu-id="9bb5a-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="9bb5a-107">V části **Aktivity poštovní schránky serveru Exchange**ověřte, zda je pole **Aktivity** nastaveno na **pravidlo vytvoření/úpravy/povolit/zakázání pole Vytvoření/změna/povolit/zakázání doručené pošty**.</span><span class="sxs-lookup"><span data-stu-id="9bb5a-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="9bb5a-108">Klepněte na **tlačítko Hledat**.</span><span class="sxs-lookup"><span data-stu-id="9bb5a-108">Click **Search**.</span></span>

<span data-ttu-id="9bb5a-109">Ve výsledcích vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="9bb5a-109">In the results, select an audit record.</span></span> <span data-ttu-id="9bb5a-110">V informačním rámečku podrobnosti klikněte na **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="9bb5a-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="9bb5a-111">Informace o nastavení pravidla doručené pošty se zobrazí v poli **Parametry.**</span><span class="sxs-lookup"><span data-stu-id="9bb5a-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="9bb5a-112">Další informace naleznete v [tématu Určení, zda uživatel vytvořil pravidlo doručené pošty](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="9bb5a-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
