---
title: PowerShell SharePointu Online
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 8c270748fc75f929371fbb2856daad3ae61a1540
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764254"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="efa0e-102">PowerShell SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="efa0e-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="efa0e-103">Pracujete s PowerShellem nebo skripty v Sharepointu Online?</span><span class="sxs-lookup"><span data-stu-id="efa0e-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="efa0e-104">Navštivte níže uvedené odkazy pro více informací.</span><span class="sxs-lookup"><span data-stu-id="efa0e-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="efa0e-105">Začínáme s prostředím pro správu SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="efa0e-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="efa0e-106">Připojení k prostředí SPO PowerShell s vícefaktorovým ověřováním (MFA)</span><span class="sxs-lookup"><span data-stu-id="efa0e-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="efa0e-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) obsahuje knihovnu příkazů prostředí PowerShell, která umožňuje provádět složité akce správy směrem k spo.</span><span class="sxs-lookup"><span data-stu-id="efa0e-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="efa0e-108">Pokud máte problémy s připojením k prostředí správy SPO, ujistěte se, že jste aktualizovali na nejnovější verzi a zkuste [modul znovu importovat](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) pomocí *rozhraní Import-Module Microsoft.Online.SharePoint.PowerShell.*</span><span class="sxs-lookup"><span data-stu-id="efa0e-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="efa0e-109">Pokud se pokoušíte spustit skripty objektového modelu na straně klienta, budete muset mít v místním počítači nainstalovanou sadu [SDK součásti klienta Sharepoint Online.](https://www.microsoft.com/download/details.aspx?id=42038)</span><span class="sxs-lookup"><span data-stu-id="efa0e-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="efa0e-110">Pokud máte problémy se spuštěným skripty z prostředí PowerShell, můžete zvážit spuštění prostředí PowerShell jako správce a změnu [zásad spuštění](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="efa0e-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>