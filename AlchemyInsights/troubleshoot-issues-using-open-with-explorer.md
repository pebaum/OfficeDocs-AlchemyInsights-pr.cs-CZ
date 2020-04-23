---
title: Poradce při potížích s aplikací Otevřít v Průzkumníkovi
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
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: cb26876d93a110b3b0addd7821206215c783f959
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759685"
---
# <a name="fix-problems-with-open-with-explorer"></a>Řešení problémů s aplikací Otevřít v Průzkumníkovi

Řešení běžných problémů s otevřením knihovny dokumentů na SharePointu nebo OneDrivu pomocí příkazu **Otevřít v Průzkumníkovi:** 
  
- Použijte internet explorer 10 nebo internet explorer 11. **Otevřít s Průzkumníkem** není kompatibilní s Microsoft Edge, Google Chrome, Firefox a další. **Otevřít v aplikaci Explorer** je zakázáno ve všech prohlížečích kromě aplikace Internet Explorer. 
    
- **Open with Explorer** není k dispozici v moderním prostředí pro sharepointové knihovny. Místo toho **použijte zobrazení v Průzkumníkovi** souborů. V **Průzkumníkovi** \> **souborů vyberte Zobrazit volby Zobrazení**. Zobrazení v Průzkumníkovi souborů není kompatibilní s Microsoft Edge, Google Chrome, Firefox a další. **Zobrazení v Průzkumníkovi souborů** je k dispozici pouze v aplikaci Internet Explorer. 
    
- Zkontrolujte, zda je spuštěna služba WebClient. Do vyhledávacího pole windows zadejte spustit, vyberte spustit aplikaci klasické pracovní plochy, zadejte services.msc a stiskněte Enter. Přejděte dolů na službu WebClient a ujistěte se, že ve sloupci **Stav** se zobrazí zpráva Spuštěno. Pokud tomu tak není, poklepejte na službu, klikněte na **tlačítko Start**a potom klikněte na **tlačítko OK**. (Službu může být nutné nejprve povolit zaškrtnutím políčka **Ručně** nebo **Automaticky** v poli **Typ spuštění.)** 
    
> [!NOTE]
> Otevření knihovny v Průzkumníkovi souborů je užitečné, pokud potřebujete jednou zkopírovat nebo přesunout více souborů a složek, ale pokud chcete v knihovně pravidelně pracovat, doporučujeme ji synchronizovat. Informace o řešení problémů s otevřením v Průzkumníkovi souborů naleznete [v tématu Otevření v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Informace o nastavení synchronizace najdete v [tématu Synchronizace sharepointových souborů s novým klientem synchronizace OneDrivu](https://go.microsoft.com/fwlink/?linkid=871666).
  
Další informace najdete v článku [Použití příkazu Otevřít v průzkumníkovi k řešení problémů v SharePointu Online.](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer) 
  

