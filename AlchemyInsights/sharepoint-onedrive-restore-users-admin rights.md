---
title: Poradce při potížích s odezírem zpráv o přístupu na weby OneDrivu pro firmy
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: a83936acf969926c113b28ceb22b006cdb96e2b4
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43692794"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="b5b2c-102">Poradce při potížích s odezírem zpráv o přístupu na weby OneDrivu pro firmy</span><span class="sxs-lookup"><span data-stu-id="b5b2c-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="b5b2c-103">K tomuto problému nejčastěji dochází při odstranění uživatele a znovu vytvořit se stejným hlavním jménem uživatele (UPN).</span><span class="sxs-lookup"><span data-stu-id="b5b2c-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="b5b2c-104">Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID).</span><span class="sxs-lookup"><span data-stu-id="b5b2c-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="b5b2c-105">Když se uživatel pokusí o přístup k kolekci webů nebo k jejich OneDrivu, má nesprávný PUID.</span><span class="sxs-lookup"><span data-stu-id="b5b2c-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="b5b2c-106">Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="b5b2c-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="b5b2c-107">Pokud se uživatelé už přihlásili ke SharePointu a potom jsou přesunuti do jiné oua nové ou a znovu synchronizováni se službou SharePoint, může se u nich vyskytnout tento problém.</span><span class="sxs-lookup"><span data-stu-id="b5b2c-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="b5b2c-108">Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní název uživatele s kroky v [článku, Obnovení uživatele v Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="b5b2c-108">To resolve this issue you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>
2. <span data-ttu-id="b5b2c-109">Pokud nemůžete obnovit původního uživatele, měli byste starého uživatele odebrat z webu OneDrivu pomocí těchto kroků, [odebrat uživatele ze seznamu uživatelských informací]().</span><span class="sxs-lookup"><span data-stu-id="b5b2c-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="b5b2c-110">Po dokončení můžete ověřit, že uživatel má práva správce webu OneDrive podle pokynů k [přidání správce pro OneDrive uživatele.](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span><span class="sxs-lookup"><span data-stu-id="b5b2c-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span></span>

<span data-ttu-id="b5b2c-111">Další informace o úrovních oprávnění najdete v článku [Principy úrovní oprávnění v SharePointu](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="b5b2c-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
