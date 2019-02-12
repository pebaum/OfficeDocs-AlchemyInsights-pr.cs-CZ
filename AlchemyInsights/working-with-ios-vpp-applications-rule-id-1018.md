---
title: Práce s iOS VPP aplikace pravidla Id 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 65b9a727171a7551068717f6327f15e1aa8e6bed
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29917489"
---
# <a name="working-with-ios-vpp-applications"></a>Práce s iOS aplikací VPP

Přečtěte si, [jak spravovat iOS apps zakoupili prostřednictvím programu objem nákupu s Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) získat informace o funkcích, omezení a opatření, která používají Apple objem nákupu programu a podporu v Microsoft Intune. 
  
 **Běžné problémy:** "Moji uživatelé jsou přiděleny aplikaci iOS VPP, ale instalace se nezdařila." 
  
- K tomu může dojít, pokud je použit jeden token VPP napříč více zprostředkovatelů správy mobilních zařízení. VPP tokeny z Apple lze použít pouze s jedním poskytovatelem. Pokud jste použili VPP token s více zprostředkovatelů, musí znovu odeslat token pro Intune.
    
- Instalace může také nezdaří, pokud celkový počet zařízení překročí počet licencí. Chcete-li zobrazit zprávu o využití licence, přejděte na **Intune Mobile apps** \> stránku **App licence** . Zjistěte, jak znovu získat licence používány, naleznete v [Toto čl.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
    

