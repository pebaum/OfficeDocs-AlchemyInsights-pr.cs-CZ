---
title: Při odesílání e-mailů blokovaných spamem došlo k chybě.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 3ff4f7a155fe74f5b42a1bd43e67ef0a751d7fbd
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714251"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="0ca4d-102">Při odesílání e-mailů došlo k chybě: Hostitel klienta byl zablokován pomocí spamhausu</span><span class="sxs-lookup"><span data-stu-id="0ca4d-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="0ca4d-103">IP adresa, která zprávu odeslala, je na seznamu blokování vlastněném [společností Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span><span class="sxs-lookup"><span data-stu-id="0ca4d-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="0ca4d-104">Mezi důvody, proč spamhaus blokuje, patří kompromitované účty, ohrožené počítače sdílející veřejnou IP adresu a zásady poskytovatele internetových služeb (ISP).</span><span class="sxs-lookup"><span data-stu-id="0ca4d-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="0ca4d-105">Možné opravy jsou:</span><span class="sxs-lookup"><span data-stu-id="0ca4d-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="0ca4d-106">U blokovaných příchozích zpráv, kde ovládáte zdrojový e-mailový server, je třeba určit příčinu a odstranit blok z webu Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="0ca4d-106">For blocked inbound messages where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="0ca4d-107">U blokovaných příchozích zpráv, u kterých zdrojová IP adresa patří někomu jinému, musí vlastník adresy odstranit blok z webu Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="0ca4d-107">For blocked inbound messages where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="0ca4d-108">Pokud je adresa IP v seznamu blokování zásad (PBL), může vlastník přiřadit jinou statickou adresu IP nebo adresu z PBL odebrat.</span><span class="sxs-lookup"><span data-stu-id="0ca4d-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="0ca4d-109">U blokovaných odchozích zpráv z vaší domény připojené k Microsoftu se tato chyba zobrazí, pokud jsou zprávy směrovány prostřednictvím služby třetí strany.</span><span class="sxs-lookup"><span data-stu-id="0ca4d-109">For blocked outbound messages from your domain connected to Microsoft, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="0ca4d-110">Pomocí vyhledávacího nástroje WHOIS můžete najít vlastníka blokované adresy IP.</span><span class="sxs-lookup"><span data-stu-id="0ca4d-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>
