---
title: Poradce při potížích s odepřením přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 9430b9786b35dda9fb2604fb6ae3c39c8c258d6e
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44505372"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a><span data-ttu-id="94c36-102">Poradce při potížích se zprávami o odepření přístupu v Centru pro správu Sharepointu/OneDrivu</span><span class="sxs-lookup"><span data-stu-id="94c36-102">Troubleshoot Access Denied messages in Sharepoint/OneDrive Admin Center</span></span>

<span data-ttu-id="94c36-103">Pokud se při pokusu o přechod do Centra pro správu Sharepointu/OneDrivu zobrazuje zpráva o odepření přístupu, ujistěte se, že [uživateli přiřadíte licenci](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span><span class="sxs-lookup"><span data-stu-id="94c36-103">If you are receiving an access denied message when attempting to browse to a Sharepoint/OneDrive Admin Center, please make sure that you [assign a license to the user](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).</span></span> <span data-ttu-id="94c36-104">Pokud má uživatel licenci, měli byste se také ujistit, že je [mu přiřazena role správce,](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) která má přístup k centrům pro správu.</span><span class="sxs-lookup"><span data-stu-id="94c36-104">If the user has a license, you should also make sure they are [assigned an administrator role](hhttps://docs.microsoft.com/microsoft-365/admin/add-users/about-admin-roles) that can access the admin centers.</span></span>

<span data-ttu-id="94c36-105">K tomuto problému může dojít také při odstranění uživatele a znovu vytvořit se stejným hlavním názvem uživatele (HLAVNÍ NÁZEV UŽIVATELE).</span><span class="sxs-lookup"><span data-stu-id="94c36-105">This issue can also occur when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="94c36-106">Nový účet je vytvořen pomocí jiné hodnoty PUID (Passport Unique ID).</span><span class="sxs-lookup"><span data-stu-id="94c36-106">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="94c36-107">Když se uživatel pokusí o přístup k kolekci webů nebo jeho OneDrive, uživatel má nesprávné PUID.</span><span class="sxs-lookup"><span data-stu-id="94c36-107">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="94c36-108">Druhý scénář zahrnuje synchronizaci adresářů s organizační jednotkou služby Active Directory (OU).</span><span class="sxs-lookup"><span data-stu-id="94c36-108">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="94c36-109">Pokud se uživatelé již přihlásili ke SharePointu a potom jsou přesunuti do jiné OU a znovu se sharepointem, může se k tomuto problému vyskytnout.</span><span class="sxs-lookup"><span data-stu-id="94c36-109">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

<span data-ttu-id="94c36-110">Chcete-li tento problém vyřešit, měli byste obnovit původní hlavní hlavní číslo uživatele s postupem v článku [Obnovení uživatele v microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span><span class="sxs-lookup"><span data-stu-id="94c36-110">To resolve this issue, you should restore the original UPN with the steps in the article, [Restore a user in Microsoft 365](https://docs.microsoft.com/microsoft-365/admin/add-users/restore-user).</span></span>

<span data-ttu-id="94c36-111">Poznámka: Pokud OneDrive nebo Centrum pro správu SharePointu není dostupné více uživatelům, kteří k nim dříve měli přístup, může se nastat problém s dočasnými službami.</span><span class="sxs-lookup"><span data-stu-id="94c36-111">Note: If a OneDrive or SharePoint Admin center is not available to multiple users who previously had access, there may be a temporary service issue.</span></span>  <span data-ttu-id="94c36-112">[Zkontrolujte řídicí panel stavu služby](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="94c36-112">[Check the service health dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>


