---
title: Poskytnutí přístupu uživatelům ke SharePointu a OneDrivu
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 0bdc2fa97ad1fe8b3280411babaaf2bd685a644d
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43721728"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="0838b-102">Poskytnutí přístupu uživatelům ke SharePointu a OneDrivu</span><span class="sxs-lookup"><span data-stu-id="0838b-102">Give users access to SharePoint and OneDrive</span></span>

> [!NOTE]
> <span data-ttu-id="0838b-103">Pokud web OneDrivu nebo SharePointu není k dispozici více uživatelům, kteří k nim měli dříve přístup, může se jedná o dočasný problém se službou.</span><span class="sxs-lookup"><span data-stu-id="0838b-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> [<span data-ttu-id="0838b-104">Kontrola řídicího panelu stavu služby</span><span class="sxs-lookup"><span data-stu-id="0838b-104">Check the service health dashboard</span></span>](https://portal.office.com/adminportal/home#/servicehealth)
  
<span data-ttu-id="0838b-105">Pokud chcete, aby se lidé ve vaší organizaci mohli přihlásit a používat SharePoint a OneDrive, musíte pro ně přidat účty a ujistit se, že mají licenci, která jim umožní přístup ke SharePointu a OneDrivu.</span><span class="sxs-lookup"><span data-stu-id="0838b-105">If you want people in your organization to be able to sign in and use SharePoint and OneDrive, you need to add accounts for them and make sure they have a license that gives them access to SharePoint and OneDrive.</span></span> <span data-ttu-id="0838b-106">Nejjednodušší způsob, jak přidat uživatele, je v Centru pro správu Microsoftu 365.</span><span class="sxs-lookup"><span data-stu-id="0838b-106">The easiest way to add users is in the Microsoft 365 admin center.</span></span>
  
1. <span data-ttu-id="0838b-107">Přejděte na [stránku Aktivní uživatelé v Centru pro správu Microsoftu 365](https://portal.office.com/adminportal/home#/users)a klikněte na **Přidat uživatele**.</span><span class="sxs-lookup"><span data-stu-id="0838b-107">Go to the [Active users page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/users), and then click **Add a user**.</span></span>
    
2. <span data-ttu-id="0838b-108">Vyplňte informace o uživateli a ujistěte se, že v části **Licence produktu**je přiřazena licence a je **vybrána sharepointonline.**</span><span class="sxs-lookup"><span data-stu-id="0838b-108">Fill in the information for the user, and make sure that under **Product licenses**, a license is assigned and **SharePoint Online** is selected.</span></span> 
    
<span data-ttu-id="0838b-109">Upozorňujeme, že pokud povolíte externí sdílení ve vaší organizaci, můžou uživatelé sdílet obsah SharePointu a OneDrivu s lidmi mimo organizaci.</span><span class="sxs-lookup"><span data-stu-id="0838b-109">Note that if you allow external sharing in your organization, users can share SharePoint and OneDrive content with people outside the organization.</span></span> <span data-ttu-id="0838b-110">Těmto externím uživatelům nemusíte udělit licence.</span><span class="sxs-lookup"><span data-stu-id="0838b-110">You don't need to give these external users licenses.</span></span> <span data-ttu-id="0838b-111">Také není nutné přidávat účty pro ně, pokud sdílení je nastavena na "Pouze stávající externí uživatelé."</span><span class="sxs-lookup"><span data-stu-id="0838b-111">You also don't need to add accounts for them, unless sharing is set to "Only existing external users."</span></span> <span data-ttu-id="0838b-112">V takovém případě, pokud lidé nejsou v adresáři vaší organizace, je třeba je přidat jako uživatele typu Host v Centru pro správu Azure AD.</span><span class="sxs-lookup"><span data-stu-id="0838b-112">In that case, if the people aren't in your organization's directory, you need to add them as guest users in the Azure AD admin center.</span></span>
  

