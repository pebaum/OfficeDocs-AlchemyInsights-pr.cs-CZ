---
title: Při zobrazení pracovního postupu byl odepřen přístup
ms.author: pebaum
author: pebaum
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 1cfda8e08ada05858a28f2bede8c31261f9de351
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/15/2019
ms.locfileid: "40050518"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Při zobrazení pracovního postupu byl odepřen přístup

Pracovní postupy služby SharePoint 2013, které se pokoušejí odeslat e-mail skupině SharePoint, mohou selhat s chybovou zprávou "přístup byl odepřen" v případě, že členství ve skupině SharePoint není nastaveno na možnost Everyone.
  
 **Tento problém vyřešíte následujícím postupem:**
  
 1. Umožňuje všem zobrazit členy skupiny SharePoint.
  
 2. Odeberte skupinu SharePoint z řádku Komu nebo kopie v e-mailu.
  
 3. Uživatelé mohou explicitně přidat uživatele do řádku Komu nebo kopie, pokud viditelnost členství nelze změnit pro skupinu SharePoint.
  
Chcete-li zobrazit další podrobnosti, použijte [protokol HTTP Neautorizováno na/_vti_bin/Client.svc/SP.Utilities.Utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  