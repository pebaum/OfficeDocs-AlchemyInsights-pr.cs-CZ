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
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36504987"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="41bfe-102">Podmíněný přístup s Intune</span><span class="sxs-lookup"><span data-stu-id="41bfe-102">Conditional Access with Intune</span></span>

<span data-ttu-id="41bfe-103">Použití **podmíněného přístupu** s Intune vyžaduje 3 kroky:</span><span class="sxs-lookup"><span data-stu-id="41bfe-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="41bfe-104">Vytvořte **zásadu podmíněného přístupu** , která definuje, které prostředky jsou chráněny, a jaké podmínky je třeba splnit pro přístup k těmto prostředkům.</span><span class="sxs-lookup"><span data-stu-id="41bfe-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="41bfe-105">Zařízení musí být například kompatibilní před přístupem k firemní e-mailu.</span><span class="sxs-lookup"><span data-stu-id="41bfe-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="41bfe-106">Vytvořte **zásady shody** definující nastavení, která musí být splněna, aby bylo zařízení považováno za vyhovující.</span><span class="sxs-lookup"><span data-stu-id="41bfe-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="41bfe-107">Například zařízení musí mít PIN alespoň 6 číslic, než je považováno za vyhovující.</span><span class="sxs-lookup"><span data-stu-id="41bfe-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="41bfe-108">Zajištění **zásad shody** a **zásad podmíněného přístupu** je zaměřeno na požadované skupiny uživatelů.</span><span class="sxs-lookup"><span data-stu-id="41bfe-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="41bfe-109">To může vyžadovat vytvoření specifických skupin uživatelů v Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="41bfe-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="41bfe-110">Další informace:</span><span class="sxs-lookup"><span data-stu-id="41bfe-110">Read more:</span></span>
  
- [<span data-ttu-id="41bfe-111">Doporučené postupy pro podmíněné přístup</span><span class="sxs-lookup"><span data-stu-id="41bfe-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="41bfe-112">Začínáme s podmíněným přístupem</span><span class="sxs-lookup"><span data-stu-id="41bfe-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

