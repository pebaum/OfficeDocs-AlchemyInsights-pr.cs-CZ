---
title: Sledování podmíněného přístupu
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 756c5e98ed3e9cedd0152b5747ea6bf1ed31778e
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32418462"
---
# <a name="monitoring-conditional-access"></a>Sledování podmíněného přístupu

Cílené s podmíněným přístupem zobrazí e-mailové oznámení v případě, že nesplňují požadavky vaší organizace přístup. Chcete-li vyřešit, doporučujeme jeden nebo více z následujících řešení:
  
- Pokud zařízení se předpokládá, že chcete být zaregistrováni, radit uživatelům přejít na aplikace portálu společnosti a ověřte, že se zobrazí v portálu společnosti. Pokud tomu tak není, uživatel by měl zapsat zařízení.
    
- Na portálu Azure přejděte na **Intune \> souladu zařízení**. V části **Sledování** klepněte na **shodu zařízení**. Zobrazení sestavy shody zařízení k ověření uživatele zařízení označeno jako kompatibilní. 
    
- Na portálu Azure přejděte na **Intune \> souladu zařízení**. Ve skupinovém rámečku **Správa**klepněte na položku **zásady**. V seznamu zásad dodržování předpisů ověřte, že je přiřazen profil uživatele zařízení. Pokud je přiřazen žádný profil, nesmí být schopni ověřit stav shody zařízení Intune. 
    
- Úprava přiřazení podmíněného přístupu uživatele.
    
1. Na portálu Azure přejděte na **Intune \> podmíněného přístupu \> zásady**
    
2. Ze seznamu vyberte zásadu
    
3. Klepněte na tlačítko **Uživatelé a skupiny**
    
4. Cíl politiky na někoho, přidejte je do seznamu **Zahrnout** . Chcete-li zajistit, že osoba je vynechán ze zásad, přidáte je do seznamu **vyloučení** . 
    
Další: [jak zařízení podmíněného přístupu Monitor](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)
  

