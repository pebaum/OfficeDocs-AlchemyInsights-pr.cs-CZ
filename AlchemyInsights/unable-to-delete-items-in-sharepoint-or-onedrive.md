---
title: Nelze odstranit položky ve službě SharePoint nebo OneDrive.
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: 3cc168846999c6880b95edfaedb2df8cf6e843a6
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36748533"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="31a82-102">Nelze odstranit položky.</span><span class="sxs-lookup"><span data-stu-id="31a82-102">Unable to delete items</span></span>

<span data-ttu-id="31a82-103">Máte problémy s odstraňováním položek služby SharePoint?</span><span class="sxs-lookup"><span data-stu-id="31a82-103">Having issues deleting SharePoint items?</span></span>

- <span data-ttu-id="31a82-104">Vždy se ujistěte, že máte [příslušná oprávnění](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) k odstranění položky nebo požádejte [správce kolekce webů](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) o odebrání položky.</span><span class="sxs-lookup"><span data-stu-id="31a82-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="31a82-105">Ujistěte se, že u položky není k dispozici nastavení [zásad uchovávání informací](https://docs.microsoft.com/office365/securitycompliance/retention-policies) .</span><span class="sxs-lookup"><span data-stu-id="31a82-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="31a82-106">Zajistěte, aby položka nebyla [rezervována](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) jinému uživateli.</span><span class="sxs-lookup"><span data-stu-id="31a82-106">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="31a82-107">Nakonec mohou správci použít [vzory a postupy služby SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP), které obsahují knihovnu příkazů prostředí PowerShell, která umožňuje provádět složité akce správy, jako je například vynucení odstranění tvrdošíjných položek.</span><span class="sxs-lookup"><span data-stu-id="31a82-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="31a82-108">Odebrat soubor PNP</span><span class="sxs-lookup"><span data-stu-id="31a82-108">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="31a82-109">Odebrat složku PNP</span><span class="sxs-lookup"><span data-stu-id="31a82-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="31a82-110">Odebrat položku seznamu PNP</span><span class="sxs-lookup"><span data-stu-id="31a82-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="31a82-111">Odebrat seznam PNP</span><span class="sxs-lookup"><span data-stu-id="31a82-111">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="31a82-112">Odebrat pole PNP (sloupec)</span><span class="sxs-lookup"><span data-stu-id="31a82-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)