---
title: Nastavení DKIM ve službách Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1388
ms.assetid: ''
ms.openlocfilehash: dd908db6a4bc1739b3c1cff059387034d67e093d
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666257"
---
# <a name="setup-dkim-in-office-365"></a><span data-ttu-id="04616-102">Nastavení DKIM ve službách Office 365</span><span class="sxs-lookup"><span data-stu-id="04616-102">Setup DKIM in Office 365</span></span>

<span data-ttu-id="04616-103">Úplné pokyny pro konfiguraci DKIM pro vlastní domény ve službách Office 365 jsou [zde](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="04616-103">The complete instructions for configuring DKIM for custom domains in Office 365 are [here](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

1. <span data-ttu-id="04616-104">Pro **každou** vlastní doménu je nutné vytvořit **dva** záznamy DKIM CNAME na hostitelské služby DNS vaší domény (obvykle registrátora domény).</span><span class="sxs-lookup"><span data-stu-id="04616-104">For **each** custom domain, you need to create **two** DKIM CNAME records at your domain's DNS hosting service (typically, the domain registrar).</span></span> <span data-ttu-id="04616-105">Například contoso.com a fourthcoffee.com vyžadují čtyři záznamy DKIM CNAME: dvě pro contoso.com a dvě pro fourthcoffee.com.</span><span class="sxs-lookup"><span data-stu-id="04616-105">For example, contoso.com and fourthcoffee.com require four DKIM CNAME records: two for contoso.com and two for fourthcoffee.com.</span></span>

   <span data-ttu-id="04616-106">Záznamy DKIM CNAME pro **každou** vlastní doménu pomocí následujících formátů:</span><span class="sxs-lookup"><span data-stu-id="04616-106">The DKIM CNAME records for **each** custom domain use the following formats:</span></span>

   - <span data-ttu-id="04616-107">**Název hostitele**:`selector1._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="04616-107">**Host name**: `selector1._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="04616-108">**Body na adresu nebo hodnotu**:`selector1-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="04616-108">**Points to address or value**: `selector1-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="04616-109">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="04616-109">**TTL**: 3600</span></span>

   - <span data-ttu-id="04616-110">**Název hostitele**:`selector2._domainkey.<CustomDomain>`</span><span class="sxs-lookup"><span data-stu-id="04616-110">**Host name**: `selector2._domainkey.<CustomDomain>`</span></span>

     <span data-ttu-id="04616-111">**Body na adresu nebo hodnotu**:`selector2-<DomainGUID>._domainkey.<InitialDomain>`</span><span class="sxs-lookup"><span data-stu-id="04616-111">**Points to address or value**: `selector2-<DomainGUID>._domainkey.<InitialDomain>`</span></span>

     <span data-ttu-id="04616-112">**TTL**: 3600</span><span class="sxs-lookup"><span data-stu-id="04616-112">**TTL**: 3600</span></span>

   <span data-ttu-id="04616-113">\<DomainGUID\> je text vlevo od `.mail.protection.outlook.com` ve vlastní záznam MX pro vlastní domény (například `contoso-com` pro doménu contoso.com).</span><span class="sxs-lookup"><span data-stu-id="04616-113">\<DomainGUID\> is the text to the left of `.mail.protection.outlook.com` in the customized MX record for the custom domain (for example, `contoso-com` for the domain contoso.com).</span></span> <span data-ttu-id="04616-114">\<InitialDomain\> je doména, který jste použili při registraci služeb Office 365 (například contoso.onmicrosoft.com).</span><span class="sxs-lookup"><span data-stu-id="04616-114">\<InitialDomain\> is the domain you used when you signed up for Office 365 (for example, contoso.onmicrosoft.com).</span></span>

2. <span data-ttu-id="04616-115">Po vytvoření záznamů CNAME pro vaší vlastní domény postupujte podle následujících pokynů:</span><span class="sxs-lookup"><span data-stu-id="04616-115">After you've created the CNAME records for your custom domains, complete the following instructions:</span></span>

   <span data-ttu-id="04616-116">na.</span><span class="sxs-lookup"><span data-stu-id="04616-116">a.</span></span> <span data-ttu-id="04616-117">[Přihlaste se k Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) pomocí svého účtu pracovní nebo školní účet.</span><span class="sxs-lookup"><span data-stu-id="04616-117">[Sign in to Office 365](https://support.office.microsoft.com/article/e9eb7d51-5430-4929-91ab-6157c5a050b4) with your work or school account.</span></span>

   <span data-ttu-id="04616-118">b.</span><span class="sxs-lookup"><span data-stu-id="04616-118">b.</span></span> <span data-ttu-id="04616-119">V levém horním rohu vyberte ikonu spouštěče aplikací a zvolte **Správce**.</span><span class="sxs-lookup"><span data-stu-id="04616-119">Select the app launcher icon in the upper-left and choose **Admin**.</span></span>

   <span data-ttu-id="04616-120">c.</span><span class="sxs-lookup"><span data-stu-id="04616-120">c.</span></span> <span data-ttu-id="04616-121">V levém navigačním **Admin** rozbalte a vyberte **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="04616-121">In the lower-left navigation, expand **Admin** and choose **Exchange**.</span></span>

   <span data-ttu-id="04616-122">d.</span><span class="sxs-lookup"><span data-stu-id="04616-122">d.</span></span> <span data-ttu-id="04616-123">Přejít na **ochranu** > **DKIM**.</span><span class="sxs-lookup"><span data-stu-id="04616-123">Go to **Protection** > **DKIM**.</span></span>

   <span data-ttu-id="04616-124">e.</span><span class="sxs-lookup"><span data-stu-id="04616-124">e.</span></span> <span data-ttu-id="04616-125">Vyberte doménu a pak zvolte **Povolit** **přihlašovací**zprávy pro tuto doménu s DKIM podpisy.</span><span class="sxs-lookup"><span data-stu-id="04616-125">Select the domain and then choose **Enable** for **Sign messages for this domain with DKIM signatures**.</span></span> <span data-ttu-id="04616-126">Tento krok opakujte pro každou vlastní doménu.</span><span class="sxs-lookup"><span data-stu-id="04616-126">Repeat this step for each custom domain.</span></span>
