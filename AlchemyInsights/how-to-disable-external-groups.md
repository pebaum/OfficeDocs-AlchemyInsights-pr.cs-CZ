---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 2159feb4aa3999072de57d76790a2959c7355976
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720761"
---
# <a name="how-to-disable-external-groups"></a>Jak zakázat externí skupiny

Yammer externí zasílání zpráv platí Exchange Transport Rules (ETRs), sada proaktivních ovládacích prvků, aby se zabránilo sdílení informací o společnosti. Chcete-li uživatelům zabránit ve vytváření externích skupin, je třeba nakonfigurovat pravidlo přenosu serveru Exchange (ETR) a potom nakonfigurovat Yammer tak, aby používal pravidlo přenosu exchange k blokování externího zasílání zpráv.
  
Po vytvoření pravidla v Centru pro správu Exchange Online nastavte eTR takto, aby se použilo v Yammeru:
  
- Přihlaste se k Yammeru jako ověřený správce a v **Centru pro správu Yammeru**přejděte na **Nastavení obsahu a zabezpečení \> C.**

- V části **Externí zasílání zpráv**vyberte v **Yammeru vynutit pravidla přenosu Exchange online (ETRs).**

- Zvolte **Uložit**.

Další informace naleznete [v tématu Zakázání externích zpráv v síti Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).
  