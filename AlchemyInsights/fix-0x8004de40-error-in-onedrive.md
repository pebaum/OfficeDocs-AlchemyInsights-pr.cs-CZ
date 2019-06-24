---
title: Opravte chyby 0x8004de40 v OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 2256fb66cb7a4e2adcff9fda16a80c87e2997f0c
ms.sourcegitcommit: 8f6a1be929b275faa295ba8aeeae17898a47c3b0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/21/2019
ms.locfileid: "35133970"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Opravte chyby 0x8004de40 v OneDrive

Pokud se zobrazí chybová 0x8004de40 s OneDrive:

- Restartujte ohrožený počítač během připojení k vaší doméně adresáře aktivovat.
- Pokud restartování počítače neodstraní problém, odebrat a znovu připojit zařízení z Azure AD. 

**Poznámka**: při provádění těchto kroků byste měli být v podnikové síti. Není provedení těchto kroků, pokud nejste schopni se připojit k vaší podnikové infrastruktury (např. při cestování). 

- Otevřete příkazový řádek se zvýšenými oprávněními. 
- Chcete-li otevřít okno příkazového řádku se zvýšenými oprávněními, klepněte na tlačítko - **Start**, klepněte pravým tlačítkem myši **Příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.
- Zadejte *dsregcmd /leave* a stiskněte klávesu **Enter**.
- Po dokončení zadejte *dsregcmd /join* a stiskněte klávesu **Enter**.
- Po dokončení zavřete okno příkazového řádku.
- Restartujte počítač a přihlásit do OneDrive.