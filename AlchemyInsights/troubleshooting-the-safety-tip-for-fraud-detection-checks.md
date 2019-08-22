---
title: Poradce při potížích bezpečnost tip pro detekci podvodů kontroly
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: 7ce8bcc7caefebf51fc8d9622367fd16405deef1
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36533156"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="86b66-102">Poradce při potížích bezpečnost tip pro detekci podvodů kontroly</span><span class="sxs-lookup"><span data-stu-id="86b66-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="86b66-103">Získání bezpečnostní tip, který říká "odesílatel nepodařilo naše kontroly detekce podvodů a který se zdá být nemusí být", pak odesílatel projdou kontrolami SPF nebo DKIM ověření se nezdařilo.</span><span class="sxs-lookup"><span data-stu-id="86b66-103">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks.</span></span> <span data-ttu-id="86b66-104">Nejlepším způsobem vyřešit je pro odesílatele ověřit sami.</span><span class="sxs-lookup"><span data-stu-id="86b66-104">The best method to resolve this is for the sender to authorize themselves.</span></span> <span data-ttu-id="86b66-105">Pokud odesílatel posílá vaším jménem, je třeba je povolit přidáním IP adresu odesílatele k záznamu SPF.</span><span class="sxs-lookup"><span data-stu-id="86b66-105">If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="86b66-106">Další informace naleznete v tématu [Poradce při potížích s červenou (podezřelé) bezpečnost tip pro detekci podvodů kontroluje](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="86b66-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span>
  
<span data-ttu-id="86b66-107">Zde jsou některé odkazy, které vám mohou pomoci:</span><span class="sxs-lookup"><span data-stu-id="86b66-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="86b66-108">Použití zásad framework odesílatele (PSPM) Chcete-li zabránit falšování služeb Office 365</span><span class="sxs-lookup"><span data-stu-id="86b66-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)

- <span data-ttu-id="86b66-109">[Nastavení specifikace SPF v Office 365 jako prevence falšování identity](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing).</span><span class="sxs-lookup"><span data-stu-id="86b66-109">[Set up SPF in Office 365 to help prevent spoofing](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)</span></span>
