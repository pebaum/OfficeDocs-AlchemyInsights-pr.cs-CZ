---
title: Chyba při odesílání e-mailu blokováno SpamHaus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 2/23/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 7d6ad2667613ae948a4abcefafe8d91cf89d2418
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32402252"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="6547b-102">Chyba při odesílání e-mailu: klienta host blokovaných Spamhaus pomocí</span><span class="sxs-lookup"><span data-stu-id="6547b-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="6547b-103">Adresu IP, který zprávu odeslal, je na seznamu blokování [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245)vlastněné.</span><span class="sxs-lookup"><span data-stu-id="6547b-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="6547b-104">Hostují účty obsahovat důvody blokován nastavením Spamhaus ohrožení počítače sdílení veřejných adres IP a zásad poskytovatele služeb Internetu (ISP).</span><span class="sxs-lookup"><span data-stu-id="6547b-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="6547b-105">Jsou možné opravy:</span><span class="sxs-lookup"><span data-stu-id="6547b-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="6547b-106">Blokování příchozích zpráv kde ovládacího prvku zdrojového serveru e-mailu služeb Office 365 je třeba zjistit příčinu a odstranit blokování Spamhaus webu.</span><span class="sxs-lookup"><span data-stu-id="6547b-106">For blocked inbound messages to Office 365 where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>
    
- <span data-ttu-id="6547b-107">U blokovaných příchozích zpráv do služeb Office 365, pokud je zdrojová adresa IP patří někomu jinému musí odstranit blok z webu Spamhaus adresa vlastníka.</span><span class="sxs-lookup"><span data-stu-id="6547b-107">For blocked inbound messages to Office 365 where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="6547b-108">Pokud adresa IP je v seznamu zásad bloku (PBL), vlastník můžete přiřadit jinou statickou adresu IP nebo adresu odebrat z PBL.</span><span class="sxs-lookup"><span data-stu-id="6547b-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>
    
- <span data-ttu-id="6547b-109">Pro blokované odchozí zprávy z vaší domény služeb Office 365 můžete obdržet tuto chybu Pokud zprávy jsou směrovány prostřednictvím služby 3. strana.</span><span class="sxs-lookup"><span data-stu-id="6547b-109">For blocked outbound messages from your Office 365 domain, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="6547b-110">Vyhledávací nástroj WHOIS můžete použít k nalezení vlastníka blokované adresy IP.</span><span class="sxs-lookup"><span data-stu-id="6547b-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
    

