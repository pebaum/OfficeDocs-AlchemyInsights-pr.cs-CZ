---
title: Omezení přístupu v serveru SharePoint nebo OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: b6be074ed5f7e83f8196ca3fe90252673896569f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281714"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Omezení přístupu v serveru SharePoint nebo OneDrive

V SharePoint a OneDrive můžete omezit přístup k položky, jako jsou soubory, složky a seznamy udělením přístupu pouze pro skupiny nebo jednotlivce, který má přístup. Ve výchozím nastavení oprávnění ve službě SharePoint zděděna z výše v hierarchii. Tak soubor dědí oprávnění ze složky, které dědí oprávnění z knihovny, který dědí oprávnění z webu.
  
Můžete sdílet na vyšší úrovni (například pomocí sdílení celého webu) a potom přerušit vztah dědičnosti, pokud chcete sdílet všechny položky na webu. Avšak nedoporučujeme to proto zachování oprávnění více složité a matoucí v budoucnosti. Zde je to, co byste mohli dělat místo toho:
  
- Pokud například chcete sdílet obsah složek s výjimkou jednoho souboru, tento soubor přesunete do nového umístění, který není sdílen.
    
- Pokud máte dvě podsložky ve složce a chcete sdílet jednu podsložku s skupiny A a B povolit pouze skupiny A přístup k podsložce druhé, skupině A sdílet složku a přidat skupiny B první podsložky.
    
[Zastavení sdílení souboru nebo složky](https://go.microsoft.com/fwlink/?linkid=2008861)
  

