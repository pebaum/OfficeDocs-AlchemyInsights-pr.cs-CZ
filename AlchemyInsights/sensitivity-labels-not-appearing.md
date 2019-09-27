---
title: Popisky citlivosti se nezobrazují.
ms.author: stephow
author: stephow-MSFT
manager: laurawi
ms.date: ''
ms.audience: admin
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 4bf8e02246c966f22648467386a7862f0521fecf
ms.sourcegitcommit: 71978e2bb779b5955fd113f84512b83321b26912
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/26/2019
ms.locfileid: "37207218"
---
# <a name="sensitivity-labels-not-appearing"></a><span data-ttu-id="c571e-102">Popisky citlivosti se nezobrazují.</span><span class="sxs-lookup"><span data-stu-id="c571e-102">Sensitivity labels not appearing</span></span>

<span data-ttu-id="c571e-103">Popisky citlivosti umožňují klasifikovat a chránit citlivý obsah.</span><span class="sxs-lookup"><span data-stu-id="c571e-103">Sensitivity labels allow you to classify and help protect your sensitive content.</span></span> <span data-ttu-id="c571e-104">Lze je vytvořit v centru pro kompatibilita společnosti Microsoft 365, ve středisku Microsoft 365 Security Center nebo Office 365 Security Center & v sekci klasifikace citlivosti >.</span><span class="sxs-lookup"><span data-stu-id="c571e-104">They can be created in the Microsoft 365 compliance center, Microsoft 365 security center, or Office 365 Security & Compliance Center under Classification > Sensitivity labels.</span></span> <span data-ttu-id="c571e-105">Další informace o této funkci naleznete v [přehledu popisů citlivosti](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="c571e-105">To learn more about this feature, see [Overview of sensitivity labels](https://docs.microsoft.com/office365/securitycompliance/sensitivity-labels).</span></span>

<span data-ttu-id="c571e-106">Pokud jste nakonfigurovali popisky citlivosti, ale nezobrazují se v aplikacích sady Office, zkontrolujte následující:</span><span class="sxs-lookup"><span data-stu-id="c571e-106">If you configured your sensitivity labels but they aren't appearing in the Office apps, check the following:</span></span>

- <span data-ttu-id="c571e-107">Potvrďte, že popisek citlivosti byl [publikován](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) pro uživatele a skupiny, které požadujete.</span><span class="sxs-lookup"><span data-stu-id="c571e-107">Confirm that the sensitivity label has been [published](https://docs.microsoft.com/Office365/SecurityCompliance/sensitivity-labels#what-label-policies-can-do) to the users and groups that you want.</span></span>

- <span data-ttu-id="c571e-108">Potvrďte, že uživatel používá aplikaci podporující popisky citlivosti-viz [popisky citlivosti v dokumentu](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?ad=US&ui=en-US&rs=en-US#bkmk_whereavailable).</span><span class="sxs-lookup"><span data-stu-id="c571e-108">Confirm that the user is using an app that supports sensitivity labels - see [sensitivity labels in your document](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?ad=US&ui=en-US&rs=en-US#bkmk_whereavailable).</span></span>

- <span data-ttu-id="c571e-109">Pokud [migrujete štítky na ochranu informací Azure](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), uvědomte si [zde](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels)uvedené skutečnosti.</span><span class="sxs-lookup"><span data-stu-id="c571e-109">If you're [migrating Azure Information Protection labels](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), be aware of the considerations listed [here](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).</span></span>

- <span data-ttu-id="c571e-110">Podpora pro zabránění ztrátě dat (DLP): v současné době lze jako podmínku v zásadách DLP použít pouze retenční štítky.</span><span class="sxs-lookup"><span data-stu-id="c571e-110">Data loss prevention (DLP) support: Currently, only retention labels can be used as a condition in DLP policies.</span></span>  <span data-ttu-id="c571e-111">Podpora popisků citlivosti v zásadách DLP ještě není k dispozici, ale pracujeme na tom.</span><span class="sxs-lookup"><span data-stu-id="c571e-111">Support for sensitivity labels in a DLP policy is not available yet but we're working on it.</span></span>

- <span data-ttu-id="c571e-112">Je-li povoleno šifrování na štítku s citlivostí, můžete zvolit jednu z těchto možnosti:</span><span class="sxs-lookup"><span data-stu-id="c571e-112">When encryption is enabled on a sensitivity label, you can choose either to:</span></span>
    - <span data-ttu-id="c571e-113">Přiřadit oprávnění nyní</span><span class="sxs-lookup"><span data-stu-id="c571e-113">Assign permissions now</span></span>
    - <span data-ttu-id="c571e-114">Dovolit uživatelům přiřazovat oprávnění</span><span class="sxs-lookup"><span data-stu-id="c571e-114">Let users assign permissions</span></span>


<span data-ttu-id="c571e-115">Další informace o možných problémech naleznete v tématu [známé problémy s popisky citlivosti](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span><span class="sxs-lookup"><span data-stu-id="c571e-115">For more information on possible issues, see [Known issues with sensitivity labels](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span></span>