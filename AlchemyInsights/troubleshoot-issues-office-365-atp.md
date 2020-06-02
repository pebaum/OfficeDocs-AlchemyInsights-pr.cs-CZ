---
title: Poradce při potížích s pokročilou ochranou před hrozbami Office 365 (ATP)
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
ms.openlocfilehash: f1dc675c8a8217ea2824ad46e029bfa303303e6a
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511105"
---
# <a name="troubleshoot-issues-with-office-365-atp"></a><span data-ttu-id="9692b-102">Řešení problémů s office 365 ATP</span><span class="sxs-lookup"><span data-stu-id="9692b-102">Troubleshoot issues with Office 365 ATP</span></span>

- <span data-ttu-id="9692b-103">**Oznámení zpoždění s doručením e-mailové zprávy?**</span><span class="sxs-lookup"><span data-stu-id="9692b-103">**Notice delays with email message delivery**?</span></span> <span data-ttu-id="9692b-104">Zkuste použít možnost dynamické doručování pro zásady zabezpečení atp.</span><span class="sxs-lookup"><span data-stu-id="9692b-104">Try using the Dynamic Delivery option for your ATP Safe Attachments policies.</span></span> <span data-ttu-id="9692b-105">Tím se zabrání zpoždění doručování e-mailových zpráv a zároveň budou příjemci chráněni před škodlivými soubory.</span><span class="sxs-lookup"><span data-stu-id="9692b-105">This will avoid email message delivery delays while protecting recipients from malicious files.</span></span>
- <span data-ttu-id="9692b-106">**Chcete nahlásit falešně pozitivní nebo falešně negativní výsledky**?</span><span class="sxs-lookup"><span data-stu-id="9692b-106">**Do you want to report false positives or false negatives**?</span></span> <span data-ttu-id="9692b-107">Tento odkaz slouží k odeslání souboru k analýze:[https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span><span class="sxs-lookup"><span data-stu-id="9692b-107">Use this link to submit your file for analysis: [https://microsoft.com/wdsi/filesubmission](https://microsoft.com/wdsi/filesubmission)</span></span>
- <span data-ttu-id="9692b-108">**Věděli jste, že můžete povolit ochranu bezpečných odkazů ATP pro e-maily odeslané mezi lidmi ve vaší organizaci?**</span><span class="sxs-lookup"><span data-stu-id="9692b-108">**Did you know that you can enable ATP Safe Links protection for email sent between people in your organization**?</span></span> <span data-ttu-id="9692b-109">Postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="9692b-109">Follow these steps:</span></span>
    1. <span data-ttu-id="9692b-110">Přejděte do https://protection.office.com , a přihlaste se.</span><span class="sxs-lookup"><span data-stu-id="9692b-110">Go to https://protection.office.com, and sign in.</span></span>
    2. <span data-ttu-id="9692b-111">Přejděte **Threat management**na bezpečné odkazy zásad  >  **správy**  >  **hrozeb**.</span><span class="sxs-lookup"><span data-stu-id="9692b-111">Go to **Threat management** > **Policy** > **Safe Links**.</span></span>
    3. <span data-ttu-id="9692b-112">V části **Zásady, které se vztahují na konkrétní příjemce**, upravte (nebo přidejte) zásadu.</span><span class="sxs-lookup"><span data-stu-id="9692b-112">Under **Policies that apply to specific recipients**, edit (or add) a policy.</span></span>
    4. <span data-ttu-id="9692b-113">Vyberte **Použít bezpečné odkazy na zprávy odeslané v rámci organizace**.</span><span class="sxs-lookup"><span data-stu-id="9692b-113">Select **Apply safe links to messages sent within the organization**.</span></span>
    5. <span data-ttu-id="9692b-114">Uložte zásady a povolte asi 30 minut, aby se změny propracovaly přes vaše datové centrum.</span><span class="sxs-lookup"><span data-stu-id="9692b-114">Save your policy, and allow about 30 minutes for your changes to work their way through your datacenter.</span></span>
- <span data-ttu-id="9692b-115">Další nápovědu k ochraně ATP najdete v tématu Ochrana před [pokročilými hrozbami Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp).</span><span class="sxs-lookup"><span data-stu-id="9692b-115">To get more help with ATP, see [Office 365 Advanced Threat Protection](https://docs.microsoft.com/microsoft-365/security/office-365-security/office-365-atp).</span></span>