---
title: Byl překročen denní limit e-mailu. Pracovního postupu je pozastavena.
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 7/25/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 802aba696da61be5f0a6c12072842cbc3cd96499
ms.sourcegitcommit: 407f6c1e82f1a0be5cf53301fbf03cd25dcbf0ee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/02/2019
ms.locfileid: "36059632"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a><span data-ttu-id="5d190-103">Byl překročen Limit denní e-mail.</span><span class="sxs-lookup"><span data-stu-id="5d190-103">Daily email Limit Exceeded.</span></span> <span data-ttu-id="5d190-104">Pracovního postupu je pozastavena.</span><span class="sxs-lookup"><span data-stu-id="5d190-104">Workflow is suspended.</span></span>

<span data-ttu-id="5d190-105">Tato chyba může obdržet v následujících situacích:</span><span class="sxs-lookup"><span data-stu-id="5d190-105">This error may be received in the following scenarios:</span></span>

- <span data-ttu-id="5d190-106">Máte pracovní postup služby SharePoint Online, který používá SharePoint 2010 nebo SharePoint 2013 typ platformy pracovního postupu.</span><span class="sxs-lookup"><span data-stu-id="5d190-106">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>
- <span data-ttu-id="5d190-107">Pracovní postup je nakonfigurován pro vlastní e-mailové zprávě odeslat více než 200 uživatelů, více než 10 000 příjemců za den, nebo více než 30 zpráv za minutu.</span><span class="sxs-lookup"><span data-stu-id="5d190-107">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>
- <span data-ttu-id="5d190-108">Při spuštění pracovního postupu není odeslána e-mailové zprávy a zaznamenat následující chování:</span><span class="sxs-lookup"><span data-stu-id="5d190-108">When you run the workflow, the email message isn't sent, and you notice the following behavior:</span></span>
    - <span data-ttu-id="5d190-109">Pomocí typ platformy SharePoint 2013 pracovního postupu přejděte na stránku **Stav pracovního postupu** .</span><span class="sxs-lookup"><span data-stu-id="5d190-109">For a workflow using the SharePoint 2013 platform type, you browse to the **Workflow Status** page.</span></span> <span data-ttu-id="5d190-110">Na stránce Stav pracovního postupu **Vnitřní stav** nastaven na **spuštěno**a zobrazí bublinu informace **nelze odeslat příjemci**.</span><span class="sxs-lookup"><span data-stu-id="5d190-110">On the Workflow Status page, the **Internal Status** is set to **Started**, and the information balloon displays **Unable to send to a recipient**.</span></span>

<span data-ttu-id="5d190-111">Chcete-li tento problém vyřešit, nakonfigurujte pracovní postup odeslání e-mailové zprávy bez překročení [limitů Exchange Online odesílatele](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span><span class="sxs-lookup"><span data-stu-id="5d190-111">To work around this issue, configure your workflow to send email messages without exceeding the [Exchange Online sender limits](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits).</span></span> <span data-ttu-id="5d190-112">Například použití pozastavit v pracovním postupu, odešlete na skupinu služeb Office 365, distribuční skupina nebo skupina zabezpečení povolena poštovní nebo méně než 200 příjemcům najednou odeslat zprávu.</span><span class="sxs-lookup"><span data-stu-id="5d190-112">For example, use a pause in the workflow, send the email to an Office 365 group, a distribution group or mail enabled security group, or send the message to fewer than 200 recipients at a time.</span></span>


<span data-ttu-id="5d190-113">Další informace naleznete v následujícím [článku](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span><span class="sxs-lookup"><span data-stu-id="5d190-113">For more information, see the following [article](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).</span></span>

## <a name="related-topics"></a><span data-ttu-id="5d190-114">Související témata</span><span class="sxs-lookup"><span data-stu-id="5d190-114">Related topics</span></span>
- [<span data-ttu-id="5d190-115">Vytvoření toku</span><span class="sxs-lookup"><span data-stu-id="5d190-115">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="5d190-116">SharePoint a toku</span><span class="sxs-lookup"><span data-stu-id="5d190-116">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 