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
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29935922"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="ec087-102">Podmíněného přístupu s Intune</span><span class="sxs-lookup"><span data-stu-id="ec087-102">Conditional Access with Intune</span></span>

<span data-ttu-id="ec087-103">Pomocí **Podmíněného přístupu** Intune vyžaduje 3 kroky:</span><span class="sxs-lookup"><span data-stu-id="ec087-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="ec087-p101">Vytvoření **Zásady podmíněného přístupu** , které určuje, jaké prostředky jsou chráněna a jaké podmínky musí být splněny pro přístup k těmto prostředkům. Zařízení musí být například kompatibilní před přístupem k podnikovým e-mailem.</span><span class="sxs-lookup"><span data-stu-id="ec087-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="ec087-p102">Vytvoření **Zásad dodržování předpisů** k definování nastavení, které musí být splněny před zařízení se považuje za vyhovující. Například zařízení musí mít alespoň 6 číslic kódu pin, je považována za vyhovující.</span><span class="sxs-lookup"><span data-stu-id="ec087-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="ec087-p103">Zajištění **Dodržování zásady** a **Zásady podmíněného přístupu** , které jsou zaměřeny na požadované skupiny uživatelů. To může vyžadovat vytvoření specifických skupin uživatelů ve službě Active Directory Azure.</span><span class="sxs-lookup"><span data-stu-id="ec087-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="ec087-110">Přečtěte si více:</span><span class="sxs-lookup"><span data-stu-id="ec087-110">Read more:</span></span>
  
- [<span data-ttu-id="ec087-111">Doporučené postupy pro podmíněný přístup</span><span class="sxs-lookup"><span data-stu-id="ec087-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="ec087-112">Začínáme s podmíněným přístupem</span><span class="sxs-lookup"><span data-stu-id="ec087-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

