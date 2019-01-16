---
title: Práce s iOS VPP aplikace pravidla Id 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 5bcfb6dd7222bd102ff2620c19bfb943e7bd9591
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28282021"
---
# <a name="working-with-ios-vpp-applications"></a>Práce s iOS aplikací VPP

Přečtěte si, [jak spravovat iOS apps zakoupili prostřednictvím programu objem nákupu s Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) získat informace o funkcích, omezení a opatření, která používají Apple objem nákupu programu a podporu v Microsoft Intune. 
  
 **Běžné problémy:** "Moji uživatelé jsou přiděleny aplikaci iOS VPP, ale instalace se nezdařila." 
  
- K tomu může dojít, pokud je použit jeden token VPP napříč více zprostředkovatelů správy mobilních zařízení. VPP tokeny z Apple lze použít pouze s jedním poskytovatelem. Pokud jste použili VPP token s více zprostředkovatelů, musí znovu odeslat token pro Intune.
    
- Instalace může také nezdaří, pokud celkový počet zařízení překročí počet licencí. Chcete-li zobrazit zprávu o využití licence, přejděte na **Intune Mobile apps** \> stránku **App licence** . Zjistěte, jak znovu získat licence používány, naleznete v [Toto čl.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

