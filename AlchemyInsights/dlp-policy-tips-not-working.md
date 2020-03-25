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
ms.openlocfilehash: 51b4472fa721443192eb542cac45965df67634df
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932579"
---
# <a name="dlp-policy-tip-issues"></a><span data-ttu-id="cb3f4-102">Problémy s tipem na zásady ochrany před únikem</span><span class="sxs-lookup"><span data-stu-id="cb3f4-102">DLP Policy Tip issues</span></span>

<span data-ttu-id="cb3f4-103">**Důležité:** Mnoho zákazníků SharePointu Online a OneDrivu spouštějí důležité podnikové aplikace proti službě, která běží na pozadí.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="cb3f4-104">Patří mezi ně migrace obsahu, ochrana před únikem dat (DLP) a řešení zálohování.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="cb3f4-105">Během těchto bezprecedentních časů podnikáme kroky k zajištění toho, aby služby SharePointu Online a OneDrivu zůstaly vysoce dostupné a spolehlivé pro vaše uživatele, kteří jsou na službě závislí více než kdy dřív ve vzdálených pracovních scénářích.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="cb3f4-106">Na podporu tohoto cíle jsme implementovali přísnější omezení pro aplikace na pozadí (migrace, DLP a řešení zálohování) během denních denních hodin.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="cb3f4-107">Měli byste očekávat, že tyto aplikace dosáhnou velmi omezené propustnost v těchto časech.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="cb3f4-108">Během večerních a víkendových hodin pro region však bude služba připravena zpracovat výrazně vyšší objem požadavků z aplikací na pozadí.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="cb3f4-109">**Tipy pro zásady ochrany před únikem informací**</span><span class="sxs-lookup"><span data-stu-id="cb3f4-109">**DLP policy tips**</span></span>

<span data-ttu-id="cb3f4-110">Při použití **zásad ochrany před únikem informací**mohou být uživatelé upozorněni na porušení zásad pomocí tipů **zásad**.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-110">When using **DLP policies**, users can be notified of a policy violation with **policy tips**.</span></span> <span data-ttu-id="cb3f4-111">Správci mohou nakonfigurovat tipy zásad k zobrazení při testování zásad ochrany před únikem informací nebo při úplném vynucování.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-111">Admins can configure policy tips to display while testing their DLP policy or when the policy is in full enforcement mode.</span></span>
  
<span data-ttu-id="cb3f4-112">Chcete-li nakonfigurovat tipy pro zásady ochrany před únikem informací v centru zabezpečení a dodržování předpisů v režimu úplného vynucení, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="cb3f4-112">To configure policy tips on your DLP policy in the Security and Compliance center in full enforcement mode, do the following:</span></span>
  
- <span data-ttu-id="cb3f4-113">Ujistěte se, že byly **povoleny** tipy zásad na pravidlo ochrany před únikem informací pomocí [kroků zde](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span><span class="sxs-lookup"><span data-stu-id="cb3f4-113">Ensure policy tips have been **enabled** on the DLP rule using the steps [here](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

- <span data-ttu-id="cb3f4-114">Ujistěte se, že váš **obsah odpovídá tomu,** co je **nutné** k aktivaci pravidla uvedeného v tomto článku [zde](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="cb3f4-114">Ensure your **content matches** what is **required** to trigger the rule outlined in this article [here](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="cb3f4-115">Tipy pro zásady se zobrazují v aplikaci OWA i v aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-115">Policy tips display in both OWA and Outlook.</span></span> <span data-ttu-id="cb3f4-116">Pokud však používáte **Outlook 2013 nebo novější**, zobrazí se tipy zásad pouze za určitých podmínek.</span><span class="sxs-lookup"><span data-stu-id="cb3f4-116">However, when using **Outlook 2013 or later**, policy tips are only displayed under certain conditions.</span></span> <span data-ttu-id="cb3f4-117">Zde jsou uvedeny tyto podmínky: [Podporované podmínky pro Outlook 2013 nebo novější pro zobrazení tipů zásad](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span><span class="sxs-lookup"><span data-stu-id="cb3f4-117">These conditions are listed here: [Supported conditions for Outlook 2013 or later for displaying Policy Tips](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips#outlook-2013-and-later-supports-showing-policy-tips-for-only-some-conditions)</span></span>

<span data-ttu-id="cb3f4-118">Další informace o tipech pro zásady ochrany před únikem informací naleznete v [tématu: Zobrazit tipy zásad pro zásady ochrany před únikem informací](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span><span class="sxs-lookup"><span data-stu-id="cb3f4-118">For additional information on DLP policy tips, see: [Show policy tips for DLP Policies](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips)</span></span>
  