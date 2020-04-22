---
title: Podmíněný přístup s Intune
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: c9c47d71b2da3840504d5b28c7c9e067b4c05fa5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706014"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="c7206-102">Podmíněný přístup s Intune</span><span class="sxs-lookup"><span data-stu-id="c7206-102">Conditional Access with Intune</span></span>

<span data-ttu-id="c7206-103">Použití **podmíněného přístupu** s Intune vyžaduje 3 kroky:</span><span class="sxs-lookup"><span data-stu-id="c7206-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="c7206-104">Vytvořte **zásady podmíněného přístupu,** které definují, jaké prostředky jsou chráněny a jaké podmínky je třeba splnit pro přístup k těmto prostředkům.</span><span class="sxs-lookup"><span data-stu-id="c7206-104">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources.</span></span> <span data-ttu-id="c7206-105">Zařízení musí být například kompatibilní před přístupem k podnikovému e-mailu.</span><span class="sxs-lookup"><span data-stu-id="c7206-105">For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="c7206-106">Vytvořte **zásady dodržování předpisů** k definování nastavení, která musí být splněna, než bude zařízení považováno za vyhovující.</span><span class="sxs-lookup"><span data-stu-id="c7206-106">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant.</span></span> <span data-ttu-id="c7206-107">Zařízení musí mít například pin o nejméně 6 číslicích, než bude považováno za vyhovující.</span><span class="sxs-lookup"><span data-stu-id="c7206-107">For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="c7206-108">Zajištění zásad **dodržování předpisů** a zásad **podmíněného přístupu** jsou zaměřeny na požadované skupiny uživatelů.</span><span class="sxs-lookup"><span data-stu-id="c7206-108">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users.</span></span> <span data-ttu-id="c7206-109">To může vyžadovat vytvoření konkrétních skupin uživatelů ve službě Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="c7206-109">This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="c7206-110">Přečtěte si více:</span><span class="sxs-lookup"><span data-stu-id="c7206-110">Read more:</span></span>
  
- [<span data-ttu-id="c7206-111">Doporučené postupy podmíněného přístupu</span><span class="sxs-lookup"><span data-stu-id="c7206-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="c7206-112">Začínáme s podmíněným přístupem</span><span class="sxs-lookup"><span data-stu-id="c7206-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    

