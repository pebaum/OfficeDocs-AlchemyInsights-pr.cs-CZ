---
title: Dynamics 365-chybné zobrazení řídicího panelu v Dynamics 365 sjednocené rozhraní
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 3d7258bdd7366f679b048e93926ab7dfe0b956d9
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36528544"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a>Chybné zobrazení řídicího panelu ve sjednoceném rozhraní Dynamics 365

Existuje několik důvodů, proč se může zobrazit jiný řídicí panel než ten, který očekáváte:

## <a name="the-user-has-set-a-user-default-dashboard"></a>Uživatel nastavil výchozí řídicí panel uživatele. 

Obvykle lze určit, že výchozí řídicí panel uživatele je nastaven v případě, že se v příkazovém řádku řídicího panelu nezobrazí tlačítko **nastavit jako výchozí** . Výchozí řídicí panel uživatele přepíše všechny ostatní výchozí řídicí panely, a to i v případě, že výchozí řídicí panel uživatele není v aktuální aplikaci.

Chcete-li zrušit nastavení výchozího řídicího panelu, použijte následující zástupné řešení.

1. Vytvoří nový osobní řídicí panel.

2. Nastaví nový řídicí panel jako výchozí uživatel.

3. Odstraňte tento řídicí panel.

## <a name="the-dashboard-is-set-in-the-sitemap"></a>Řídicí panel je nastaven v mapě webu

Můžete nastavit výchozí řídicí panel organizace výběrem řídicího panelu a zvolením možnosti nastavit jako výchozí v části vlastní nastavení systému. Avšak řídicí panel definovaný v Návrháři mapy webu bude mít přednost před tímto řídicím panelem, pokud k němu má přístup uživatel.

Chcete-li, aby uživatelé viděli řídicí panel, který jste nastavili jako výchozí nastavení organizace, můžete buď:

* Nastavit tento řídicí panel v mapě webu

* Odebrání přístupu k řídicím panelům definovaným v mapě webu pro tyto uživatele
