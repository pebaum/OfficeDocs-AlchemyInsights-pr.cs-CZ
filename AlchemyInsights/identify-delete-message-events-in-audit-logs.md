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
ms.openlocfilehash: 797a4b1146862faf91d2b9e8d74feade90f71650
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716489"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="02d58-102">Protokoly auditování odstraněných e-mailových zpráv</span><span class="sxs-lookup"><span data-stu-id="02d58-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="02d58-103">Od ledna 2019 společnost Microsoft ve výchozím nastavení zapíná protokolování auditu poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="02d58-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="02d58-104">V opačném případě chcete zkontrolovat odstranění událostí zprávy pro konkrétního uživatele, je třeba ručně povolit akce odstranění pro auditování.</span><span class="sxs-lookup"><span data-stu-id="02d58-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="02d58-105">Pokud je protokolování auditu poštovní schránky již povoleno pro vaši organizaci nebo pro konkrétního uživatele, postupujte podle následujících kroků.</span><span class="sxs-lookup"><span data-stu-id="02d58-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="02d58-106">Přihlášení do [Centra dodržování předpisů pro zabezpečení & microsoftu 365](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="02d58-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="02d58-107">Klepněte na tlačítko **Hledat a šetření** a vyberte možnost Hledání protokolu **auditu**.</span><span class="sxs-lookup"><span data-stu-id="02d58-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="02d58-108">Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum.**</span><span class="sxs-lookup"><span data-stu-id="02d58-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="02d58-109">Zadejte uživatelské jméno uživatele, kterého chcete prozkoumat (uživatele, který položky odstranil).</span><span class="sxs-lookup"><span data-stu-id="02d58-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="02d58-110">V poli **Aktivity** vyberte **Odstraněná zpráva ze složky Odstraněná pošta** a **Přesunuté zprávy do složky Odstraněná pošta**.</span><span class="sxs-lookup"><span data-stu-id="02d58-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="02d58-111">Klepněte na **tlačítko Hledat**.</span><span class="sxs-lookup"><span data-stu-id="02d58-111">Click **Search**.</span></span>

<span data-ttu-id="02d58-112">Ve výsledcích vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="02d58-112">In the results, select an audit record.</span></span> <span data-ttu-id="02d58-113">V informačním rámečku podrobnosti klikněte na **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="02d58-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="02d58-114">Další informace o odstraněné položce (například řádek předmětu a umístění položky při jeho odstranění) se zobrazí v poli **Ovlivněné položky.**</span><span class="sxs-lookup"><span data-stu-id="02d58-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="02d58-115">Vlastnost **ClientInfoString** zobrazí, pokud k odstranění došlo v outlooku, outlooku na webu (dříve označované jako Outlook Web App) nebo v jakémkoli jiném zařízení.</span><span class="sxs-lookup"><span data-stu-id="02d58-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="02d58-116">Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="02d58-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="02d58-117">**Poznámka:** Odstraněné položky nelze načíst pomocí funkce protokolu auditu.</span><span class="sxs-lookup"><span data-stu-id="02d58-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="02d58-118">Informace o načtení odstraněných zpráv v Outlooku na webu najdete [v tématu Obnovení odstraněných položek v Outlook Web Appu](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="02d58-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
