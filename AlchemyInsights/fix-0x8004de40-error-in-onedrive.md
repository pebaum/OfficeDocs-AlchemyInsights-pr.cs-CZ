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
ms.openlocfilehash: d436184bdc0e283db217ea734fb2c8e05f85b4e7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36525052"
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