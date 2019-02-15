---
title: 1385-office-365výstraha zásady
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: a0a1c749a120714c33cffd9fbdad08ea2cd6d62f
ms.sourcegitcommit: 983d08cd9ffe9542db75102b5b5c036d38eff67b
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/14/2019
ms.locfileid: "30056687"
---
# <a name="office-365-alert-policies"></a><span data-ttu-id="607d1-102">Oznámení zásady Office 365</span><span class="sxs-lookup"><span data-stu-id="607d1-102">Office 365 Alert policies</span></span>

<span data-ttu-id="607d1-p101">_AMP_ zabezpečení Office 365 nabízí centra kompatibility [oznámení výchozí zásady](https://docs.microsoft.com/office365/securitycompliance/alert-policies#default-alert-policies) aktivují výstrahy pro organizace s předplatným Office 365 Enterprise nebo Office 365 nám vláda E1/G1, E3/G3 nebo E5/G5. Proto admins mohou přijímat oznámení e-mailové oznámení odeslaných Office365Alerts@microsoft.com s řádkem Předmět, jako "nízkou závažností výstraha:*název výstrahy zásady*". Upozornění jsou oznámení odesílána při výstrahy se spouštějí pro běžné činnosti, například když uživatelé:</span><span class="sxs-lookup"><span data-stu-id="607d1-p101">The Office 365 Security & Compliance Center offers [default alert policies](https://docs.microsoft.com/office365/securitycompliance/alert-policies#default-alert-policies) that trigger alerts for organizations with an Office 365 Enterprise or Office 365 US Government E1/G1, E3/G3, or E5/G5 subscription. Therefore, admins may receive an alert email notification sent by Office365Alerts@microsoft.com with a subject line such as "A low-severity alert:*name of alert policy*". Alert notifications are sent when alerts are triggered for common activities, such as when users:</span></span>

- <span data-ttu-id="607d1-106">Vytvořte pravidla složky Doručená pošta pro předávání e-mailu.</span><span class="sxs-lookup"><span data-stu-id="607d1-106">Create inbox rules that forward email.</span></span>
- <span data-ttu-id="607d1-107">Přiřadíte oprávnění poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="607d1-107">Assign permissions their mailbox.</span></span>
- <span data-ttu-id="607d1-108">Sdílení nebo odstranění velkého počtu souborů v sdílení souborů služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="607d1-108">Sharing or deleting a large number of files in SharePoint file sharing.</span></span>
- <span data-ttu-id="607d1-109">Vytvořit služba eDiscovery hledání a exportovat výsledky hledání.</span><span class="sxs-lookup"><span data-stu-id="607d1-109">Create eDiscovery searches and export search results.</span></span>
 
<span data-ttu-id="607d1-110">Prohlížení a působit na oznámení:</span><span class="sxs-lookup"><span data-stu-id="607d1-110">To review and act on an alert:</span></span>

1. <span data-ttu-id="607d1-111">Přejít na [& zabezpečení centra kompatibility](https://protection.office.com) a přihlaste se.</span><span class="sxs-lookup"><span data-stu-id="607d1-111">Go to the [Security & Compliance Center](https://protection.office.com) and sign in.</span></span>
2. <span data-ttu-id="607d1-112">Klepněte na tlačítko **výstrahy > zobrazení výstrah**.</span><span class="sxs-lookup"><span data-stu-id="607d1-112">Click **Alerts > View alerts**.</span></span>
3. <span data-ttu-id="607d1-113">Klepněte na tlačítko výstrahy zobrazení plovoucí panel stránky s informace o výstraze.</span><span class="sxs-lookup"><span data-stu-id="607d1-113">Click an alert to display a flyout page with information about the alert.</span></span>

<span data-ttu-id="607d1-p102">Provést akci pro výstrahu, jako je například [Odebrání pravidla podezřelé složky Doručená pošta](https://docs.microsoft.com/office365/securitycompliance/responding-to-a-compromised-email-account). Nebo můžete jednoduše zavřete upozornění klepnutím na tlačítko **Odstranit** na stránce oznámení plovoucí panel.</span><span class="sxs-lookup"><span data-stu-id="607d1-p102">You can take action on an alert, such as [removing a suspicious inbox rule](https://docs.microsoft.com/office365/securitycompliance/responding-to-a-compromised-email-account). Or you can simply close the alert by clicking **Resolve** on the alert flyout page.</span></span>

<span data-ttu-id="607d1-116">Další informace o konfiguraci a správě upozornění zásad naleznete [v tomto článku](https://docs.microsoft.com/office365/securitycompliance/alert-policies).</span><span class="sxs-lookup"><span data-stu-id="607d1-116">For more information about configuring and managing alert policies, see  [this article](https://docs.microsoft.com/office365/securitycompliance/alert-policies).</span></span>

<span data-ttu-id="607d1-117">**Důležité**: oznámení e-mailové oznámení od společnosti Microsoft nikdy zeptá, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="607d1-117">**Important**: Alert email notifications from Microsoft will never ask you to do the following:</span></span>

- <span data-ttu-id="607d1-118">Zadejte heslo.</span><span class="sxs-lookup"><span data-stu-id="607d1-118">Provide a password.</span></span>
- <span data-ttu-id="607d1-119">Ověřte podrobnosti zabezpečení vašeho účtu.</span><span class="sxs-lookup"><span data-stu-id="607d1-119">Verify the security details of your account.</span></span>
- <span data-ttu-id="607d1-120">Znovu sami ověřit.</span><span class="sxs-lookup"><span data-stu-id="607d1-120">Re-authenticate yourself.</span></span>

<span data-ttu-id="607d1-p103">Pokud obdržíte e-mailové zprávy tímto způsobem, nebyla odeslána společnosti Microsoft a považovat za nevyžádanou podvodnou poštu. Pokud se tak stane, prosím [ohlaste společnosti Microsoft](https://docs.microsoft.com/office365/SecurityCompliance/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop).</span><span class="sxs-lookup"><span data-stu-id="607d1-p103">If you receive an email message like this, it was not sent by Microsoft and should be considered a phishing scam. If that happens, please [report it to Microsoft](https://docs.microsoft.com/office365/SecurityCompliance/report-junk-email-and-phishing-scams-in-outlook-on-the-web-eop).</span></span>