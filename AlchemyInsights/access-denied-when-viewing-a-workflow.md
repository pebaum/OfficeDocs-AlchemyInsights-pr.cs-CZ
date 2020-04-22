---
title: Přístup byl odepřen při zobrazení pracovního postupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: c576bf88225582f2577e0b59506a7482cf9f38d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687323"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Přístup byl odepřen při zobrazení pracovního postupu

Pracovní postupy SharePointu 2013, které se pokoušejí odeslat e-mail skupině SharePointu, můžou selhat s chybovou zprávou "Přístup byl odepřen", pokud členství ve skupině SharePoint není nastaveno na Všechny.
  
 **Chcete-li tento problém vyřešit, postupujte takto:**
  
 1. Umožněte všem zobrazit členy skupiny SharePoint.
  
 2. Odeberte skupinu SharePoint z řádku Komu nebo KOPIE e-mailu.
  
 3. Explicitně přidejte uživatele do řádku Komu nebo KOPIE, pokud viditelnost členství nelze pro skupinu SharePoint změnit.
  
Chcete-li zobrazit další podrobnosti naleznete [v protokolu HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  