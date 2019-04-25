---
title: Omezení přístupu v serveru SharePoint nebo OneDrive
ms.author: mikeplum
author: MikePlumleyMSFT
ms.date: 8/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e0fbec6eb269a173664e2b9a1efe6eefb527b96f
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32383864"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Omezení přístupu v serveru SharePoint nebo OneDrive

V SharePoint a OneDrive můžete omezit přístup k položky, jako jsou soubory, složky a seznamy udělením přístupu pouze pro skupiny nebo jednotlivce, který má přístup. Ve výchozím nastavení oprávnění ve službě SharePoint zděděna z výše v hierarchii. Tak soubor dědí oprávnění ze složky, které dědí oprávnění z knihovny, který dědí oprávnění z webu.
  
Můžete sdílet na vyšší úrovni (například pomocí sdílení celého webu) a potom přerušit vztah dědičnosti, pokud chcete sdílet všechny položky na webu. Avšak nedoporučujeme to proto zachování oprávnění více složité a matoucí v budoucnosti. Zde je to, co byste mohli dělat místo toho:
  
- Pokud například chcete sdílet obsah složek s výjimkou jednoho souboru, tento soubor přesunete do nového umístění, který není sdílen.
    
- Pokud máte dvě podsložky ve složce a chcete sdílet jednu podsložku s skupiny A a B povolit pouze skupiny A přístup k podsložce druhé, skupině A sdílet složku a přidat skupiny B první podsložky.
    
[Zastavení sdílení souboru nebo složky](https://go.microsoft.com/fwlink/?linkid=2008861)
  

