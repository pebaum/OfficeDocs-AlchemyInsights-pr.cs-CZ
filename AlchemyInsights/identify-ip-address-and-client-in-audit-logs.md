---
title: Určení adresy IP a klient z protokolů auditování
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1367"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: e0119762d2a34bd2b0da827faf55c832e29d8a2b
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36539022"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="02770-102">Určení adresy IP a klient z protokolů auditování</span><span class="sxs-lookup"><span data-stu-id="02770-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="02770-103">Adresu IP, která odpovídá aktivity služeb Office 365, uživatel nebo správce se zobrazí záznamy auditu.</span><span class="sxs-lookup"><span data-stu-id="02770-103">The IP address that corresponds to an activity by an Office 365 user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="02770-104">Informace o klientovi je také zaznamenána.</span><span class="sxs-lookup"><span data-stu-id="02770-104">The client information is also logged.</span></span> <span data-ttu-id="02770-105">Zde jsou kroky k identifikaci těchto informací</span><span class="sxs-lookup"><span data-stu-id="02770-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="02770-106">Přihlášení do [Centra kompatibility aplikace Office 365 zabezpečení &](https://protection.office.com/).</span><span class="sxs-lookup"><span data-stu-id="02770-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="02770-107">Přejít na **vyhledávání** > **auditování protokolu vyhledávací** stránku.</span><span class="sxs-lookup"><span data-stu-id="02770-107">Go to the **Search** > **Audit log search** page.</span></span>

   <span data-ttu-id="02770-108">Pokud vás zajímají konkrétní aktivity, vyberte ji ze seznamu **aktivit** .</span><span class="sxs-lookup"><span data-stu-id="02770-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="02770-109">Pokud ne, budou vráceny všechny aktivity pro vybraného uživatele (výchozí nastavení).</span><span class="sxs-lookup"><span data-stu-id="02770-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="02770-110">**Poznámka**: některé činnosti nemusí být k dispozici v nabídce **činností** ; však ty položky auditu bude vrácena, pokud je **Zobrazit výsledky pro všechny činnosti** (výchozí nastavení).</span><span class="sxs-lookup"><span data-stu-id="02770-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="02770-111">Zadejte uživatelské jméno do pole **Uživatelé** a vyberte příslušné období aktivity klepněte na tlačítko **Hledat**.</span><span class="sxs-lookup"><span data-stu-id="02770-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="02770-112">Ve výsledcích se zobrazí adresu IP pro tuto činnost v podokně výsledků.</span><span class="sxs-lookup"><span data-stu-id="02770-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="02770-113">Vyberte záznam auditu zobrazíte podrobné informace vždy **Podrobnosti** (například klienta, uživatel, který provedl akci, atd.).</span><span class="sxs-lookup"><span data-stu-id="02770-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="02770-114">Další informace naleznete v tématu [vyhledání adresy IP počítače pro přístup k ohrožení zabezpečení účtu](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="02770-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
