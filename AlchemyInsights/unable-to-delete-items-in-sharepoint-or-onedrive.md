---
title: Nelze odstranit položky služby SharePoint nebo OneDrive
ms.author: kirks
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
ms.openlocfilehash: b25e6d144dcefcfed4258e78ad5cfd4089ba7d1e
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36558646"
---
# <a name="unable-to-delete-items"></a>Nelze odstranit položky

Máte problémy s odstraněním položky služby SharePoint?

- Vždy zkontrolujte, zda že máte [příslušná oprávnění](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) k odstranění položky nebo mít požadavek na [správce kolekce webů](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) položku odebrat.

- Ujistěte se, že není nastavení [zásad pro uchovávání informací](https://docs.microsoft.com/office365/securitycompliance/retention-policies) o položce.

- Zkontrolujte, zda že položka není [rezervován](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) jiným uživatelem.

- Nakonec mohou správci [služby SharePoint vzory a postupy](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) obsahující knihovnu PowerShell příkazy, které umožňují provádět akce komplexní správy Vynutit odstranění stubborn položek.
- [Odebrání PNP souboru](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Odebrat složku PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Odebrat položku seznamu PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Odebrání seznamu PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Odebrání PNP pole (sloupec)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)