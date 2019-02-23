---
title: Udělit uživatelům přístup k webu služby SharePoint a OneDrive
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: d29764266f44aee5f8f8e2c93ad67b2a33c6f417
ms.sourcegitcommit: c003a5db7edc3a44fb5b31b46cd45f12b62d172a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/22/2019
ms.locfileid: "30209730"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="12a56-102">Udělit uživatelům přístup k webu služby SharePoint a OneDrive</span><span class="sxs-lookup"><span data-stu-id="12a56-102">Give users access to SharePoint and OneDrive</span></span>

> [!NOTE]
> <span data-ttu-id="12a56-p101">Pokud není k dispozici pro více uživatelů, kteří dříve měl přístup na OneDrive nebo SharePoint Server, může se jednat o problém dočasnou službu. [Kontrola řídicí panel stavu služeb](https://portal.office.com/adminportal/home#/servicehealth)</span><span class="sxs-lookup"><span data-stu-id="12a56-p101">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue. [Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth)</span></span>
  
<span data-ttu-id="12a56-p102">Pokud chcete uživatelům ve vaší organizaci budete moci přihlásit a používat SharePoint a OneDrive, musíte přidat účty a ujistěte se, že mají licenci, která umožňuje přístup k webu služby SharePoint a OneDrive. Nejjednodušší způsob, jak přidat uživatele je ve středisku pro správce služeb Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="12a56-p102">If you want people in your organization to be able to sign in and use SharePoint and OneDrive, you need to add accounts for them and make sure they have a license that gives them access to SharePoint and OneDrive. The easiest way to add users is in the Microsoft 365 admin center.</span></span>
  
1. <span data-ttu-id="12a56-107">Přejít na [stránky aktivních uživatelů v centru Microsoft 365 admin](https://portal.office.com/adminportal/home#/users)a potom klepněte na tlačítko **Přidat uživatele**.</span><span class="sxs-lookup"><span data-stu-id="12a56-107">Go to the [Active users page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/users), and then click **Add a user**.</span></span>
    
2. <span data-ttu-id="12a56-108">Vyplňte informace pro uživatele a ujistěte se, že pod **licencí**je přiřazena licence a vybrané **Online služby SharePoint** .</span><span class="sxs-lookup"><span data-stu-id="12a56-108">Fill in the information for the user, and make sure that under **Product licenses**, a license is assigned and **SharePoint Online** is selected.</span></span> 
    
<span data-ttu-id="12a56-p103">Všimněte si, že pokud chcete povolit externí sdílení v rámci organizace, uživatelé mohou sdílet obsah služby SharePoint a OneDrive s uživateli mimo organizaci. Není nutné poskytnout tyto licence pro externí uživatele. Také není nutné přidat účty, pokud sdílení je nastavena na "Pouze existující externí uživatele." V takovém případě nejsou-li osoby v adresáři vaší organizace, musíte je přidat jako hosta v Centru pro správu Azure AD.</span><span class="sxs-lookup"><span data-stu-id="12a56-p103">Note that if you allow external sharing in your organization, users can share SharePoint and OneDrive content with people outside the organization. You don't need to give these external users licenses. You also don't need to add accounts for them, unless sharing is set to "Only existing external users." In that case, if the people aren't in your organization's directory, you need to add them as guest users in the Azure AD admin center.</span></span>
  

