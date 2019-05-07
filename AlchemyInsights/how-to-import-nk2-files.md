---
title: How-k-import-nk2-soubory
ms.author: daeite
author: daeite
manager: joallard
ms.date: 5/3/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1800027"
- "1267"
ms.assetid: ''
ms.openlocfilehash: ed0c679cf3ed9d363e552c04a5ae6d0fc72f88dd
ms.sourcegitcommit: 6a229919cf67005e7e67841e9e45f2f3aa6833ef
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/06/2019
ms.locfileid: "33630009"
---
# <a name="how-to-import-nk2-files"></a>Import souborů NK2 

Při prvním spuštění aplikace Microsoft Outlook 2013, aplikace Outlook 2016, 2019 aplikace Outlook nebo Outlook pro Office 365, je mezipaměť přezdívek (uložené v souboru *Název_profilu*.nk2) importovat do skryté zprávy ve výchozím úložišti zpráv.

Pro import souborů NK2 do aplikace Outlook 2013, aplikace Outlook 2016, 2019 aplikace Outlook nebo Outlook pro Office 365, ujistěte se, že soubor NK2 je v následující složce: %appdata%\Microsoft\Outlook

**Poznámka**: soubor NK2 musí mít stejný název jako aktuální profil aplikace Outlook 2013 nebo Outlook 2016. Ve výchozím nastavení je název profilu "Outlook". Zkontrolujte název profilu, postupujte takto: 
1. Klepněte na tlačítko **Start**a na příkaz **Ovládací panely**.
2. Poklepejte na panel **Pošta**.
3. V dialogovém okně Nastavení pošty vyberte **Zobrazit profily**.
4. Vyberte možnost **Spustit** > **spuštění**.
5. Do pole **Otevřít** zadejte *outlook.exe /importnk2*a potom klepněte na tlačítko **OK**. 

Po importu souboru NK2 obsah souboru jsou sloučeny do existující mezipaměť přezdívek uloženy v poštovní schránce.

**Poznámka**: soubor NK2 přejmenován s příponou OLD, při příštím spuštění aplikace Outlook 2013, aplikace Outlook 2016, 2019 aplikace Outlook nebo Outlook pro Office 365. Pokud chcete znovu importovat soubor NK2, nejprve odeberte příponu názvu souboru OLD.

Další informace naleznete v tématu [Import nebo kopírování seznamu automatického dokončování do jiného počítače](https://support.microsoft.com/en-us/help/2806550/how-to-import-nk2-files-into-outlook%).