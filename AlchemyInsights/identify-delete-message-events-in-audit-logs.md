---
title: Identifikace událostí odstranění zpráv v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 641c0216491186aeb423a13854c6b39ee005e5df
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508981"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="689f2-102">Protokoly auditu pro odstraněné e-mailové zprávy</span><span class="sxs-lookup"><span data-stu-id="689f2-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="689f2-103">Počínaje lednem 2019 microsoft ve výchozím nastavení zapíná protokolování auditu poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="689f2-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="689f2-104">V opačném případě chcete-li zkontrolovat události odstranění zprávy pro konkrétního uživatele, je třeba ručně povolit akce odstranění pro auditování.</span><span class="sxs-lookup"><span data-stu-id="689f2-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="689f2-105">Pokud je protokolování auditu poštovní schránky již pro vaši organizaci nebo pro konkrétního uživatele povoleno, postupujte podle následujících kroků.</span><span class="sxs-lookup"><span data-stu-id="689f2-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="689f2-106">Přihlaste se do [Centra dodržování předpisů zabezpečení microsoftu 365 &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="689f2-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="689f2-107">Klepněte na tlačítko **Hledat a vyšetřování** a vyberte možnost Hledat v protokolu **auditu**.</span><span class="sxs-lookup"><span data-stu-id="689f2-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="689f2-108">V polích **Počáteční datum** a **Koncové datum** vyberte rozsah dat.</span><span class="sxs-lookup"><span data-stu-id="689f2-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="689f2-109">Zadejte uživatelské jméno pro uživatele, který chcete prozkoumat (uživatel, který odstranil položky).</span><span class="sxs-lookup"><span data-stu-id="689f2-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="689f2-110">V poli **Aktivity** vyberte **položku Odstraněná zpráva ze složky Odstraněná pošta** a **Přesunuté zprávy do složky Odstraněná pošta**.</span><span class="sxs-lookup"><span data-stu-id="689f2-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="689f2-111">Klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="689f2-111">Click **Search**.</span></span>

<span data-ttu-id="689f2-112">Ve výsledcích vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="689f2-112">In the results, select an audit record.</span></span> <span data-ttu-id="689f2-113">V informačním rámečku podrobnosti klepněte na tlačítko **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="689f2-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="689f2-114">Další informace o odstraněné položce (například řádek předmětu a umístění položky při jeho odstranění) se zobrazí v poli **AffectedItems.**</span><span class="sxs-lookup"><span data-stu-id="689f2-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="689f2-115">Vlastnost **ClientInfoString** zobrazí, pokud k odstranění došlo v aplikaci Outlook, Outlook na webu (dříve označované jako Outlook Web App) nebo jiné zařízení.</span><span class="sxs-lookup"><span data-stu-id="689f2-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="689f2-116">Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="689f2-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="689f2-117">**Poznámka:** Odstraněné položky nelze načíst pomocí funkce protokolu auditu.</span><span class="sxs-lookup"><span data-stu-id="689f2-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="689f2-118">Pokud chcete načíst odstraněné zprávy v Outlooku na webu, [přečtěte si tématu Obnovení odstraněných položek v Outlook Web Appu](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="689f2-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
