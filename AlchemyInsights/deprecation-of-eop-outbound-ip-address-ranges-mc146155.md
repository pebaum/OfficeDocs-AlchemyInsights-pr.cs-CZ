---
title: 1065 Vyřazení rozsahů odchozích IP adres EOPMC146155
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: f4854c32d970d84f3a0664a9e384dc6e3cd0bfa7
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704590"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="47878-102">Vyřazení rozsahů odchozích IP adres EOP</span><span class="sxs-lookup"><span data-stu-id="47878-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="47878-103">Zjistili jsme potenciální problém s vaší organizací, který (pokud nebude opraven do 26. října 2018) může přerušit tok pošty do místních nebo externích cílů.</span><span class="sxs-lookup"><span data-stu-id="47878-103">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations.</span></span> <span data-ttu-id="47878-104">Jak již bylo sděleno, pro zjednodušení správy rozsahu IP adres, konsolidujeme rozsahy IP adres Exchange Online Protection (EOP), které se používají k odesílání a přijímání e-mailů mimo Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="47878-104">As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Microsoft 365.</span></span> <span data-ttu-id="47878-105">Naše analýza ukazuje, že jeden nebo více externích zdrojů e-mailů nebo cílů, které jste nakonfigurovali v konektorech toku pošty, nepřijímá připojení z rozsahů IP adres, které jsou [zde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)zobrazeny .</span><span class="sxs-lookup"><span data-stu-id="47878-105">Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

<span data-ttu-id="47878-106">Zákon do 26.října zajistit tyto zdroje a cíle budou přijímat spojení do a ze všech [publikovaných EOP IP adresy](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="47878-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

<span data-ttu-id="47878-107">Další informace o této změně naleznete v tématu Message Center příspěvky [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), nebo [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span><span class="sxs-lookup"><span data-stu-id="47878-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>

<span data-ttu-id="47878-108">**Poznámka:** Pokud jste dříve používali publikování IP nebo URL přes HTML, XML a RSS pro aktualizace koncového bodu, měli byste také migrovat na nové webové služby pro automatizaci těchto typů aktualizací.</span><span class="sxs-lookup"><span data-stu-id="47878-108">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates.</span></span> <span data-ttu-id="47878-109">Další informace naleznete v [kategoriích koncových bodů společnosti Microsoft 365 a webové službě IP adresy a adresy URL společnosti Microsoft 365](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="47878-109">For more information, see [Microsoft 365 endpoint categories and Microsoft 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
