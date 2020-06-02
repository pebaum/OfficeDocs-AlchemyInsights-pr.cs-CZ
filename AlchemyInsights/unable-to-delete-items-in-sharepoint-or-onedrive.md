---
title: Nelze odstranit položky na SharePointu nebo OneDrivu.
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
ms.openlocfilehash: 8647b65c52a782ca48ca58bb2700556db528796b
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511969"
---
# <a name="unable-to-delete-items"></a>Nelze odstranit položky.

Zásady uchovávání informací může způsobit to, je třeba buď zakázat nebo vyloučit příslušné blokování, které je příčinou tohoto problému. Po odebrání zásad uchovávání informací nebo blokování může trvat až 24 hodin, než se změna projeví. Ujistěte se, že není nastavení [zásad uchovávání informací](https://docs.microsoft.com/microsoft-365/compliance/retention-policies) na položku.

Web mohl překročit limit úložiště, zvýšit [kvótu webu](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) a odstranit položku.

Ujistěte se, že položka není [rezervována](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) pro jiného uživatele.

Nakonec mohou správci používat [vzory a postupy služby SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP), která obsahuje knihovnu příkazů prostředí PowerShell, které umožňují provádět složité akce správy, jako je například vynucení odstranění nepodmíněných položek.
- [Odebrání souboru PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [Odebrání složky PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [Odebrat položku seznamu PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [Odebrat seznam PNP](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [Odebrat pole PNP (sloupec)](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)