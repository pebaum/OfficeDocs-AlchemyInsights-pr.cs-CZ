---
title: Řešení problémů s nastavením DKIM
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
ms.openlocfilehash: d725eb0d46dcbf1b5b6d77ca9f59fcafa5298bf1
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43717555"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="0195b-102">Řešení problémů s nastavením DKIM</span><span class="sxs-lookup"><span data-stu-id="0195b-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="0195b-103">Pokud narazíte na problémy s povolením DKIM pro vlastní doménu, použijte následující kroky:</span><span class="sxs-lookup"><span data-stu-id="0195b-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="0195b-104">Většina problémů s nastavením DKIM souvisí s nesprávnými záznamy DNS.</span><span class="sxs-lookup"><span data-stu-id="0195b-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="0195b-105">Ověřte, zda je záznam DKIM CNAME **(nikoli** záznam TXT) správně formátován.</span><span class="sxs-lookup"><span data-stu-id="0195b-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="0195b-106">Další informace naleznete v tomto [tématu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="0195b-106">For more information, see this [topic](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

- <span data-ttu-id="0195b-107">Po vytvoření nebo aktualizaci záznamů DKIM DNS v hostitelské službě DNS pro vaši doménu (obvykle doménového registrátora) počkejte, až se záznamy DNS rozšíří.</span><span class="sxs-lookup"><span data-stu-id="0195b-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="0195b-108">Pokud nemůžete vytvořit záznamy DKIM DNS v Centru pro \<správu, můžete nahradit vlastní doménu\> vlastní doménou (například contoso.com) a spustit tento příkaz v Exchange Online [PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span><span class="sxs-lookup"><span data-stu-id="0195b-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
