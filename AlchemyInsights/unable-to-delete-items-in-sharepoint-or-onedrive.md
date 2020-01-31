---
title: Nelze odstranit položky v SharePointu nebo OneDrivu.
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: abfcb91c6040aeed759d697ca63546ccea8ede97
ms.sourcegitcommit: c5e800313a6f211386a384716e5fa18e7fcc8c1c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/28/2020
ms.locfileid: "41571235"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="fccba-102">Nelze odstranit položky.</span><span class="sxs-lookup"><span data-stu-id="fccba-102">Unable to delete items</span></span>

<span data-ttu-id="fccba-103">Zásady uchovávání informací mohou způsobit toto, je třeba zakázat nebo vyloučit příslušné blokování, které je příčinou tohoto problému.</span><span class="sxs-lookup"><span data-stu-id="fccba-103">Retention policies can cause this, you need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="fccba-104">Po odebrání zásad uchovávání informací nebo blokování může trvat až 24 hodin, než se změna projeví.</span><span class="sxs-lookup"><span data-stu-id="fccba-104">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> <span data-ttu-id="fccba-105">Ujistěte se, že není nastavení [zásad uchovávání informací](https://docs.microsoft.com/office365/securitycompliance/retention-policies) pro položku.</span><span class="sxs-lookup"><span data-stu-id="fccba-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

<span data-ttu-id="fccba-106">Web pravděpodobně překročil limit úložiště, zvýšil [kvótu webu](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) a odstranil položku.</span><span class="sxs-lookup"><span data-stu-id="fccba-106">The site might have exceeded storage limit, increase the [site quota](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) and delete the item.</span></span>

<span data-ttu-id="fccba-107">Ujistěte se, že položka není rezervována jinému [uživateli.](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de)</span><span class="sxs-lookup"><span data-stu-id="fccba-107">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

<span data-ttu-id="fccba-108">Správci mohou nakonec používat [sharepointové vzory a postupy](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP), která obsahuje knihovnu příkazů prostředí PowerShell, které umožňují provádět složité akce správy, jako je vynucení odstranění tvrdohlavých položek.</span><span class="sxs-lookup"><span data-stu-id="fccba-108">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="fccba-109">Odebrání souboru PNP</span><span class="sxs-lookup"><span data-stu-id="fccba-109">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="fccba-110">Odebrání složky PNP</span><span class="sxs-lookup"><span data-stu-id="fccba-110">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="fccba-111">Odebrat položku seznamu PNP</span><span class="sxs-lookup"><span data-stu-id="fccba-111">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="fccba-112">Odebrat seznam PNP</span><span class="sxs-lookup"><span data-stu-id="fccba-112">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="fccba-113">Odebrat pole PNP (sloupec)</span><span class="sxs-lookup"><span data-stu-id="fccba-113">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)