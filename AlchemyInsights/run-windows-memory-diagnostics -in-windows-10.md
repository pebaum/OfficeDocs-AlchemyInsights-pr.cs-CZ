---
title: Spuštění diagnostiky paměti Windows ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002959"
- "5661"
ms.openlocfilehash: 3fedc52d02f1f70743429d0313eda0361306c3f3
ms.sourcegitcommit: 18b080c2a5d741af01ec589158effc35ea7cf449
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/19/2020
ms.locfileid: "44357379"
---
# <a name="run-windows-memory-diagnostics-in-windows-10"></a>Spuštění diagnostiky paměti Windows ve Windows 10

Pokud systém Windows a aplikace v počítači havaruje, zamrzá nebo jedná nestabilním způsobem, můžete mít potíže s pamětí počítače (RAM). Můžete spustit Diagnostika paměti systému Windows a zkontrolovat problémy s pamětí RAM počítače.

Do vyhledávacího pole na hlavním panelu zadejte **diagnostiku paměti**a vyberte **nástroj Diagnostika paměti systému Windows**. 

Chcete-li spustit diagnostiku, počítač musí restartovat. Máte možnost restartovat okamžitě (prosím, uložte svou práci a zavřete otevřené dokumenty a e-maily první), nebo naplánovat diagnostiku spustit automaticky při příštím restartování počítače:

![Diagnostika paměti systému Windows](media/windows-memory-diagnostic.png)

Po restartování počítače se **nástroj Diagnostika paměti systému Windows** spustí automaticky. Stav a průběh se zobrazí při spuštění diagnostiky a máte možnost zrušit diagnostiku stisknutím klávesy **ESC** na klávesnici.

Po dokončení diagnostiky se systém Windows spustí normálně.
Ihned po restartování, když se zobrazí plocha, se zobrazí oznámení (vedle ikony **Centra akcí** na hlavním panelu), které označuje, zda byly nalezeny nějaké chyby paměti. Příklad:

Tady je ikona Centra akcí: ![Ikona Centra akcí](media/action-center-icon.png) 

A ukázkové oznámení: ![Žádné chyby paměti](media/no-memory-errors.png)

Pokud jste oznámení zmeškali, můžete vybrat ikonu **Centrum akcí** na hlavním panelu, chcete-li zobrazit **Centrum akcí** a zobrazit posuvný seznam oznámení.

Chcete-li zkontrolovat podrobné informace, zadejte **událost** do vyhledávacího pole na hlavním panelu a vyberte **Prohlížeč událostí**. V levém podokně **prohlížeče událostí**přejděte do > **systému Windows Logs**. V pravém podokně naskenujete seznam při pohledu na sloupec **Zdroj,** dokud neuvidíte události se zdrojovou hodnotou **MemoryDiagnostics-Results**. Zvýrazněte každou takovou událost a podívejte se na informace o výsledku v poli pod kartou **Obecné** pod seznamem.
