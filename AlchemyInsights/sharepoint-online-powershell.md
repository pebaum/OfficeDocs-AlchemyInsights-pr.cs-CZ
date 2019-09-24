---
title: Prostředí SharePoint Online PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/23/2019
ms.locfileid: "37122992"
---
# <a name="sharepoint-online-powershell"></a>Prostředí SharePoint Online PowerShell

Práce s PowerShell nebo skripty v rámci služby SharePoint Online? Další informace získáte na níže uvedených odkazech.
- [Začínáme s prostředím služby SharePoint Online pro správu](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [Připojení k SPO PowerShell s vícefaktorové autentizaci (MFA)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- [Vzory a postupy služby SharePoint (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) obsahují knihovnu příkazů prostředí PowerShell, která umožňuje provádět složité akce správy na serveru spo.

> [!NOTE]
> - Pokud máte problémy s připojením k prostředí správy SPO, ujistěte se, že jste aktualizovali na nejnovější verzi a zkuste [modul znovu importovat](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) pomocí *"Import-Module Microsoft. online. SharePoint. PowerShell".*
> - Pokud se pokoušíte spustit skripty objektového modelu na straně klienta, je třeba mít v místním počítači nainstalovánu [sadu SDK pro klientské součásti služby SharePoint Online](https://www.microsoft.com/download/details.aspx?id=42038) .
> - Máte-li problémy se spouštěním skriptů z prostředí PowerShell, můžete zvážit spuštění prostředí PowerShell jako správce a změnu [zásad spuštění](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).