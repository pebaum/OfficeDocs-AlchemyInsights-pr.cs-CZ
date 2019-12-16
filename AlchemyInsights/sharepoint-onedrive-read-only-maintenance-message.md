---
title: Zpráva jen pro čtení pro zprávu o údržbě při pokusu o použití služby SharePoint nebo OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: 02cf1aa7abae365a3d317af9e785648d1c1517e1
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40051274"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a>Zpráva jen pro čtení pro zprávu o údržbě při pokusu o použití služby SharePoint nebo OneDrive

Při pokusu o použití služby SharePoint nebo OneDrive pro jeden z následujících scénářů se uživatelům může zobrazit zpráva **o údržbě jen pro čtení** . 

-   Plánovaná nebo aktivní aktivita údržby.  Vyhledejte je pomocí navigace do [centra zpráv](https://portal.office.com/adminportal/home#/messagecenter).
-   Vysoce prioritní, aktivní servisní incident, který se může objevovat. Vyhledejte všechny informační zpravodaje a incidenty přechodem na [stav služby](https://portal.office.com/adminportal/home#/servicehealth).
-   Malý scénář zotavení s automatickým uzdravením, který by mohl být způsoben událostmi, které by mohly trvat méně než 30 min. 
    
    U těchto menších obnovení není k dispozici žádné Centrum zpráv ani příspěvky na stav služby, ale měli byste se brzy vrátit k normálu.

Během několika málo případů jsme si byli velmi dobře vypozorovali, že jeden ze tří výše uvedených scénářů byl příčinou a služba byla obnovena, ale mezipaměť uživatelů prohlížeče nebyla vymazána.

Před přechodem na web se pokuste vymazat mezipaměť prohlížeče.

1. V prohlížeči Microsoft Edge klepněte na položku **Nastavení**a vyberte položku **Ochrana osobních údajů a zabezpečení**.
2. V části **procházení s jasnou**volbou vyberte **položku, kterou chcete vymazat**.
3. Vyberte **soubory cookie a uložená data webu**a vyberte možnost **Vymazat**.

>[!Note] 
> Tyto kroky se mohou lišit v případě použití jiných prohlížečů, jako je Mozilla Firefox nebo Google Chrome.

>[!Note] 
> Další možností je otevření webu služby SharePoint nebo funkce OneDrive v novém okně se službou InPrivate.