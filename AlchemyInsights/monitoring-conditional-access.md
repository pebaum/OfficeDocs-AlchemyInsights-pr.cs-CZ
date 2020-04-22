---
title: Monitorování podmíněného přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 8b76d58791408037b5704b421d7afa166e3ea0be
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713711"
---
# <a name="monitoring-conditional-access-for-exchange"></a>Monitorování podmíněného přístupu pro exchange

Uživatelé cílení s podmíněným přístupem obdrží e-mail s oznámením, pokud nesplňují požadavky na přístup vaší organizace. Chcete-li vyřešit, doporučujeme jeden nebo více z následujících řešení:
  
- Pokud se předpokládá, že zařízení je zaregistrované, řekněte uživateli, aby přešel do aplikace Portál společnosti a ověřil, že se zobrazuje na portálu společnosti. Pokud tomu tak není, uživatel by měl zaregistrovat zařízení.
    
- Na webu Azure Portal přejděte na **dodržování předpisů pro zařízení Intune \> **. V části **Monitor** klikněte na **Kompatibilita zařízení**. Chcete-li ověřit, zda je zařízení uživatele označeno jako vyhovující, zobrazte zprávu o dodržování předpisů zařízení. 
    
- Na webu Azure Portal přejděte na **dodržování předpisů pro zařízení Intune \> **. V části **Manage**klikněte na **Zásady**. V seznamu zásad dodržování předpisů ověřte, zda je k zařízení uživatele přiřazen profil. Pokud není přiřazen žádný profil, Intune nebude moct potvrdit stav kompatibility zařízení. 
    
- Upravte přiřazení podmíněného přístupu uživatele.
    
1. Na webu Azure Portal přejděte na **Zásady podmíněného \> přístupu \> Intune**
    
2. Výběr zásadze ze seznamu
    
3. Klikněte na **Uživatelé a skupiny.**
    
4. Chcete-li na někoho cílit určitou zásadu, přidejte ji do seznamu **Zahrnout.** Chcete-li zajistit, aby byla osoba ze zásad vynechána, přidejte ji do seznamu **Vyloučit.** 
    
Přečtěte si více: [Jak monitorovat zařízení podmíněného přístupu](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)
  

