---
title: 1065 odmítání příznaku EOP odchozí IP adresy rangesMC146155
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 0def0a93c61ea762918f1c9e6edb2e9b04446851
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30777265"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="851a6-102">Odmítání příznaku rozsahů adres IP pro odchozí EOP</span><span class="sxs-lookup"><span data-stu-id="851a6-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="851a6-103">Zjistili jsme potenciální problém s organizaci (26. října 2018 není korigovaná) může porušit tok e-mailů na místní nebo externí cíle.</span><span class="sxs-lookup"><span data-stu-id="851a6-103">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations.</span></span> <span data-ttu-id="851a6-104">Které dříve oznámila zjednodušit řízení rozsah adres IP, jsme se konsoliduje rozsahy adres IP serveru Exchange Online ochrany (EOP), které slouží k odesílání a přijímání e-mailů mimo služeb Office 365.</span><span class="sxs-lookup"><span data-stu-id="851a6-104">As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365.</span></span> <span data-ttu-id="851a6-105">Naše analýza naznačuje, jeden nebo více externí emailových zdrojů nebo cílů, nakonfigurované v spojnice toku pošty nepřijali připojení IP adresu oblasti uvedeno [zde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="851a6-105">Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="851a6-106">Působit před 26. října zajistit, aby že tyto zdroje a cíle bude přijímat připojení z [publikované adresy EOP IP](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)a.</span><span class="sxs-lookup"><span data-stu-id="851a6-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="851a6-107">Další informace o této změně získáte, že zpráva Centrum účtuje, [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)nebo [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span><span class="sxs-lookup"><span data-stu-id="851a6-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>
  
 <span data-ttu-id="851a6-108">**Poznámka**: Pokud jste dříve používali IP nebo adresu URL publikování pomocí HTML, XML a RSS aktualizace koncového bodu, také měli byste přenést do nové webové služby pro automatizaci tyto typy aktualizací.</span><span class="sxs-lookup"><span data-stu-id="851a6-108">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates.</span></span> <span data-ttu-id="851a6-109">Další informace naleznete v tématu [kategorie koncového bodu služeb Office 365 a Office 365 IP adresa a adresa URL webové služby](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="851a6-109">For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
  

