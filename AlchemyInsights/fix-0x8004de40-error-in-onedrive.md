---
title: Fix 0x8004de40 chyba v OneDrive
ms.author: pebaum
author: pebaum
ms.date: 6/20/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 48b29f57763ca22a71a23b2afddcac0e8e8a95db
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052030"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a>Fix 0x8004de40 chyba v OneDrive

Obdržíte-li chybu 0x8004de40 u funkce OneDrive:

- Restartujte ohrožený počítač, který je připojen k doméně adresáře Acitve.
- Pokud počítač nebude problém napravovat, připojte se a znovu připojte k zařízení Azure AD. 

**Poznámka**: při provádění těchto kroků byste měli být v podnikové síti. Neprovádějte tyto kroky, pokud se nemůžete připojit k podnikové infrastruktuře (například při cestování). 

- Otevřete příkazový řádek se zvýšenými oprávněními. 
- Chcete-li otevřít příkazový řádek se zvýšenými oprávněními, klepněte na tlačítko **Start**, klepněte pravým tlačítkem myši na položku **příkazový řádek**a potom klepněte na příkaz **Spustit jako správce**.
- Zadejte příkaz *dsregcmd/odejdi* a stiskněte klávesu **ENTER**.
- Po dokončení zadejte příkaz *dsregcmd/JOIN* a stiskněte klávesu **ENTER**.
- Po dokončení ukončete příkazový řádek.
- Restartujte počítač a přihlaste se k OneDrive.