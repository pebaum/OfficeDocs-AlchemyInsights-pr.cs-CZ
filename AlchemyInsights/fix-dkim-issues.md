---
title: Oprava problémů s instalací DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 8195b0e3fada6da033b2d95b1fc6600e7fa3341e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506767"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="d9a59-102">Oprava problémů s instalací DKIM</span><span class="sxs-lookup"><span data-stu-id="d9a59-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="d9a59-103">Pokud narazíte na problémy s povolením DKIM pro vaši vlastní doménu, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="d9a59-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="d9a59-104">Většina problémů s nastavením DKIM souvisí s nesprávnými záznamy DNS.</span><span class="sxs-lookup"><span data-stu-id="d9a59-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="d9a59-105">Ověřte, zda je záznam DKIM CNAME **(nikoli** záznam TXT) správně formátován.</span><span class="sxs-lookup"><span data-stu-id="d9a59-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="d9a59-106">Další informace naleznete v tomto [tématu](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span><span class="sxs-lookup"><span data-stu-id="d9a59-106">For more information, see this [topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email#steps-you-need-to-do-to-manually-set-up-dkim).</span></span>

- <span data-ttu-id="d9a59-107">Po vytvoření nebo aktualizaci záznamů SLUŽBY DKIM DNS v hostitelské službě DNS pro vaši doménu (obvykle váš registrátor domény) počkejte, až se záznamy DNS rozšíří.</span><span class="sxs-lookup"><span data-stu-id="d9a59-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="d9a59-108">Pokud nemůžete vytvořit záznamy DKIM DNS v Centru pro správu, můžete nahradit \<CustomDomain\> vlastní doménou (například contoso.com) a spustit tento příkaz v [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true` .</span><span class="sxs-lookup"><span data-stu-id="d9a59-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
