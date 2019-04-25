---
title: Podmíněného přístupu s Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 2e778bf4fbdb766700fb24b3405b4ddce89253f7
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32393534"
---
# <a name="conditional-access-with-intune"></a>Podmíněného přístupu s Intune

Pomocí **Podmíněného přístupu** Intune vyžaduje 3 kroky: 
  
- Vytvoření **Zásady podmíněného přístupu** , které určuje, jaké prostředky jsou chráněna a jaké podmínky musí být splněny pro přístup k těmto prostředkům. Zařízení musí být například kompatibilní před přístupem k podnikovým e-mailem. 
    
- Vytvoření **Zásad dodržování předpisů** k definování nastavení, které musí být splněny před zařízení se považuje za vyhovující. Například zařízení musí mít alespoň 6 číslic kódu pin, je považována za vyhovující. 
    
- Zajištění **Dodržování zásady** a **Zásady podmíněného přístupu** , které jsou zaměřeny na požadované skupiny uživatelů. To může vyžadovat vytvoření specifických skupin uživatelů ve službě Active Directory Azure. 
    
Přečtěte si více:
  
- [Doporučené postupy pro podmíněný přístup](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [Začínáme s podmíněným přístupem](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

