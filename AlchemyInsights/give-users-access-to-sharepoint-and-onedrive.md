---
title: Poskytnout uživatelům přístup ke službě SharePoint a OneDrive
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 1be9763ce7766c6261f0c1dae78ced6727c7a88d
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "36523756"
---
# <a name="give-users-access-to-sharepoint-and-onedrive"></a><span data-ttu-id="78c17-102">Poskytnout uživatelům přístup ke službě SharePoint a OneDrive</span><span class="sxs-lookup"><span data-stu-id="78c17-102">Give users access to SharePoint and OneDrive</span></span>

> [!NOTE]
> <span data-ttu-id="78c17-103">Pokud není web OneDrive nebo SharePoint k dispozici pro více uživatelů, kteří měli přístup dříve, může se jednat o dočasný problém se službou.</span><span class="sxs-lookup"><span data-stu-id="78c17-103">If a OneDrive or SharePoint site is not available to multiple users who previously had access, there may be a temporary service issue.</span></span> [<span data-ttu-id="78c17-104">Kontrola řídicího panelu stavu služby</span><span class="sxs-lookup"><span data-stu-id="78c17-104">Check the service health dashboard</span></span>](https://portal.office.com/adminportal/home#/servicehealth)
  
<span data-ttu-id="78c17-105">Chcete-li, aby se uživatelé ve vaší organizaci mohli přihlásit a používat službu SharePoint a OneDrive, musíte pro ně přidat účty a ujistit se, že mají licenci, která jim poskytuje přístup ke službě SharePoint a OneDrive.</span><span class="sxs-lookup"><span data-stu-id="78c17-105">If you want people in your organization to be able to sign in and use SharePoint and OneDrive, you need to add accounts for them and make sure they have a license that gives them access to SharePoint and OneDrive.</span></span> <span data-ttu-id="78c17-106">Nejsnadnější způsob přidání uživatelů je v centru Microsoft 365 Admin Center.</span><span class="sxs-lookup"><span data-stu-id="78c17-106">The easiest way to add users is in the Microsoft 365 admin center.</span></span>
  
1. <span data-ttu-id="78c17-107">Přejděte na [stránku aktivní uživatelé ve středisku Microsoft 365 Admin Center](https://portal.office.com/adminportal/home#/users)a klepněte na tlačítko **Přidat uživatele**.</span><span class="sxs-lookup"><span data-stu-id="78c17-107">Go to the [Active users page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/users), and then click **Add a user**.</span></span>
    
2. <span data-ttu-id="78c17-108">Zadejte informace pro uživatele a ujistěte se, že je v rámci **licencí k produktu**přiřazena licence a je vybrána **Služba SharePoint Online** .</span><span class="sxs-lookup"><span data-stu-id="78c17-108">Fill in the information for the user, and make sure that under **Product licenses**, a license is assigned and **SharePoint Online** is selected.</span></span> 
    
<span data-ttu-id="78c17-109">Počítejte s tím, že pokud povolíte externí sdílení v organizaci, mohou uživatelé sdílet obsah služby SharePoint a OneDrive s lidmi mimo organizaci.</span><span class="sxs-lookup"><span data-stu-id="78c17-109">Note that if you allow external sharing in your organization, users can share SharePoint and OneDrive content with people outside the organization.</span></span> <span data-ttu-id="78c17-110">Tyto licence externích uživatelů nemusíte poskytovat.</span><span class="sxs-lookup"><span data-stu-id="78c17-110">You don't need to give these external users licenses.</span></span> <span data-ttu-id="78c17-111">Pro ně také nemusíte přidávat účty, pokud není sdílení nastaveno na "pouze existující externí uživatelé".</span><span class="sxs-lookup"><span data-stu-id="78c17-111">You also don't need to add accounts for them, unless sharing is set to "Only existing external users."</span></span> <span data-ttu-id="78c17-112">V takovém případě, pokud uživatelé nejsou v adresáři vaší organizace, je třeba je přidat jako uživatele Guest do centra Azure AD Admin Center.</span><span class="sxs-lookup"><span data-stu-id="78c17-112">In that case, if the people aren't in your organization's directory, you need to add them as guest users in the Azure AD admin center.</span></span>
  

