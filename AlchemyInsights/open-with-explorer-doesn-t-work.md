---
title: Není možné otevřít v programu Průzkumník
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: b55fc7bd5670e655334ef7be368b245c8899633a
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29462467"
---
# <a name="open-with-explorer-isnt-working"></a>Otevřít v programu Průzkumník není funkční.

Pokud není možné **Otevřít pomocí Průzkumníka** nebo **zobrazení v Průzkumníku souborů** zkontrolujte, zda že služba Webový klient je nastavena ke **spuštění** pomocí následujících kroků. Například může trvat dlouhou dobu otevření knihovny služby SharePoint nebo OneDrive, pokud služba není spuštěna. 
  
1. Do pole hledání systému Windows spustit, typ vyberte desktop app spustit, zadejte services.msc a potom vyberte možnost **Enter**.
    
2. Vyhledejte položku Služba Webový klient a zaškrtněte políčko ve sloupci **Stav** . Pokud stav služby Webový klient není **spuštěna**, poklepejte na položku služby, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**. Povolte službu, v případě potřeby v rozevíracím seznamu **Typ spouštění** vyberte **Ruční** nebo **Automatické** . 
    
> [!NOTE]
> Problémů s otevřením v File Explorer, viz [Otevřít v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Zkoumání synchronizovat jako lepší alternativa: [SharePoint synchronizace souborů pomocí nového klienta synchronizace OneDrive](https://go.microsoft.com/fwlink/?linkid=871666). 
  

