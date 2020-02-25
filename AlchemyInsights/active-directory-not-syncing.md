---
title: Nesynchronizace služby Active Directory
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001688"
- "3754"
ms.openlocfilehash: 3abad160ab28922685d235a1fa546105e31757fb
ms.sourcegitcommit: d87a6ac6ee77375d1d750100359b4dc7b2871691
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/25/2020
ms.locfileid: "42265154"
---
# <a name="active-directory-not-syncing"></a><span data-ttu-id="5b022-102">Nesynchronizace služby Active Directory</span><span class="sxs-lookup"><span data-stu-id="5b022-102">Active Directory not syncing</span></span>

<span data-ttu-id="5b022-103">Pokud přijímáte chyby synchronizace, například "žádná nedávná synchronizace", nebo si všimnete stavu synchronizace adresářů na portálu pro správu Office, říká: "Poslední synchronizace před více než 3 dny", může se to být, že AADConnect má nesprávné nastavení nebo nedostatečné oprávnění k provedení synchronizace.</span><span class="sxs-lookup"><span data-stu-id="5b022-103">If you are receiving synchronization errors, such as "no recent synchronization," or notice the directory synchronization status in the Office admin portal says, "Last synced more than 3 days ago," it may be that AADConnect has incorrect settings or insufficient permissions to perform a synchronization.</span></span>  

<span data-ttu-id="5b022-104">Přeinstalace AADConnect pomocí expresního nastavení může problém rychle vyřešit:</span><span class="sxs-lookup"><span data-stu-id="5b022-104">Reinstalling AADConnect by using express settings may resolve the issue quickly:</span></span>

1. <span data-ttu-id="5b022-105">[Stáhněte si nejnovější verzi aadconnectu](https://go.microsoft.com/fwlink/?LinkId=615771).</span><span class="sxs-lookup"><span data-stu-id="5b022-105">[Download the latest version of AADConnect](https://go.microsoft.com/fwlink/?LinkId=615771).</span></span>

2. <span data-ttu-id="5b022-106">[Postupujte podle pokynů pro expresní instalaci](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-install-express).</span><span class="sxs-lookup"><span data-stu-id="5b022-106">[Follow the instructions for express installation](https://docs.microsoft.com/azure/active-directory/hybrid/how-to-connect-install-express).</span></span>

<span data-ttu-id="5b022-107">Další informace o účtech služby AADConnect najdete v tématu [Azure AD Connect: Účty a oprávnění](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-accounts-permissions).</span><span class="sxs-lookup"><span data-stu-id="5b022-107">For more information about AADConnect service accounts, see [Azure AD Connect: Accounts and permissions](https://docs.microsoft.com/azure/active-directory/hybrid/reference-connect-accounts-permissions).</span></span>
