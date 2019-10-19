---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: b2328ea85d3ff6ec722cc56d8a46395d8438f79c
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36739486"
---
# <a name="how-to-disable-external-groups"></a>Jak zakázat externí skupiny

Externí zasílání zpráv Yammer používá pravidla přenosu Exchange (ETRs), což je sada proaktivních kontrol, které zabraňují sdílení informací o společnosti. Chcete-li uživatelům zabránit ve vytváření externích skupin, je třeba nakonfigurovat pravidlo přenosu na serveru Exchange (ETR) a poté nakonfigurovat Yammer tak, aby používal pravidlo Transport Exchange k blokování externích zpráv.
  
Po vytvoření pravidla v centru pro správu serveru Exchange Online postupujte podle následujících kroků, abyste nastavili použití ETR v Yammer:
  
- Přihlaste se k Yammer jako ověřený správce a v **centru pro správu Yammer**přejděte na **obsah C a nastavení zabezpečení zabezpečení \> .**

- Ve skupinovém rámečku **externí zasílání zpráv**vyberte možnost **vynucovat v Yammer pravidla přenosu na serveru Exchange Online.**

- Zvolte **Uložit**.

Další informace naleznete v tématu [zakázání externího zasílání zpráv v síti Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).
  