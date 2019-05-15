---
title: Nelze odstranit položky služby SharePoint nebo OneDrive
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 21d7b928fade48a6729c120e6ea33b16dafe799e
ms.sourcegitcommit: 22ce2315c8cf643137ab3420cdc1cda41433d44a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/14/2019
ms.locfileid: "34057688"
---
# <a name="unable-to-delete-items"></a>Nelze odstranit položky

S odstraněním problémů?

- Vždy zkontrolujte, zda že máte [příslušná oprávnění](https://docs.microsoft.com/en-us/sharepoint/default-sharepoint-groups) k odstranění položky nebo mít požadavek na [správce kolekce webů](https://docs.microsoft.com/en-us/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) položku odebrat.

- Ujistěte se, že není nastavení [zásad pro uchovávání informací](https://docs.microsoft.com/en-us/office365/securitycompliance/retention-policies) o položce.

- Zkontrolujte, zda že položka není [rezervován](https://support.office.com/en-us/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) jiným uživatelem.

- Nakonec mohou správci [služby SharePoint vzory a postupy](https://docs.microsoft.com/en-us/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) obsahující knihovnu PowerShell příkazy, které umožňují provádět akce komplexní správy Vynutit odstranění stubborn položek. 
- [Odebrání PNP souboru](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Odebrat složku PNP](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Odebrat položku seznamu PNP](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Odebrání seznamu PNP](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Odebrání PNP pole (sloupec)](https://docs.microsoft.com/en-us/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)