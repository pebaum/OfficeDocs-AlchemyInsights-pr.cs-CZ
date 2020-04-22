---
title: Identifikace IP adresy a klienta v protokolech auditu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: d1a0d412fc0c6d79e50b101ca759127522f45dcd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716381"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="8cdb3-102">Identifikace IP adresy a klienta v protokolech auditu</span><span class="sxs-lookup"><span data-stu-id="8cdb3-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="8cdb3-103">Ip adresa, která odpovídá aktivitě uživatele nebo správce microsoftu 365, je zobrazena v protokolech auditu.</span><span class="sxs-lookup"><span data-stu-id="8cdb3-103">The IP address that corresponds to an activity by a Microsoft 365 user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="8cdb3-104">Informace o klientovi jsou také protokolovány.</span><span class="sxs-lookup"><span data-stu-id="8cdb3-104">The client information is also logged.</span></span> <span data-ttu-id="8cdb3-105">Zde jsou kroky k identifikaci těchto informací</span><span class="sxs-lookup"><span data-stu-id="8cdb3-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="8cdb3-106">Přihlaste se k [Centru dodržování předpisů pro zabezpečení & microsoft 365](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="8cdb3-106">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="8cdb3-107">Přejděte na stránku**hledání protokolu auditování** **vyhledávání.** > </span><span class="sxs-lookup"><span data-stu-id="8cdb3-107">Go to the **Search** > **Audit log search** page.</span></span>

   <span data-ttu-id="8cdb3-108">Pokud máte zájem o konkrétní aktivitu, vyberte ji ze seznamu **Aktivity.**</span><span class="sxs-lookup"><span data-stu-id="8cdb3-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="8cdb3-109">Pokud tomu tak není, budou pro vybraného uživatele vráceny všechny aktivity (výchozí nastavení).</span><span class="sxs-lookup"><span data-stu-id="8cdb3-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="8cdb3-110">**Poznámka**: Některé aktivity nemusí být v nabídce **Aktivity** k dispozici. tyto položky auditu však budou vráceny, pokud je **vybrána možnost Zobrazit výsledky pro všechny aktivity** (výchozí nastavení).</span><span class="sxs-lookup"><span data-stu-id="8cdb3-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="8cdb3-111">Zadejte uživatelské jméno do pole **Uživatelé,** vyberte příslušné časové období aktivity a klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="8cdb3-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="8cdb3-112">Ve výsledcích se zobrazí ip adresa pro tuto aktivitu v podokně výsledků.</span><span class="sxs-lookup"><span data-stu-id="8cdb3-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="8cdb3-113">Výběrem záznamu auditu zobrazíte podrobné informace v informačním rámečku **Podrobnosti** (například Klient, Uživatel, který provedl akci atd.).</span><span class="sxs-lookup"><span data-stu-id="8cdb3-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="8cdb3-114">Další informace naleznete [v tématu Hledání IP adresy počítače používaného pro přístup k ohroženému účtu](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="8cdb3-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
