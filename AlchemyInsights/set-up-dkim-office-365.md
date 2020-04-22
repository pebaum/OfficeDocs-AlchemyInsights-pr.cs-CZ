---
title: Nastavení DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: d23a816d4eef065f800eaee60829d57dc1e7177f
ms.sourcegitcommit: 6bf1d945b4fd6a1fe37d00c5ea99adea7eef9910
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/21/2020
ms.locfileid: "43645665"
---
# <a name="setup-dkim"></a><span data-ttu-id="949fb-102">Nastavení DKIM</span><span class="sxs-lookup"><span data-stu-id="949fb-102">Setup DKIM</span></span>

<span data-ttu-id="949fb-103">Úplné pokyny pro konfiguraci DKIM pro vlastní domény v Microsoft 365 jsou [zde](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="949fb-103">The complete instructions for configuring DKIM for custom domains in Microsoft 365 are [here](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

1. <span data-ttu-id="949fb-104">Pro **každou** vlastní doménu je třeba vytvořit **dva** záznamy DKIM CNAME v hostitelské službě DNS vaší domény (obvykle registrátor domény).</span><span class="sxs-lookup"><span data-stu-id="949fb-104">For **each** custom domain, you need to create **two** DKIM CNAME records at your domain's DNS hosting service (typically, the domain registrar).</span></span> <span data-ttu-id="949fb-105">Například contoso.com a fourthcoffee.com vyžadují čtyři záznamy DKIM CNAME: dva pro contoso.com a dva pro fourthcoffee.com.</span><span class="sxs-lookup"><span data-stu-id="949fb-105">For example, contoso.com and fourthcoffee.com require four DKIM CNAME records: two for contoso.com and two for fourthcoffee.com.</span></span>

   <span data-ttu-id="949fb-106">Záznamy DKIM CNAME pro **každou** vlastní doménu používají následující formáty:</span><span class="sxs-lookup"><span data-stu-id="949fb-106">The DKIM CNAME records for **each** custom domain use the following formats:</span></span>

   - <span data-ttu-id="949fb-107">**Název hostitele**:`selector1._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="949fb-107">**Host name**: `selector1._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="949fb-108">**Body na adresu nebo hodnotu**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="949fb-108">**Points to address or value**: `selector1-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="949fb-109">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="949fb-109">**TTL**: 3600</span></span>

   - <span data-ttu-id="949fb-110">**Název hostitele**:`selector2._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="949fb-110">**Host name**: `selector2._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="949fb-111">**Body na adresu nebo hodnotu**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="949fb-111">**Points to address or value**: `selector2-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="949fb-112">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="949fb-112">**TTL**: 3600</span></span>

   <span data-ttu-id="949fb-113">\<DomainGUID\> je text nalevo od `.mail.protection.outlook.com` v přizpůsobeném záznamu MX `contoso-com` pro vlastní doménu (například pro doménu contoso.com).</span><span class="sxs-lookup"><span data-stu-id="949fb-113">\<DomainGUID\> is the text to the left of `.mail.protection.outlook.com` in the customized MX record for the custom domain (for example, `contoso-com` for the domain contoso.com).</span></span> <span data-ttu-id="949fb-114">\<InitialDomain\> je doména, kterou jste použili při registraci do Microsoftu 365 (například contoso.onmicrosoft.com).</span><span class="sxs-lookup"><span data-stu-id="949fb-114">\<InitialDomain\> is the domain you used when you signed up for Microsoft 365 (for example, contoso.onmicrosoft.com).</span></span>

2. <span data-ttu-id="949fb-115">Po vytvoření záznamů CNAME pro vlastní domény postupujte podle následujících pokynů:</span><span class="sxs-lookup"><span data-stu-id="949fb-115">After you've created the CNAME records for your custom domains, complete the following instructions:</span></span>

   <span data-ttu-id="949fb-116">A.</span><span class="sxs-lookup"><span data-stu-id="949fb-116">a.</span></span> <span data-ttu-id="949fb-117">[Přihlaste se k Microsoftu 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomocí pracovního nebo školního účtu.</span><span class="sxs-lookup"><span data-stu-id="949fb-117">[sign in to Microsoft 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) with your work or school account.</span></span>

   <span data-ttu-id="949fb-118">B.</span><span class="sxs-lookup"><span data-stu-id="949fb-118">b.</span></span> <span data-ttu-id="949fb-119">V levém horním rohu vyberte ikonu spouštěče aplikací a zvolte **Správce**.</span><span class="sxs-lookup"><span data-stu-id="949fb-119">Select the app launcher icon in the upper-left and choose **Admin**.</span></span>

   <span data-ttu-id="949fb-120">C.</span><span class="sxs-lookup"><span data-stu-id="949fb-120">c.</span></span> <span data-ttu-id="949fb-121">V levém dolním navigačním panelu rozbalte **položku Správce** a zvolte **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="949fb-121">In the lower-left navigation, expand **Admin** and choose **Exchange**.</span></span>

   <span data-ttu-id="949fb-122">D.</span><span class="sxs-lookup"><span data-stu-id="949fb-122">d.</span></span> <span data-ttu-id="949fb-123">Přejděte na **ochranu** > **DKIM**.</span><span class="sxs-lookup"><span data-stu-id="949fb-123">Go to **Protection** > **DKIM**.</span></span>

   <span data-ttu-id="949fb-124">E.</span><span class="sxs-lookup"><span data-stu-id="949fb-124">e.</span></span> <span data-ttu-id="949fb-125">Vyberte doménu a pak zvolte **Povolit** pro **podepisování zpráv pro tuto doménu s podpisy DKIM**.</span><span class="sxs-lookup"><span data-stu-id="949fb-125">Select the domain and then choose **Enable** for **Sign messages for this domain with DKIM signatures**.</span></span> <span data-ttu-id="949fb-126">Tento krok opakujte pro každou vlastní doménu.</span><span class="sxs-lookup"><span data-stu-id="949fb-126">Repeat this step for each custom domain.</span></span>
