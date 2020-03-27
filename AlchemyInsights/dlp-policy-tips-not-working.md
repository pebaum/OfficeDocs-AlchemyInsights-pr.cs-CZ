---
title: Tipy pro zásady ochrany před únikem informací nefungují
ms.author: deniseb
author: denisebmsft
manager: laurawims
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: c03d30be-474a-4a34-b3c0-240eb2a2c466
ms.custom:
- "1428"
- "3200001"
ms.openlocfilehash: 6375fa8077529f36ae95d6632ad4d2db5625dc29
ms.sourcegitcommit: d108a2da2f5dab05246e30b5108cca5173e09051
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/26/2020
ms.locfileid: "42977227"
---
# <a name="dlp-policy-tip-issues"></a><span data-ttu-id="c5cd8-102">Problémy s tipem na zásady ochrany před únikem</span><span class="sxs-lookup"><span data-stu-id="c5cd8-102">DLP Policy Tip issues</span></span>

<span data-ttu-id="c5cd8-103">**Důležité:** V těchto nebývalých časech podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrive zůstaly vysoce dostupné – další informace najdete na stránce [Dočasné úpravy funkcí SharePointu Online.](https://aka.ms/ODSPAdjustments)</span><span class="sxs-lookup"><span data-stu-id="c5cd8-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

<span data-ttu-id="c5cd8-104">**Tipy pro zásady ochrany před únikem informací**</span><span class="sxs-lookup"><span data-stu-id="c5cd8-104">**DLP policy tips**</span></span>

<span data-ttu-id="c5cd8-105">Při použití **zásad ochrany před únikem informací**mohou být uživatelé upozorněni na porušení zásad pomocí tipů **zásad**.</span><span class="sxs-lookup"><span data-stu-id="c5cd8-105">When using **DLP policies**, users can be notified of a policy violation with **policy tips**.</span></span> <span data-ttu-id="c5cd8-106">Správci mohou nakonfigurovat tipy zásad k zobrazení při testování zásad ochrany před únikem informací nebo při úplném vynucování.</span><span class="sxs-lookup"><span data-stu-id="c5cd8-106">Admins can configure policy tips to display while testing their DLP policy or when the policy is in full enforcement mode.</span></span>
  
<span data-ttu-id="c5cd8-107">Chcete-li nakonfigurovat tipy pro zásady ochrany před únikem informací v centru zabezpečení a dodržování předpisů v režimu úplného vynucení, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="c5cd8-107">To configure policy tips on your DLP policy in the Security and Compliance center in full enforcement mode, do the following:</span></span>
  
- <span data-ttu-id="c5cd8-108">Ujistěte se, že byly **povoleny** tipy zásad na pravidlo ochrany před únikem informací pomocí [kroků zde](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span><span class="sxs-lookup"><span data-stu-id="c5cd8-108">Ensure policy tips have been **enabled** on the DLP rule using the steps [here](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

- <span data-ttu-id="c5cd8-109">Ujistěte se, že váš **obsah odpovídá tomu,** co je **nutné** k aktivaci pravidla uvedeného v tomto článku [zde](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="c5cd8-109">Ensure your **content matches** what is **required** to trigger the rule outlined in this article [here](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="c5cd8-110">Tipy pro zásady se zobrazují v aplikaci OWA i v aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="c5cd8-110">Policy tips display in both OWA and Outlook.</span></span> <span data-ttu-id="c5cd8-111">Pokud však používáte **Outlook 2013 nebo novější**, zobrazí se tipy zásad pouze za určitých podmínek.</span><span class="sxs-lookup"><span data-stu-id="c5cd8-111">However, when using **Outlook 2013 or later**, policy tips are only displayed under certain conditions.</span></span> <span data-ttu-id="c5cd8-112">Zde jsou uvedeny tyto podmínky: [Podporované podmínky pro Outlook 2013 nebo novější pro zobrazení tipů zásad](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span><span class="sxs-lookup"><span data-stu-id="c5cd8-112">These conditions are listed here: [Supported conditions for Outlook 2013 or later for displaying Policy Tips](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span></span>

<span data-ttu-id="c5cd8-113">Další informace o tipech pro zásady ochrany před únikem informací naleznete v [tématu: Zobrazit tipy zásad pro zásady ochrany před únikem informací](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span><span class="sxs-lookup"><span data-stu-id="c5cd8-113">For additional information on DLP policy tips, see: [Show policy tips for DLP Policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span></span>
  