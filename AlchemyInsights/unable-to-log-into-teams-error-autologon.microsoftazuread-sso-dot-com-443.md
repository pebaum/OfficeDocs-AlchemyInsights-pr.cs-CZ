---
title: Nelze se přihlásit k Teams kvůli chybě autologon.microsoftazuread-sso.com:443
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9001686"
- "3750"
ms.openlocfilehash: 77049153939989d1c63789adfec0b494d047a6e4
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931830"
---
# <a name="unable-to-log-into-teams-due-to-error-autologonmicrosoftazuread-sso-dot-com443"></a><span data-ttu-id="86d18-102">Nelze se přihlásit k Teams kvůli chybě autologon.microsoftazuread-sso dot com:443</span><span class="sxs-lookup"><span data-stu-id="86d18-102">Unable to log into Teams due to error autologon.microsoftazuread-sso dot com:443</span></span>

<span data-ttu-id="86d18-103">Pokud je v rámci ověřování O365 povolené bezproblémové jednotné přihlašování, je možné, že bude potřeba adresu URL autologon.microsoftazuread-sso.com přidat na intranetové weby.</span><span class="sxs-lookup"><span data-stu-id="86d18-103">If Seamless SSO is enabled as the O365 authentication, the URL "autologon.microsoftazuread-sso.com" may need to be added to Intranet Sites.</span></span>  <span data-ttu-id="86d18-104">Pokud jste ji už dříve přidali k důvěryhodným webům a používáte bezproblémové jednotné přihlašování, měla by být z důvěryhodných webů odebrána.</span><span class="sxs-lookup"><span data-stu-id="86d18-104">If it has previously been added to Trusted Sites  and Seamless SSO is in use, it should be removed from Trusted Sites.</span></span>

<span data-ttu-id="86d18-105">Podívejte se na [kontrolní seznam pro řešení potíží s bezproblémovým jednotným přihlašováním](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).</span><span class="sxs-lookup"><span data-stu-id="86d18-105">Please review the [Seamless SSO Troubleshooting Checklist](https://docs.microsoft.com/azure/active-directory/hybrid/tshoot-connect-sso#troubleshooting-checklist).</span></span>

<span data-ttu-id="86d18-106">Pokud chcete přidat adresu URL do seznamu intranetových webů, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="86d18-106">Follow these steps to add a URL to Intranet Sites list:</span></span>

1. <span data-ttu-id="86d18-107">Spusťte Internet Explorer kliknutím na tlačítko **Start**.</span><span class="sxs-lookup"><span data-stu-id="86d18-107">Open Internet Explorer by clicking the **Start** button.</span></span> <span data-ttu-id="86d18-108">Do vyhledávacího pole napište Internet Explorer a pak v seznamu výsledků klikněte na **Internet Explorer**.</span><span class="sxs-lookup"><span data-stu-id="86d18-108">In the search box, type Internet Explorer, and then, in the list of results, click **Internet Explorer**.</span></span>
2. <span data-ttu-id="86d18-109">Klikněte na **Nástroje** a pak na **Možnosti Internetu**.</span><span class="sxs-lookup"><span data-stu-id="86d18-109">Click **Tools**, and then click **Internet options**.</span></span>
3. <span data-ttu-id="86d18-110">Klikněte na kartu **Zabezpečení**.</span><span class="sxs-lookup"><span data-stu-id="86d18-110">Click the **Security** tab.</span></span>
4. <span data-ttu-id="86d18-111">Teď klikněte na **weby místního intranetu**, klikněte na tlačítko **weby** a pak na tlačítko **Upřesnit**.</span><span class="sxs-lookup"><span data-stu-id="86d18-111">Now click on **Local Intranet sites** and then click on the **sites** button and then **Advanced** button.</span></span>
5. <span data-ttu-id="86d18-112">Zadejte adresu URL webu a klikněte na **Přidat**.</span><span class="sxs-lookup"><span data-stu-id="86d18-112">Enter the Website URL and click **Add**.</span></span>
6. <span data-ttu-id="86d18-113">Po dokončení klikněte na **Zavřít**.</span><span class="sxs-lookup"><span data-stu-id="86d18-113">When you are finished, click **Close**.</span></span>

<span data-ttu-id="86d18-114">Další informace najdete v článku o [dokumentaci pro nasazení bezproblémového jednotného přihlašování k Office 365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (obsahuje proces založený na zásadách k přidání adresy URL k intranetovým webům v kroku 3).</span><span class="sxs-lookup"><span data-stu-id="86d18-114">For more information, see [Documentation for deploying Seamless SSO for O365](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-sso-quick-start) (includes Policy-based process to add a URL to Intranet Sites in Step 3).</span></span>
