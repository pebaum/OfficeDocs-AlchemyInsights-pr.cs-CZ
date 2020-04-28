---
title: Přidání externích uživatelů do distribuční skupiny
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 7dbc69bced9ca800d3f95081b77dda5e49662579
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/27/2020
ms.locfileid: "43910925"
---
# <a name="add-external-users-to-a-distribution-group"></a>Přidání externích uživatelů do distribuční skupiny

Přidání externího kontaktu do distribuční skupiny (DG) je dvoustupňový proces:
  
1. Vytvoření kontaktu pošty pro externího uživatele:
    
    1. V Centru pro správu přejděte na stránku[Kontakty](https://admin.microsoft.com/adminportal/home#/Contact) **uživatelů.** >  
    
    2. Vyberte **Přidat kontakt**.
    
    3. Zadejte informace o kontaktu a vyberte **Přidat**.
    
2. Přidejte mailový kontakt do svého GŘ:
    
    1. V Centru pro správu přejděte na stránku > [Skupiny](https://admin.microsoft.com/adminportal/home#/groups) skupin. **Groups** 
    
    2. Najděte GŘ, do kterého chcete přidat externího uživatele, a vyberte ho, chcete-li otevřít dialogové okno pro úpravy.
    
    3. Na kartě **Členové** vyberte **Zobrazit vše a spravovat členy**. 
    
    4. Vyberte **Přidat členy**.
    
    5. Vyberte kontakt pošty, který jste vytvořili v předchozím kroku, a pak vyberte **Uložit**.
    
Pokud po provedení těchto kroků nemohou externí uživatelé odesílat e-maily GŘ nebo od něj nedostávají e-maily, může se podařit, že GŘ je označeno tak, aby umožňovalo pouze e-maily od interních uživatelů. Můžete zkontrolovat tuto konfiguraci a opravit ji podle pokynů [zde](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).
  
 **Poznámka:** Tyto pokyny se nevztahují, pokud je typ vaší skupiny "Skupina Microsoft 365" místo "Distribuční skupina". V takovém případě můžete externího uživatele přidat přímo do skupiny z aplikace Outlook. Podrobné informace o hostech skupin y Microsoft 365 a pokyny pro přidání externích hostů naleznete v [tomto článku](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).
  