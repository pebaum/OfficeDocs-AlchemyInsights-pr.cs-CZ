---
title: 618 Zásady sdílení kalendáře
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/26/2020
ms.locfileid: "44372992"
---
# <a name="policy-error-when-sharing-a-calendar"></a><span data-ttu-id="ef7ea-102">Chyba zásad při sdílení kalendáře</span><span class="sxs-lookup"><span data-stu-id="ef7ea-102">Policy error when sharing a calendar</span></span>

1. <span data-ttu-id="ef7ea-103">Proveďte jednu z následujících akcí podle vaší situace:</span><span class="sxs-lookup"><span data-stu-id="ef7ea-103">Do one of the following, as appropriate for your situation:</span></span>
    - <span data-ttu-id="ef7ea-104">Připojte se k Exchange Online pomocí vzdáleného prostředí PowerShell.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-104">Connect to Exchange Online by using Remote PowerShell.</span></span> <span data-ttu-id="ef7ea-105">Další informace naleznete [v tématu Připojení k Exchange Online pomocí vzdáleného prostředí PowerShell](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="ef7ea-105">For more information, see [Connect to Exchange Online using Remote PowerShell](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span></span>
    - <span data-ttu-id="ef7ea-106">Na místním serveru otevřete prostředí Exchange Management Shell.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-106">On the on-premises server, open the Exchange Management Shell.</span></span>
2. <span data-ttu-id="ef7ea-107">Určete zásady sdílení, které jsou přiřazeny uživateli.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-107">Determine the sharing policy that's assigned to the user.</span></span> <span data-ttu-id="ef7ea-108">Chcete-li to provést, spusťte následující příkaz a poznamenejte si vrácenou zásadu:</span><span class="sxs-lookup"><span data-stu-id="ef7ea-108">To do this, run the following command and note the policy returned:</span></span>

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. <span data-ttu-id="ef7ea-109">Aktualizujte zásady sdílení pro uživatele.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-109">Update the sharing policy for the user.</span></span> <span data-ttu-id="ef7ea-110">Uděláte to takto:</span><span class="sxs-lookup"><span data-stu-id="ef7ea-110">To do this, follow these steps:</span></span>
    - <span data-ttu-id="ef7ea-111">Otevřete Centrum pro správu Exchange.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-111">Open the Exchange admin center.</span></span>
    - <span data-ttu-id="ef7ea-112">Klikněte na **Organizace**a potom poklikejte na zásadu přiřazenou uživateli v části **Individuální sdílení**.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-112">Click **Organization**, and then double-click the policy that's assigned to the user under **Individual Sharing**.</span></span> <span data-ttu-id="ef7ea-113">Toto je zásada, která byla vrácena v kroku 2.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-113">This is the policy that was returned in step 2.</span></span>
    - <span data-ttu-id="ef7ea-114">Na stránce Pravidlo sdílení vyberte úroveň sdílení kalendáře, kterou chcete povolit, v části **Určit informace, které chcete sdílet**; klepněte na **tlačítko Uložit**.</span><span class="sxs-lookup"><span data-stu-id="ef7ea-114">On the Sharing Rule page, select the calendar sharing level that you want to allow under **Specify what information you want to share**; click **Save**.</span></span>

<span data-ttu-id="ef7ea-115">Další informace naleznete v [tématu: "Zásady neumožňují udělení oprávnění na této úrovni jednomu nebo více příjemcům" při pokusu uživatele o sdílení kalendáře](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span><span class="sxs-lookup"><span data-stu-id="ef7ea-115">For more information see: ["Policy does not allow granting permissions at this level to one or more of the recipient(s)" error when user tries to share calendar](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span></span>
