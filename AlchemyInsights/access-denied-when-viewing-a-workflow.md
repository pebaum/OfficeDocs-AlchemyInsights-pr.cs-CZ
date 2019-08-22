---
title: Přístup byl odepřen při zobrazení pracovního postupu
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 53bd9285e49e220f880eea21923f261302003127
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36495816"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Přístup byl odepřen při zobrazení pracovního postupu

Pracovní postupy služby SharePoint 2013, který se pokusí odeslat e-mailu skupině SharePoint může selhat s chybovou zprávou "Přístup byl odepřen", pokud členství ve skupině služby SharePoint není nastavena na hodnotu Všichni.
  
 **Chcete-li tento problém vyřešit, proveďte tyto kroky:**
  
 1. Každý uživatel, chcete-li zobrazit členy skupiny SharePoint povolte.
  
 2. Odebrat skupinu SharePoint ze Komu nebo kopie řádku e-mailu.
  
 3. Explicitně přidat uživatele do Komu nebo kopie řádku, pokud nelze změnit viditelnost členství pro skupinu služby SharePoint.
  
Chcete-li zobrazit další podrobnosti naleznete v [HTTP Neoprávněný k /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  