---
title: Spravovat uživatele synchronizovány
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: a943c59d67c512e6326856dacd0053db121f6aa3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36541977"
---
# <a name="unable-to-set-primary-email-address-or-change-user-attributes"></a><span data-ttu-id="82c8b-102">Nepodařilo se nastavit primární e-mailovou adresu nebo změnit atributy uživatele</span><span class="sxs-lookup"><span data-stu-id="82c8b-102">Unable to set primary email address or change user attributes</span></span>

<span data-ttu-id="82c8b-103">Pokud je synchronizace adresářů povoleno prostředí, nelze některé atributy pro objekt uživatele nebo změnit pomocí středisku pro správce služeb Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="82c8b-103">If directory synchronization is enabled for your environment, some user or object attributes cannot be changed using the Microsoft 365 admin center.</span></span>

<span data-ttu-id="82c8b-104">Ke správě plně synchronizované uživatele a jejich atributy, pomocí vaší místní služby active directory uživatelé a skupiny konzoly Správa (adsiedit.msc).</span><span class="sxs-lookup"><span data-stu-id="82c8b-104">To fully manage synchronized users and all their attributes, use your local active directory users and groups management console (adsiedit.msc).</span></span>  

<span data-ttu-id="82c8b-105">Můžete také změnit jednotlivé uživatele nebo pro synchronizované uživatele pomocí prostředí powershell jako zobrazené v těchto příkladech společné atributy:</span><span class="sxs-lookup"><span data-stu-id="82c8b-105">Alternatively, you can change individual users or attributes for synchronized users using powershell such as shown in these common examples:</span></span> 
- <span data-ttu-id="82c8b-106">Sada MsolUser - UserPrincipalName user@yourdomain.onmicrosoft.com - AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span><span class="sxs-lookup"><span data-stu-id="82c8b-106">Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com</span></span>
- <span data-ttu-id="82c8b-107">Sada MsolUser - UserPrincipalName "user@yourdomain.onmicrosoft.com" - DisplayName "Zkoušky uživatelské" - Příjmení "Uživatel"-"Správce" hlava-oddělení "HR"</span><span class="sxs-lookup"><span data-stu-id="82c8b-107">Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"</span></span>
- <span data-ttu-id="82c8b-108">"User@yourdomain.onmicrosoft.com odebrat MsolUser - UserPrincipalName</span><span class="sxs-lookup"><span data-stu-id="82c8b-108">Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com</span></span>