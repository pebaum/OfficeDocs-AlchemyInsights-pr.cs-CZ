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
ms.openlocfilehash: 98627edcd2b685673dda8a8a18821eddf9b64bc1
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32391202"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="8ea65-102">Poradce při potížích bezpečnost tip pro detekci podvodů kontroly</span><span class="sxs-lookup"><span data-stu-id="8ea65-102">Troubleshooting the safety tip for fraud detection checks</span></span>



<span data-ttu-id="8ea65-103">Získání bezpečnostní tip, který říká "odesílatel nepodařilo naše kontroly detekce podvodů a který se zdá být nemusí být", pak odesílatel projdou kontrolami SPF nebo DKIM ověření se nezdařilo.</span><span class="sxs-lookup"><span data-stu-id="8ea65-103">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks.</span></span> <span data-ttu-id="8ea65-104">Nejlepším způsobem vyřešit je pro odesílatele ověřit sami.</span><span class="sxs-lookup"><span data-stu-id="8ea65-104">The best method to resolve this is for the sender to authorize themselves.</span></span> <span data-ttu-id="8ea65-105">Pokud odesílatel posílá vaším jménem, je třeba je povolit přidáním IP adresu odesílatele k záznamu SPF.</span><span class="sxs-lookup"><span data-stu-id="8ea65-105">If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="8ea65-106">Další informace naleznete v tématu [Poradce při potížích s červenou (podezřelé) bezpečnost tip pro detekci podvodů kontroluje](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="8ea65-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="8ea65-107">Zde jsou některé odkazy, které vám mohou pomoci:</span><span class="sxs-lookup"><span data-stu-id="8ea65-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="8ea65-108">Použití zásad framework odesílatele (PSPM) Chcete-li zabránit falšování služeb Office 365</span><span class="sxs-lookup"><span data-stu-id="8ea65-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- <span data-ttu-id="8ea65-109">[Nastavení specifikace SPF v Office 365 jako prevence falšování identity](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing).</span><span class="sxs-lookup"><span data-stu-id="8ea65-109">[Set up SPF in Office 365 to help prevent spoofing](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)</span></span>
    

