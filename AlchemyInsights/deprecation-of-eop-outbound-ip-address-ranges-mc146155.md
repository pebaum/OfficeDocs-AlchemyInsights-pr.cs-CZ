---
title: 1065 odmítání příznaku EOP odchozí IP adresy rangesMC146155
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 9860845dea444847833d4c5cd01d49ea93473778
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/07/2019
ms.locfileid: "34752948"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a>Odmítání příznaku rozsahů adres IP pro odchozí EOP

Zjistili jsme potenciální problém s organizaci (26. října 2018 není korigovaná) může porušit tok e-mailů na místní nebo externí cíle. Které dříve oznámila zjednodušit řízení rozsah adres IP, jsme se konsoliduje rozsahy adres IP serveru Exchange Online ochrany (EOP), které slouží k odesílání a přijímání e-mailů mimo služeb Office 365. Naše analýza naznačuje, jeden nebo více externí emailových zdrojů nebo cílů, nakonfigurované v spojnice toku pošty nepřijali připojení IP adresu oblasti uvedeno [zde](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Působit před 26. října zajistit, aby že tyto zdroje a cíle bude přijímat připojení z [publikované adresy EOP IP](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)a.

Další informace o této změně získáte, že zpráva Centrum účtuje, [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)nebo [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).

**Poznámka**: Pokud jste dříve používali IP nebo adresu URL publikování pomocí HTML, XML a RSS aktualizace koncového bodu, také měli byste přenést do nové webové služby pro automatizaci tyto typy aktualizací. Další informace naleznete v tématu [kategorie koncového bodu služeb Office 365 a Office 365 IP adresa a adresa URL webové služby](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).
