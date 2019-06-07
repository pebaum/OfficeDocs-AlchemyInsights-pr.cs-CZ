---
title: Opravit problémy s instalací DKIM
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1389
ms.assetid: ''
ms.openlocfilehash: 4d6dadbcbf71fe6e9ea56d6a82a7d8ababdd38ef
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34764933"
---
# <a name="fix-dkim-setup-issues"></a><span data-ttu-id="a7d5e-102">Opravit problémy s instalací DKIM</span><span class="sxs-lookup"><span data-stu-id="a7d5e-102">Fix DKIM setup issues</span></span>

<span data-ttu-id="a7d5e-103">Pokud máte problémy s vaší vlastní domény povolení DKIM, použijte následující kroky:</span><span class="sxs-lookup"><span data-stu-id="a7d5e-103">If you experience issues enabling DKIM for your custom domain, use the following steps:</span></span>

- <span data-ttu-id="a7d5e-104">Většinu potíží při instalaci DKIM souvisejí nesprávné záznamy DNS.</span><span class="sxs-lookup"><span data-stu-id="a7d5e-104">Most DKIM setup issues are related to incorrect DNS records.</span></span> <span data-ttu-id="a7d5e-105">Ověřte, zda že záznam DKIM CNAME (**není** záznam TXT) je správně formátován.</span><span class="sxs-lookup"><span data-stu-id="a7d5e-105">Verify the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="a7d5e-106">Další informace najdete v tomto [tématu](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="a7d5e-106">For more information, see this [topic](https://docs.microsoft.com/office365/SecurityCompliance/use-dkim-to-validate-outbound-email#what-you-need-to-do-to-manually-set-up-dkim-in-office-365).</span></span>

- <span data-ttu-id="a7d5e-107">Můžete vytvořit nebo aktualizovat své záznamy DKIM DNS na DNS hostitelem vaší domény (obvykle váš Registrátor domény), DNS záznamy k šíření čekat.</span><span class="sxs-lookup"><span data-stu-id="a7d5e-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain (typically, your domain registrar), wait for the DNS records to propagate.</span></span>

- <span data-ttu-id="a7d5e-108">Pokud záznamy DKIM DNS nelze vytvořit ve středisku pro správce, můžete nahradit \<CustomDomain\> s vaší vlastní domény (například contoso.com) a spusťte tento příkaz v [Prostředí Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span><span class="sxs-lookup"><span data-stu-id="a7d5e-108">If you can't create the DKIM DNS records in the admin center, you can replace \<CustomDomain\> with your custom domain (for example, contoso.com) and run this command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell): `New-DkimSigningConfig -DomainName <CustomDomain> -Enabled $true`.</span></span>
