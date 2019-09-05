---
title: Přidání externích uživatelů do distribuční skupiny
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: e84a5b04d6fc805deaa47cb10c91081f37411e5b
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36737866"
---
# <a name="add-external-users-to-a-distribution-group"></a>Přidání externích uživatelů do distribuční skupiny

Přidání externího kontaktu do distribuční skupiny (DG) je dvoustupňový proces:
  
1. Vytvoření e-mailového kontaktu pro externího uživatele:
    
    1. V centru pro správu přejděte na stránku **Uživatelé** > [kontaktů](https://admin.microsoft.com/adminportal/home#/Contact) . 
    
    2. Vyberte možnost **Přidat kontakt**.
    
    3. Zadejte informace o kontaktu a vyberte možnost **Přidat**.
    
2. Přidejte poštovní kontakt k generálnímu ředitelství:
    
    1. V centru pro správu přejděte > [na stránku](https://admin.microsoft.com/adminportal/home#/groups) skupiny **skupin.** 
    
    2. Najděte DG, do kterého chcete přidat externího uživatele, a vyberte jej, abyste otevřeli dialog pro úpravy.
    
    3. Na kartě **Členové** vyberte možnost **Zobrazit všechny a spravovat členy**. 
    
    4. Vyberte možnost **přidat členy**.
    
    5. Vyberte poštovní kontakt, který jste vytvořili v předchozím kroku, a pak klepněte na **Uložit**.
    
Pokud po provedení těchto kroků nebudou externí uživatelé odesílat e-maily generálnímu ředitelství nebo vám nebudou dostávat emaily, může to být tím, že GŘ je označeno tak, že povoluje pouze e-maily od interních uživatelů. Tuto konfiguraci můžete zkontrolovat a opravit podle pokynů [zde](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).
  
 **Poznámka:** Tyto pokyny neplatí, pokud je typ skupiny "Office 365 Group" místo "distribuční skupina". V takovém případě můžete externí uživatele přidat přímo do skupiny z aplikace Outlook. Podrobné informace o sadě Office 365 a pokyny pro přidání externích hostů naleznete v [tomto článku](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).
  