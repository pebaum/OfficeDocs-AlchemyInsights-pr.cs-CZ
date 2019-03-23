---
title: Řešení potíží pomocí otevřít pomocí Průzkumníka
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
ms.assetid: ed852342-e33f-4450-8400-63d30df09476
ms.openlocfilehash: 03bb3ad01a716390ec50845b29ddf6cc81a83116
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30759287"
---
# <a name="fix-problems-with-open-with-explorer"></a>Řešení potíží se službou otevřít v programu Průzkumník

Řešení běžných potíží s otevřením knihovny dokumentů služby SharePoint nebo OneDrive pomocí příkazu **Otevřít v Průzkumníkovi** : 
  
- Pomocí Internet Explorer 10 nebo Internet Explorer 11. **Otevřít v aplikaci Explorer** není kompatibilní s Edge Microsoft, Google Chrome, Firefox a další. **Otevřít pomocí Průzkumníka** je zakázáno ve všech prohlížečích s výjimkou Internet Explorer. 
    
- **Otevřít v Průzkumníkovi** není k dispozici v moderních zkušenosti pro knihovny služby SharePoint. Místo toho použijte **zobrazení v Průzkumníku souborů** . Vyberte **Možnosti zobrazení** \> **zobrazení v Průzkumníku souborů**. Zobrazení v Průzkumníku souboru není kompatibilní s Edge Microsoft, Google Chrome, Firefox a další. **Zobrazení v Průzkumníku souboru** k dispozici pouze v aplikaci Internet Explorer. 
    
- Zkontrolujte, zda že je spuštěna služba Webový klient. Do pole hledání systému Windows spustit, typ vyberte desktop app spustit, zadejte příkaz services.msc a stiskněte klávesu Enter. Přejděte na položku Služba Webový klient a ujistěte se, že ve sloupci **Stav** zobrazí "Spuštění." Pokud tomu tak není, poklepejte na položku služby, klepněte na tlačítko **Start**a potom klepněte na tlačítko **OK**. (Pravděpodobně nutné nejprve povolit výběrem **Ruční** nebo **Automatické** v rozevíracím seznamu **Typ spouštění** .) 
    
> [!NOTE]
> Otevření knihovny v Průzkumníku souborů je užitečné, pokud chcete kopírovat nebo přesouvat více souborů a složek po, ale pokud chcete pravidelně pracovat v knihovně, doporučujeme jeho synchronizací. Problémů s otevřením v File Explorer, viz [Otevřít v Průzkumníkovi](https://go.microsoft.com/fwlink/?linkid=871665). Informace o nastavení synchronizace naleznete v tématu [SharePoint synchronizace souborů pomocí nového klienta synchronizace OneDrive](https://go.microsoft.com/fwlink/?linkid=871666).
  
Naleznete další informace v článku [použití příkazu "otevřít pomocí Průzkumníka" problémů v Online služby SharePoint](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4) . 
  

