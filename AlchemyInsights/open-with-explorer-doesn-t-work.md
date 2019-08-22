---
title: Není možné otevřít v programu Průzkumník
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 12/10/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 7680766b53bd5e85789375d3f9e9ab635780ec6c
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36538459"
---
# <a name="open-with-explorer-isnt-working"></a>Otevřít v programu Průzkumník není funkční.

Pokud není možné **Otevřít pomocí Průzkumníka** nebo **zobrazení v Průzkumníku souborů** zkontrolujte, zda že služba Webový klient je nastavena ke **spuštění** pomocí následujících kroků. Například může trvat dlouhou dobu otevření knihovny služby SharePoint nebo OneDrive, pokud služba není spuštěna. 
  
1. Do pole hledání systému Windows spustit, typ vyberte desktop app spustit, zadejte services.msc a potom vyberte možnost **Enter**.
    
2. Vyhledejte položku Služba Webový klient a zaškrtněte políčko ve sloupci **Stav** . Pokud stav služby Webový klient není **spuštěna**, poklepejte na položku služby, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**. Povolte službu, v případě potřeby v rozevíracím seznamu **Typ spouštění** vyberte **Ruční** nebo **Automatické** . 
    
> [!NOTE]
> Problémů s otevřením v File Explorer, viz [Otevřít v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Zkoumání synchronizovat jako lepší alternativa: [SharePoint synchronizace souborů pomocí nového klienta synchronizace OneDrive](https://go.microsoft.com/fwlink/?linkid=871666). 
  

