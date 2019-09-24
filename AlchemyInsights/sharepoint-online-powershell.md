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
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="34162-102">Prostředí SharePoint Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="34162-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="34162-103">Práce s PowerShell nebo skripty v rámci služby SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="34162-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="34162-104">Další informace získáte na níže uvedených odkazech.</span><span class="sxs-lookup"><span data-stu-id="34162-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="34162-105">Začínáme s prostředím služby SharePoint Online pro správu</span><span class="sxs-lookup"><span data-stu-id="34162-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="34162-106">Připojení k SPO PowerShell s vícefaktorové autentizaci (MFA)</span><span class="sxs-lookup"><span data-stu-id="34162-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="34162-107">[Vzory a postupy služby SharePoint (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) obsahují knihovnu příkazů prostředí PowerShell, která umožňuje provádět složité akce správy na serveru spo.</span><span class="sxs-lookup"><span data-stu-id="34162-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="34162-108">Pokud máte problémy s připojením k prostředí správy SPO, ujistěte se, že jste aktualizovali na nejnovější verzi a zkuste [modul znovu importovat](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) pomocí *"Import-Module Microsoft. online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="34162-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="34162-109">Pokud se pokoušíte spustit skripty objektového modelu na straně klienta, je třeba mít v místním počítači nainstalovánu [sadu SDK pro klientské součásti služby SharePoint Online](https://www.microsoft.com/download/details.aspx?id=42038) .</span><span class="sxs-lookup"><span data-stu-id="34162-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="34162-110">Máte-li problémy se spouštěním skriptů z prostředí PowerShell, můžete zvážit spuštění prostředí PowerShell jako správce a změnu [zásad spuštění](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="34162-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>