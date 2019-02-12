---
title: S externím uživatelům sdílení nefunguje.
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 5/18/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: 20b538846997c021b6e88596a1e8aff401ea935b
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29900858"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a>Řešení potíží s externím uživatelům sdílení obsahu služby SharePoint

Ujistěte se, že externí sdílení pro vaši organizaci:
  
1. Přejděte [služby &amp; stránku doplňky ve středisku pro správce služeb Office 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)a klepněte na tlačítko **servery**.
    
2. Zkontrolujte, zda že je zapnuto nastavení "On". Pokud je vybrána "Pouze existující externí uživatelé", přesvědčte se, zda externí uživatel je uveden ve středisku pro správce služeb Office 365.
    
Přesvědčte se, zda externí sdílení zapnuta pro web. Kolekce klasických webů:
  
1. V klasické SharePoint admin center v levém podokně klikněte na **kolekce webů**.
    
2. Vyberte web nebo weby a na pásu karet, klepněte na příkaz **sdílení**.
    
Pro týmový web, který patří do skupiny Office 365, nebo komunikační web:
  
- Tyto nové typy webu Pokud budou mít stejné sdílení nastavení jako nastavení celoorganizačních celopodnikové nastavení umožňuje sdílení souborů pomocí odkazů, které nevyžadují přihlásit. V tomto případě weby povolit sdílení se nové a existující externí uživatelé přihlásit. Chcete-li změnit nastavení pro konkrétní weby, pomocí nového centra správy služby SharePoint (Náhled) nebo v prostředí PowerShell. [Další informace](https://go.microsoft.com/fwlink/?linkid=871863).
    
> [!NOTE]
> Externí sdílení nastavení libovolného webu může být více omezující než nastavení celoorganizačních ale povolující ne více než celopodnikové nastavení. 
  

