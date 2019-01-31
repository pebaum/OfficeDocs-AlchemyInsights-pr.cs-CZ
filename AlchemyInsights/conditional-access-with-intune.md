---
title: Podmíněného přístupu s Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 3b50bc96a879017b62e42e1849f72e68408a0d9d
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662320"
---
# <a name="conditional-access-with-intune"></a>Podmíněného přístupu s Intune

Pomocí **Podmíněného přístupu** Intune vyžaduje 3 kroky: 
  
- Vytvoření **Zásady podmíněného přístupu** , které určuje, jaké prostředky jsou chráněna a jaké podmínky musí být splněny pro přístup k těmto prostředkům. Zařízení musí být například kompatibilní před přístupem k podnikovým e-mailem. 
    
- Vytvoření **Zásad dodržování předpisů** k definování nastavení, které musí být splněny před zařízení se považuje za vyhovující. Například zařízení musí mít alespoň 6 číslic kódu pin, je považována za vyhovující. 
    
- Zajištění **Dodržování zásady** a **Zásady podmíněného přístupu** , které jsou zaměřeny na požadované skupiny uživatelů. To může vyžadovat vytvoření specifických skupin uživatelů ve službě Active Directory Azure. 
    
Přečtěte si více:
  
- [Doporučené postupy pro podmíněný přístup](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Začínáme s podmíněným přístupem](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

