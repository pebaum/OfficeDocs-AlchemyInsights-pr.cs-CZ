---
title: Řešení problémů s Office 365 Advanced Threat Protection (ATP)
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: 99bc985f2d66693aca45f0833ab47c043acc1324
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766738"
---
# <a name="troubleshoot-issues-with-office-365-atp"></a><span data-ttu-id="f08f0-102">Řešení problémů s úřadem ATP Office 365</span><span class="sxs-lookup"><span data-stu-id="f08f0-102">Troubleshoot issues with Office 365 ATP</span></span>

- <span data-ttu-id="f08f0-103">**Oznámení zpoždění s doručováním e-mailových zpráv?**</span><span class="sxs-lookup"><span data-stu-id="f08f0-103">**Notice delays with email message delivery**?</span></span> <span data-ttu-id="f08f0-104">Zkuste použít možnost Dynamické doručování pro zásady bezpečné přílohy ATP.</span><span class="sxs-lookup"><span data-stu-id="f08f0-104">Try using the Dynamic Delivery option for your ATP Safe Attachments policies.</span></span> <span data-ttu-id="f08f0-105">Tím se zabrání zpoždění doručování e-mailových zpráv a zároveň ochránípříjemce před škodlivými soubory.</span><span class="sxs-lookup"><span data-stu-id="f08f0-105">This will avoid email message delivery delays while protecting recipients from malicious files.</span></span>
- <span data-ttu-id="f08f0-106">**Chcete nahlásit falešně pozitivní nebo falešně negativní**výsledky?</span><span class="sxs-lookup"><span data-stu-id="f08f0-106">**Do you want to report false positives or false negatives**?</span></span> <span data-ttu-id="f08f0-107">Tento odkaz slouží k odeslání souboru k analýze:[https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span><span class="sxs-lookup"><span data-stu-id="f08f0-107">Use this link to submit your file for analysis: [https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span></span>
- <span data-ttu-id="f08f0-108">**Věděli jste, že můžete povolit ochranu atp bezpečné odkazy pro e-maily odeslané mezi lidmi ve vaší organizaci?**</span><span class="sxs-lookup"><span data-stu-id="f08f0-108">**Did you know that you can enable ATP Safe Links protection for email sent between people in your organization**?</span></span> <span data-ttu-id="f08f0-109">Postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="f08f0-109">Follow these steps:</span></span>
    1. <span data-ttu-id="f08f0-110">Přejděte https://protection.office.comna a přihlaste se.</span><span class="sxs-lookup"><span data-stu-id="f08f0-110">Go to https://protection.office.com, and sign in.</span></span>
    2. <span data-ttu-id="f08f0-111">Přejděte na bezpečné odkazy > **pro správu** >  **hrozeb**.**Safe Links**</span><span class="sxs-lookup"><span data-stu-id="f08f0-111">Go to **Threat management** > **Policy** > **Safe Links**.</span></span>
    3. <span data-ttu-id="f08f0-112">V části **Zásady, které platí pro konkrétní příjemce**, upravte (nebo přidejte) zásadu.</span><span class="sxs-lookup"><span data-stu-id="f08f0-112">Under **Policies that apply to specific recipients**, edit (or add) a policy.</span></span>
    4. <span data-ttu-id="f08f0-113">Vyberte **Použít bezpečné odkazy na zprávy odeslané v rámci organizace**.</span><span class="sxs-lookup"><span data-stu-id="f08f0-113">Select **Apply safe links to messages sent within the organization**.</span></span>
    5. <span data-ttu-id="f08f0-114">Uložte si zásady a nechte asi 30 minut, než se změny propracují přes vaše datové centrum.</span><span class="sxs-lookup"><span data-stu-id="f08f0-114">Save your policy, and allow about 30 minutes for your changes to work their way through your datacenter.</span></span>
- <span data-ttu-id="f08f0-115">Další pomoc s ochrany matná z atp najdete v [tématu Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span><span class="sxs-lookup"><span data-stu-id="f08f0-115">To get more help with ATP, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/office365/securitycompliance/office-365-atp).</span></span>