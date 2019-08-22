---
title: Identifikace aktivity pravidla složky Doručená pošta z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 1201a625948743cacfaa58410abeb4108ed2eb56
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539152"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="cc864-102">Identifikace aktivity pravidla složky Doručená pošta z protokolů auditování</span><span class="sxs-lookup"><span data-stu-id="cc864-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="cc864-103">Můžete hledat protokolu auditu v zabezpečení Office 365 & centra kompatibility zobrazení událostí pravidla složky Doručená pošta (vytváření, úprava a odstranění pravidla složky Doručená pošta).</span><span class="sxs-lookup"><span data-stu-id="cc864-103">You can use audit log search in the Office 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="cc864-104">Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="cc864-104">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="cc864-105">Přejít na **vyhledávání** > **auditování protokolu vyhledávací** stránku.</span><span class="sxs-lookup"><span data-stu-id="cc864-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="cc864-106">Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** .</span><span class="sxs-lookup"><span data-stu-id="cc864-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="cc864-107">V rámci **Činnosti poštovní schránky serveru Exchange**, ověřte pole **aktivity** je nastavena na **New-InboxRule vytvořit/upravit/povolit/zakázat pravidla složky Doručená pošta**.</span><span class="sxs-lookup"><span data-stu-id="cc864-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="cc864-108">Klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="cc864-108">Click **Search**.</span></span>

<span data-ttu-id="cc864-109">V seznamu výsledků vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="cc864-109">In the results, select an audit record.</span></span> <span data-ttu-id="cc864-110">V plovoucí panel Podrobnosti klepněte na tlačítko **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="cc864-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="cc864-111">Informace o nastavení pravidel složky Doručená pošta se zobrazí v poli **Parametry** .</span><span class="sxs-lookup"><span data-stu-id="cc864-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="cc864-112">Další informace naleznete v tématu [určení, pokud uživatelem vytvořené pravidlo pro doručenou poštu](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="cc864-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
