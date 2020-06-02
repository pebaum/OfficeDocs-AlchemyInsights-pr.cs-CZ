---
title: Identifikace externího předávání e-mailů v poštovních schránkách v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1369"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 592eb92e4b0fe0f9da2fa20bb93ffa4fbbb76662
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508945"
---
# <a name="identify-when-external-email-forwarding-is-configured-on-mailboxes"></a><span data-ttu-id="044a9-102">Zjištění, kdy je na poštovních schránkách nakonfigurováno externí předávání e-mailů</span><span class="sxs-lookup"><span data-stu-id="044a9-102">Identify when external email forwarding is configured on mailboxes</span></span>

<span data-ttu-id="044a9-103">Když uživatel Microsoft 365 nakonfiguruje externí předávání e-mailů v poštovní schránce, aktivita je auditována jako součást rutiny **Set-Mailbox.**</span><span class="sxs-lookup"><span data-stu-id="044a9-103">When a Microsoft 365 user configures external email forwarding on a mailbox, the activity is audited as part of the **Set-Mailbox** cmdlet.</span></span> <span data-ttu-id="044a9-104">Aktivitu můžete zobrazit pomocí vyhledávání v protokolu auditu v Centru dodržování předpisů zabezpečení &.</span><span class="sxs-lookup"><span data-stu-id="044a9-104">You can see the activity using audit log search in the Security & Compliance Center.</span></span>

1. <span data-ttu-id="044a9-105">Přihlaste se do [Centra dodržování předpisů zabezpečení microsoftu 365 &](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="044a9-105">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="044a9-106">Přejděte **Search**na  >  stránku**hledání protokolu auditu** hledání.</span><span class="sxs-lookup"><span data-stu-id="044a9-106">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="044a9-107">V polích **Počáteční datum** a **Koncové datum** vyberte rozsah dat.</span><span class="sxs-lookup"><span data-stu-id="044a9-107">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="044a9-108">Nemusíte zadávat uživatelské jméno.</span><span class="sxs-lookup"><span data-stu-id="044a9-108">You don't need to specify a username.</span></span> <span data-ttu-id="044a9-109">Ověřte, zda je pole **Aktivity** nastaveno na **Zobrazit výsledky pro všechny aktivity**.</span><span class="sxs-lookup"><span data-stu-id="044a9-109">Verify the **Activities** field is set to **Show results for all activities**.</span></span>

4. <span data-ttu-id="044a9-110">Klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="044a9-110">Click **Search**.</span></span>

<span data-ttu-id="044a9-111">Ve výsledcích klikněte na **Filtrovat výsledky** a do pole filtru aktivity zadejte **nastavit poštovní schránku.**</span><span class="sxs-lookup"><span data-stu-id="044a9-111">In the results, click **Filter Results** and type **Set-Mailbox** in the activity filter box.</span></span> <span data-ttu-id="044a9-112">Ve výsledcích vyberte záznam auditu.</span><span class="sxs-lookup"><span data-stu-id="044a9-112">Select an audit record in the results.</span></span> <span data-ttu-id="044a9-113">V informačním rámečku **Podrobnosti** klepněte na tlačítko **Další informace**.</span><span class="sxs-lookup"><span data-stu-id="044a9-113">In the **Details** flyout, click **More information**.</span></span> <span data-ttu-id="044a9-114">Musíte se podívat na podrobnosti každého záznamu auditu, abyste zjistili, zda aktivita souvisí s předáváním e-mailů.</span><span class="sxs-lookup"><span data-stu-id="044a9-114">You have to look at the details of each audit record to determine if the activity is related to email forwarding.</span></span>

- <span data-ttu-id="044a9-115">**ObjectId**: Hodnota aliasu poštovní schránky, která byla změněna.</span><span class="sxs-lookup"><span data-stu-id="044a9-115">**ObjectId**: The alias value of the mailbox that was modified.</span></span>

- <span data-ttu-id="044a9-116">**Parametry**: _ForwardingSmtpAddress_ označuje cílovou e-mailovou adresu.</span><span class="sxs-lookup"><span data-stu-id="044a9-116">**Parameters**: _ForwardingSmtpAddress_ indicates the target email address.</span></span>

- <span data-ttu-id="044a9-117">**UserId**: Uživatel, který nakonfiguroval předávání e-mailů v poštovní schránce v poli **ObjectId.**</span><span class="sxs-lookup"><span data-stu-id="044a9-117">**UserId**: The user who configured email forwarding on the mailbox in the **ObjectId** field.</span></span>

<span data-ttu-id="044a9-118">Další informace naleznete v [tématu Určení, kdo nastavil předávání e-mailů pro poštovní schránku](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).</span><span class="sxs-lookup"><span data-stu-id="044a9-118">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/microsoft-365/compliance/auditing-troubleshooting-scenarios#determine-who-set-up-email-forwarding-for-a-mailbox).</span></span>
