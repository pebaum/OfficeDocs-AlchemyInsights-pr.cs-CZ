---
title: Přístup byl odepřen při zobrazení pracovního postupu
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: cced887b03876eef527e0166a5a3c9be4b553029
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281164"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Přístup byl odepřen při zobrazení pracovního postupu

Pracovní postupy služby SharePoint 2013, který se pokusí odeslat e-mailu skupině SharePoint může selhat s chybovou zprávou "Přístup byl odepřen", pokud členství ve skupině služby SharePoint není nastavena na hodnotu Všichni.
  
 **Chcete-li tento problém vyřešit, proveďte tyto kroky:**
  
 1. Každý uživatel, chcete-li zobrazit členy skupiny SharePoint povolte. 
  
 2. Odebrat skupinu SharePoint ze Komu nebo kopie řádku e-mailu. 
  
 3. Explicitně přidat uživatele do Komu nebo kopie řádku, pokud nelze změnit viditelnost členství pro skupinu služby SharePoint. 
  
Chcete-li zobrazit další podrobnosti naleznete v [HTTP Neoprávněný k /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  

