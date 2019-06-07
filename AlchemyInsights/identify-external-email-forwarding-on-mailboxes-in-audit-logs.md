---
title: Identifikovat externí e-mailu předávání poštovních schránek z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1369
ms.assetid: ''
ms.openlocfilehash: 518e4dd485ee7c54ce83e65794152e32f4c3a836
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34751991"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="d4231-102">Identifikovat při konfiguraci externí e-mailu předávání poštovních schránek</span><span class="sxs-lookup"><span data-stu-id="d4231-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="d4231-103">Když uživatel konfiguruje externí e-mailu předávání poštovní schránky, je jako část rutiny **Set-Mailbox** auditované činnosti.</span><span class="sxs-lookup"><span data-stu-id="d4231-103">When a user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="d4231-104">Můžete zobrazit aktivitu pomocí vyhledávání protokolu auditování zabezpečení & centra kompatibility.</span><span class="sxs-lookup"><span data-stu-id="d4231-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="d4231-105">Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="d4231-105">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="d4231-106">Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.</span><span class="sxs-lookup"><span data-stu-id="d4231-106">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="d4231-107">Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** .</span><span class="sxs-lookup"><span data-stu-id="d4231-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="d4231-108">Není třeba zadat uživatelské jméno.</span><span class="sxs-lookup"><span data-stu-id="d4231-108">You don't need to specify a username.</span></span> <span data-ttu-id="d4231-109">Ověřte, zda že pole **aktivity** je nastavena na **Zobrazit výsledky pro všechny aktivity**.</span><span class="sxs-lookup"><span data-stu-id="d4231-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="d4231-110">Klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="d4231-110">Click **Search**.</span></span>

<span data-ttu-id="d4231-111">Ve výsledcích **Výsledky filtru** klepněte a zadejte **Set-Mailbox** v poli Filtr aktivity.</span><span class="sxs-lookup"><span data-stu-id="d4231-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="d4231-112">V seznamu výsledků vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="d4231-112">Select an audit record in the results.</span></span> <span data-ttu-id="d4231-113">V plovoucí panel **Podrobnosti** klepněte na tlačítko **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="d4231-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="d4231-114">Je nutné podívat se na podrobnosti každý záznam auditu k určení, pokud je aktivita spojena k předávání e-mailu.</span><span class="sxs-lookup"><span data-stu-id="d4231-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="d4231-115">**ObjectId**: Hodnota alias poštovní schránky, který byl upraven.</span><span class="sxs-lookup"><span data-stu-id="d4231-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="d4231-116">**Parametry**: _ForwardingSmtpAddress_ označuje cílovou e-mailovou adresu.</span><span class="sxs-lookup"><span data-stu-id="d4231-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="d4231-117">**ID uživatele**: uživatel nakonfigurovat předávání e-mailu na poštovní schránky v poli **ID objektu** .</span><span class="sxs-lookup"><span data-stu-id="d4231-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="d4231-118">Další informace naleznete v tématu [určení, která nastavila e-mail dál pro poštovní schránky](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="d4231-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-who-set-up-email-forwarding-for-a-mailbox).</span></span>
