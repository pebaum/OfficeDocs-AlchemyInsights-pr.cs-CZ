---
title: 902 (kvůli duplicitní objekty chyby synchronizace)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: f576460547110e0e599a9062ae03f690792fe635
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29919865"
---
# <a name="sync-errors-due-to-duplicate-objects"></a>Chyby synchronizace z duplikovaných objektů

Po dokončení synchronizace adresáře se může zobrazit jedna z následujících chybových zpráv:
  
- Nelze aktualizovat objekt v aplikaci Microsoft Online Services, protože mají následující atributy přidružené k tomuto objektu hodnoty, které již mohou být spojen s jiným objektem v místní adresář.
    
- Synchronizovaného objektu s stejnou adresu proxy serveru již existuje v adresáři služby Microsoft Online Services.
    
- Nelze aktualizovat objekt, protože mají následující atributy přidružené k tomuto objektu hodnoty, které již mohou být spojen s jiným objektem v místní adresářové služby: UserPrincipalName.
    
Identifikovat a vyřešit tento problém, stáhněte a spusťte [Nástroj náprava chyb IdFix DirSync](https://www.microsoft.com/download/details.aspx?id=36832).
  
Další informace naleznete v tématu [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).
  

