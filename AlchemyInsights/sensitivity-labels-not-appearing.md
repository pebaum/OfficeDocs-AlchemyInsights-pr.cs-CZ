---
title: Nezobrazují se popisky citlivosti
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 72dc88a55b55954f34c95fa5b5038f472261c5bb
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758378"
---
# <a name="sensitivity-labels-not-appearing"></a><span data-ttu-id="f10d2-102">Nezobrazují se popisky citlivosti</span><span class="sxs-lookup"><span data-stu-id="f10d2-102">Sensitivity labels not appearing</span></span>

<span data-ttu-id="f10d2-103">Popisky citlivosti umožňují klasifikovat a chránit citlivý obsah.</span><span class="sxs-lookup"><span data-stu-id="f10d2-103">Sensitivity labels allow you to classify and help protect your sensitive content.</span></span> <span data-ttu-id="f10d2-104">Lze je vytvořit v Centru dodržování předpisů Microsoft 365, Centru zabezpečení Microsoft 365 nebo Centru zabezpečení microsoftu 365 & compliance center v části Klasifikace > popisky citlivosti.</span><span class="sxs-lookup"><span data-stu-id="f10d2-104">They can be created in the Microsoft 365 compliance center, Microsoft 365 security center, or Microsoft 365 security & Compliance Center under Classification > Sensitivity labels.</span></span> <span data-ttu-id="f10d2-105">Další informace o této funkci naleznete v [tématu Přehled popisků citlivosti](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="f10d2-105">To learn more about this feature, see [Overview of sensitivity labels](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels).</span></span>

<span data-ttu-id="f10d2-106">Pokud jste nakonfigurovali štítky citlivosti, ale nezobrazovaly se v aplikacích Office, zkontrolujte následující:</span><span class="sxs-lookup"><span data-stu-id="f10d2-106">If you configured your sensitivity labels but they aren't appearing in the Office apps, check the following:</span></span>

- <span data-ttu-id="f10d2-107">Zkontrolujte, zda byl popisek citlivosti [publikován](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) požadovaným uživatelům a skupinám.</span><span class="sxs-lookup"><span data-stu-id="f10d2-107">Confirm that the sensitivity label has been [published](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) to the users and groups that you want.</span></span>

- <span data-ttu-id="f10d2-108">Zkontrolujte, zda uživatel používá aplikaci, která podporuje popisky citlivosti – viz [popisky citlivosti v dokumentu](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable).</span><span class="sxs-lookup"><span data-stu-id="f10d2-108">Confirm that the user is using an app that supports sensitivity labels - see [sensitivity labels in your document](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable).</span></span>

- <span data-ttu-id="f10d2-109">Pokud [migrujete popisky Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), uvědomte si aspekty uvedené [zde](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).</span><span class="sxs-lookup"><span data-stu-id="f10d2-109">If you're [migrating Azure Information Protection labels](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), be aware of the considerations listed [here](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).</span></span>

- <span data-ttu-id="f10d2-110">Podpora ochrany před únikem informací (DLP) (Ochrana dat) (DLP): V současné době lze v zásadách ochrany před únikem informací použít pouze popisky uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="f10d2-110">Data loss prevention (DLP) support: Currently, only retention labels can be used as a condition in DLP policies.</span></span>  <span data-ttu-id="f10d2-111">Podpora popisků citlivosti v zásadách ochrany před únikem dat ještě není k dispozici, ale pracujeme na ní.</span><span class="sxs-lookup"><span data-stu-id="f10d2-111">Support for sensitivity labels in a DLP policy is not available yet but we're working on it.</span></span>

- <span data-ttu-id="f10d2-112">Pokud je na popisku citlivosti povoleno šifrování, můžete zvolit:</span><span class="sxs-lookup"><span data-stu-id="f10d2-112">When encryption is enabled on a sensitivity label, you can choose either to:</span></span>
    - <span data-ttu-id="f10d2-113">Přiřazení oprávnění nyní</span><span class="sxs-lookup"><span data-stu-id="f10d2-113">Assign permissions now</span></span>
    - <span data-ttu-id="f10d2-114">Povolit uživatelům přiřazovat oprávnění</span><span class="sxs-lookup"><span data-stu-id="f10d2-114">Let users assign permissions</span></span>


<span data-ttu-id="f10d2-115">Další informace o možných problémech naleznete v [tématu Známé problémy s popisky citlivosti](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span><span class="sxs-lookup"><span data-stu-id="f10d2-115">For more information on possible issues, see [Known issues with sensitivity labels](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span></span>