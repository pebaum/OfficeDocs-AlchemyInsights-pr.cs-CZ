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
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a>Vyřazení rozsahů odchozích IP adres EOP

Zjistili jsme potenciální problém s vaší organizací, který (pokud nebude opraven do 26. října 2018) může přerušit tok pošty do místních nebo externích cílů. Jak již bylo sděleno, pro zjednodušení správy rozsahu IP adres, konsolidujeme rozsahy IP adres Exchange Online Protection (EOP), které se používají k odesílání a přijímání e-mailů mimo Microsoft 365. Naše analýza ukazuje, že jeden nebo více externích zdrojů e-mailů nebo cílů, které jste nakonfigurovali v konektorech toku pošty, nepřijímá připojení z rozsahů IP adres, které jsou [zde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)zobrazeny .

Zákon do 26.října zajistit tyto zdroje a cíle budou přijímat spojení do a ze všech [publikovaných EOP IP adresy](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Další informace o této změně naleznete v tématu Message Center příspěvky [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), nebo [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).

**Poznámka:** Pokud jste dříve používali publikování IP nebo URL přes HTML, XML a RSS pro aktualizace koncového bodu, měli byste také migrovat na nové webové služby pro automatizaci těchto typů aktualizací. Další informace naleznete v [kategoriích koncových bodů společnosti Microsoft 365 a webové službě IP adresy a adresy URL společnosti Microsoft 365](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).
