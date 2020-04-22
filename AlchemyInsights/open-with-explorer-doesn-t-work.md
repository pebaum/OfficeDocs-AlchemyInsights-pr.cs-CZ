---
title: Otevřít v Průzkumníkovi nefunguje
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: dc939a3451ff4fe95e4aa5a999839a2c532b398c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713027"
---
# <a name="open-with-explorer-isnt-working"></a>Otevřít v Průzkumníkovi nefunguje

Pokud **open s Průzkumníkem** nebo **zobrazení v Průzkumníku souborů** nefunguje, ujistěte se, že služba WebClient je nastavena na **spuštěno** podle následujících kroků. Otevření knihovny SharePointu nebo OneDrivu může například trvat dlouho, když služba není spuštěná. 
  
1. Do vyhledávacího pole windows zadejte spustit, vyberte spustit aplikaci klasické pracovní plochy, zadejte services.msc a pak vyberte **Enter**.
    
2. Přejděte dolů na službu WebClient a zkontrolujte sloupec **Stav.** Pokud stav služby WebClient není **spuštěn**, poklepejte na službu, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**. V případě potřeby povolte službu zaškrtnutím políčka **Ručně** nebo **Automaticky** v poli **Typ spuštění.** 
    
> [!NOTE]
> Informace o řešení problémů s otevřením v Průzkumníkovi souborů naleznete [v tématu Otevření v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Prozkoumejte synchronizaci jako lepší alternativu: [Synchronizujte sharepointové soubory s novým klientem synchronizace OneDrivu](https://go.microsoft.com/fwlink/?linkid=871666). 
  

