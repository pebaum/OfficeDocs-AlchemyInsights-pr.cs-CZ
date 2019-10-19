---
title: Sdílení s externími uživateli nepracuje
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: d4c8fc75ff8db2319b88a20bea9b3ee661f2e36e
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36502224"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Opravit problémy se sdílením obsahu služby SharePoint s externími uživateli

Zkontrolujte, zda je pro vaši organizaci zapnuto externí sdílení:
  
1. Přejděte na [stránku doplňky &amp; služeb v centru pro správu Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klepněte na možnost **servery**.
    
2. Ujistěte se, že je nastavení zapnuto "zapnuto". Pokud je vybrána možnost pouze existující externí uživatelé, ujistěte se, že je externí uživatel uveden v centru pro správu Microsoft 365.
    
Přesvědčte se, zda je u daného webu zapnuto externí sdílení. Klasická kolekce webů:
  
1. V novém centru pro správu služby SharePoint klepněte v levém podokně na položku **servery**.
    
2. Vyberte web nebo weby a na pásu karet klepněte na tlačítko **sdílení**.
    
Týmový web, který patří do skupiny Office 365, nebo na komunikační web:
  
- Tyto nové typy webů mají stejné nastavení sdílení jako nastavení pro celou organizaci, pokud nastavení na úrovni organizace neumožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlášení. V tomto případě weby umožňují sdílení s novými a existujícími externími uživateli, kteří se budou přihlašovat. Chcete-li změnit nastavení pro určité weby, použijte nové centrum pro správu služby SharePoint nebo prostředí PowerShell. Další [informace](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> Nastavení externího sdílení pro všechny weby může být více omezující než nastavení celé organizace, ale nikoli více opravňující nastavení pro celou organizaci. 
  

