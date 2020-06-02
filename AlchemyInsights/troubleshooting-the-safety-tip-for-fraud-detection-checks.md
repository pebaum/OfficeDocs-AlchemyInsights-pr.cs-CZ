---
title: Řešení bezpečnostního tipu pro kontroly odhalování podvodů
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: 74913492a086de688067d588e95dd87e6946743b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44504976"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="9f39e-102">Řešení bezpečnostního tipu pro kontroly odhalování podvodů</span><span class="sxs-lookup"><span data-stu-id="9f39e-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="9f39e-103">Pokud se vám zobrazuje bezpečnostní tip s nápisem "Odesílatel selhal v kontrolách zjišťování podvodů a nemusí být tím, kým se zdá být", odesílatel neprošel kontrolou ověřování DKIM nebo SPF.</span><span class="sxs-lookup"><span data-stu-id="9f39e-103">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks.</span></span> <span data-ttu-id="9f39e-104">Nejlepší způsob, jak to vyřešit, je pro odesílatele, aby se sami.</span><span class="sxs-lookup"><span data-stu-id="9f39e-104">The best method to resolve this is for the sender to authorize themselves.</span></span> <span data-ttu-id="9f39e-105">Pokud odesílatel odesílá vaším jménem, musíte je autorizovat přidáním IP adresy odesílatele do záznamu SPF.</span><span class="sxs-lookup"><span data-stu-id="9f39e-105">If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="9f39e-106">Další informace najdete [v tématu Řešení červeného (podezřelého) bezpečnostního tipu pro kontroly odhalování podvodů.](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/)</span><span class="sxs-lookup"><span data-stu-id="9f39e-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span>
  
<span data-ttu-id="9f39e-107">Zde jsou některé další odkazy, které mohou pomoci:</span><span class="sxs-lookup"><span data-stu-id="9f39e-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="9f39e-108">Jak společnost Microsoft používá rámec zásad odesílatele (SPF) k zabránění falšování identity</span><span class="sxs-lookup"><span data-stu-id="9f39e-108">How Microsoft uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-office-365-uses-spf-to-prevent-spoofing)

- [<span data-ttu-id="9f39e-109">Nastavení SPF, aby se zabránilo falšování identity</span><span class="sxs-lookup"><span data-stu-id="9f39e-109">Set up SPF to help prevent spoofing</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-spf-in-office-365-to-help-prevent-spoofing)
