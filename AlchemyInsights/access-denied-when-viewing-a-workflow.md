---
title: Při zobrazení pracovního postupu byl odepřen přístup
ms.author: pebaum
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 4ca65583fbd98867026e9e3cc8f36fe38798aa85
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36747741"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Při zobrazení pracovního postupu byl odepřen přístup

Pracovní postupy služby SharePoint 2013, které se pokoušejí odeslat e-mail skupině SharePoint, mohou selhat s chybovou zprávou "přístup byl odepřen" v případě, že členství ve skupině SharePoint není nastaveno na možnost Everyone.
  
 **Tento problém vyřešíte následujícím postupem:**
  
 1. Umožňuje všem zobrazit členy skupiny SharePoint.
  
 2. Odeberte skupinu SharePoint z řádku Komu nebo kopie v e-mailu.
  
 3. Uživatelé mohou explicitně přidat uživatele do řádku Komu nebo kopie, pokud viditelnost členství nelze změnit pro skupinu SharePoint.
  
Chcete-li zobrazit další podrobnosti, použijte [protokol HTTP neoprávněný na/_vti_bin/Client.svc/SP.Utilities.Utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  