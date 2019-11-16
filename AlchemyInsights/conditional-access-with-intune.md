---
title: Podmíněný přístup s Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: e147e7460ee6a786e577a43c0b8355fc27ee367b
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "36504987"
---
# <a name="conditional-access-with-intune"></a>Podmíněný přístup s Intune

Použití **podmíněného přístupu** s Intune vyžaduje 3 kroky: 
  
- Vytvořte **zásadu podmíněného přístupu** , která definuje, které prostředky jsou chráněny, a jaké podmínky je třeba splnit pro přístup k těmto prostředkům. Zařízení musí být například kompatibilní před přístupem k firemní e-mailu. 
    
- Vytvořte **zásady shody** definující nastavení, která musí být splněna, aby bylo zařízení považováno za vyhovující. Například zařízení musí mít PIN alespoň 6 číslic, než je považováno za vyhovující. 
    
- Zajištění **zásad shody** a **zásad podmíněného přístupu** je zaměřeno na požadované skupiny uživatelů. To může vyžadovat vytvoření specifických skupin uživatelů v Azure Active Directory. 
    
Další informace:
  
- [Doporučené postupy pro podmíněné přístup](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Začínáme s podmíněným přístupem](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

