---
title: Poradce při potížích s odepřením zpráv accessu na weby OneDrivu pro firmy
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: 95bd46e8b7a6006f3735612d9a5602fb2b2a283b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511177"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="e8387-102">Poradce při potížích s odepřením zpráv accessu na weby OneDrivu pro firmy</span><span class="sxs-lookup"><span data-stu-id="e8387-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="e8387-103">K tomuto problému nejčastěji dochází, když je uživatel odstraněn a znovu vytvořen se stejným hlavním názvem uživatele (HLAVNÍ NÁZEV UŽIVATELE).</span><span class="sxs-lookup"><span data-stu-id="e8387-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="e8387-104">Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID).</span><span class="sxs-lookup"><span data-stu-id="e8387-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="e8387-105">Když se uživatel pokusí o přístup k kolekci webů nebo jeho OneDrive, uživatel má nesprávné PUID.</span><span class="sxs-lookup"><span data-stu-id="e8387-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="e8387-106">Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="e8387-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="e8387-107">Pokud se uživatelé již přihlásili ke SharePointu a potom jsou přesunuti do jiné OU a znovu se sharepointem, může se k tomuto problému vyskytnout.</span><span class="sxs-lookup"><span data-stu-id="e8387-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="e8387-108">Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní hlavní číslo uživatele s postupem v článku [Obnovení uživatele v microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span><span class="sxs-lookup"><span data-stu-id="e8387-108">To resolve this issue you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span></span>
2. <span data-ttu-id="e8387-109">Pokud nemůžete obnovit původního uživatele, měli byste odebrat starého uživatele z webu OneDrive pomocí těchto kroků, [odebrat uživatele ze seznamu s informacemi o uživateli]().</span><span class="sxs-lookup"><span data-stu-id="e8387-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="e8387-110">Po dokončení můžete ověřit, že uživatel má práva správce na web OneDrivu podle pokynů k [přidání správce pro OneDrive uživatele.](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span><span class="sxs-lookup"><span data-stu-id="e8387-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles)</span></span>

<span data-ttu-id="e8387-111">Další informace o úrovních oprávnění naleznete v článku [Principy úrovní oprávnění v SharePointu](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="e8387-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
