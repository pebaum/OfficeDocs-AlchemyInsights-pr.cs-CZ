---
title: Identifikovat odstranit zprávy události v protokolech auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1370"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: b358b7944b82182a8551d64701e6879a01816524
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539202"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="b0a14-102">Protokoly auditu pro odstraněné e-mailové zprávy</span><span class="sxs-lookup"><span data-stu-id="b0a14-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="b0a14-103">Spuštění v lednu 2019, Microsoft je zapnutí ve výchozím nastavení je protokolování auditování poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="b0a14-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="b0a14-104">Jinak můžete ověřit události odstranit zprávy pro určitého uživatele, je třeba ručně povolit auditování akce odstranění.</span><span class="sxs-lookup"><span data-stu-id="b0a14-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="b0a14-105">Pokud auditování poštovní schránky ve vaší organizaci nebo pro konkrétního uživatele je již povoleno protokolování, postupujte následujícím způsobem.</span><span class="sxs-lookup"><span data-stu-id="b0a14-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="b0a14-106">Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="b0a14-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="b0a14-107">Klepněte na tlačítko **vyhledávání a vyšetřování** a vyberte **Hledat protokolu auditu**.</span><span class="sxs-lookup"><span data-stu-id="b0a14-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="b0a14-108">Vyberte rozsah dat v polích **Počáteční datum** a **Koncové datum** .</span><span class="sxs-lookup"><span data-stu-id="b0a14-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="b0a14-109">Zadejte uživatelské jméno uživatele, který chcete prozkoumat (uživatel, který odstraněné položky).</span><span class="sxs-lookup"><span data-stu-id="b0a14-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="b0a14-110">V oblasti **aktivity** vyberte **odstraněné zprávy ze složky Odstraněná pošta** a **Moved zprávy do složky Odstraněná pošta**.</span><span class="sxs-lookup"><span data-stu-id="b0a14-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="b0a14-111">Klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="b0a14-111">Click **Search**.</span></span>

<span data-ttu-id="b0a14-112">V seznamu výsledků vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="b0a14-112">In the results, select an audit record.</span></span> <span data-ttu-id="b0a14-113">V plovoucí panel Podrobnosti klepněte na tlačítko **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="b0a14-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="b0a14-114">Další informace o odstraněné položky (například předmět a umístění položky po odstranění) se zobrazí v poli **AffectedItems** .</span><span class="sxs-lookup"><span data-stu-id="b0a14-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="b0a14-115">Vlastnost **ClientInfoString** se zobrazí, pokud došlo k odstranění v aplikaci Outlook, aplikace Outlook na webu (dříve známá jako aplikace Outlook Web App) nebo jiné zařízení.</span><span class="sxs-lookup"><span data-stu-id="b0a14-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="b0a14-116">Další informace naleznete v tématu [určení, která nastavila e-mail dál pro poštovní schránky](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="b0a14-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="b0a14-117">**Poznámka**: Nelze načíst odstraněné položky pomocí funkce protokolu auditu.</span><span class="sxs-lookup"><span data-stu-id="b0a14-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="b0a14-118">Chcete-li obnovit odstraněné zprávy v aplikaci Outlook na webu, naleznete v tématu [Obnovit odstraněné položky v aplikaci Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="b0a14-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
