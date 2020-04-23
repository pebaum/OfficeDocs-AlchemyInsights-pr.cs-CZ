---
title: Sdílení s externími uživateli nefunguje
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 285535d6144825f0935bf72579a483260c2f2bd6
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767242"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Řešení problémů se sdílením sharepointového obsahu s externími uživateli

Zkontrolujte, jestli je pro vaši organizaci zapnuté externí sdílení:
  
1. Přejděte na [stránku Doplňky &amp; služeb v Centru pro správu Microsoftu 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klikněte na **Weby**.
    
2. Zkontrolujte, zda je nastavení zapnuto. Pokud je vybraná možnost "Jenom stávající externí uživatelé", ujistěte se, že je externí uživatel uveden v Centru pro správu Microsoftu 365.
    
Ujistěte se, že je pro web zapnuté externí sdílení. Pro klasickou kolekci webů:
  
1. V novém Centru pro správu SharePointu klikněte v levém podokně na **Weby**.
    
2. Vyberte web nebo weby a na pásu karet klikněte na **Sdílení**.
    
Pro týmový web, který patří do skupiny Office 365 nebo komunikačního webu:
  
- Tyto nové typy webů mají stejné nastavení sdílení jako nastavení pro celou organizaci, pokud nastavení pro celou organizaci neumožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlášení. V takovém případě umožňují weby sdílení s novými a stávajícími externími uživateli, kteří se přihlašují. Pokud chcete změnit nastavení pro konkrétní weby, použijte nové Centrum pro správu SharePointu nebo PowerShell. [Další informace](https://go.microsoft.com/fwlink/?linkid=871863)
    
> [!NOTE]
> Externí nastavení sdílení pro libovolný web může být více omezující než nastavení celé organizace, ale ne tolerantnější než nastavení pro celou organizaci. 
  

