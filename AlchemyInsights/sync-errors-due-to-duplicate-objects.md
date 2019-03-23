---
title: 902 (kvůli duplicitní objekty chyby synchronizace)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: eac74a6d4de58c9cdbdc8e8df8f705293bb12e87
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30781255"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="fe833-102">Chyby synchronizace z duplikovaných objektů</span><span class="sxs-lookup"><span data-stu-id="fe833-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="fe833-103">Po dokončení synchronizace adresáře se může zobrazit jedna z následujících chybových zpráv:</span><span class="sxs-lookup"><span data-stu-id="fe833-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="fe833-104">Nelze aktualizovat objekt v aplikaci Microsoft Online Services, protože mají následující atributy přidružené k tomuto objektu hodnoty, které již mohou být spojen s jiným objektem v místní adresář.</span><span class="sxs-lookup"><span data-stu-id="fe833-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="fe833-105">Synchronizovaného objektu s stejnou adresu proxy serveru již existuje v adresáři služby Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="fe833-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="fe833-106">Nelze aktualizovat objekt, protože mají následující atributy přidružené k tomuto objektu hodnoty, které již mohou být spojen s jiným objektem v místní adresářové služby: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="fe833-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="fe833-107">Identifikovat a vyřešit tento problém, stáhněte a spusťte [Nástroj náprava chyb IdFix DirSync](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="fe833-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="fe833-108">Další informace naleznete v tématu [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="fe833-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  

