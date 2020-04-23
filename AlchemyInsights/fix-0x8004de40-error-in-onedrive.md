---
title: Oprava chyby 0x8004de40 na OneDrivu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 5da4271f242597b195ef61d553fd4a2ffb313025
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716021"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Oprava chyby 0x8004de40 na OneDrivu

Pokud se na OneDrivu zobrazí chyba 0x8004de40:

- Restartujte postižený počítač při připojení k doméně Acitve Directory.
- Pokud restartování problém nevyřeší, odpojte se a znovu se připojte k zařízení z Azure AD. 

**Poznámka:** Při provádění těchto kroků byste měli být v podnikové síti. Tyto kroky neprovádějte, pokud se nemůžete připojit k podnikové infrastruktuře (například na cestách). 

- Otevřete příkazový řádek se zvýšenými oprávněními. 
- Chcete-li otevřít příkazový řádek se zvýšenými oprávněními, klepněte na tlačítko - **Spustit**, klepněte pravým tlačítkem myši na **příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.
- Zadejte *dsregcmd /leave* a stiskněte **enter**.
- Po dokončení zadejte *dsregcmd /join* a stiskněte **Enter**.
- Po dokončení zavřete příkazový řádek.
- Restartujte počítač a přihlaste se k OneDrivu.