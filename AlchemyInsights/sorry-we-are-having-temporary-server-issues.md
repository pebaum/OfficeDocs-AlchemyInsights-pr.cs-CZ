---
title: Oprava aplikací sady Office Omlouváme se, došlo k dočasné chybě serveru.
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: 4b90f843843416408d7f3091325fe436dc3ec9df
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627983"
---
# <a name="fixing-the-office-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="189af-102">Oprava aplikací sady Office "Promiňte, dochází k dočasným potížím se serverem"</span><span class="sxs-lookup"><span data-stu-id="189af-102">Fixing the Office apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="189af-103">Zobrazí-li se tato zpráva, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="189af-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="189af-104">Zkontrolujte bránu firewall, antivirový software a nastavení serveru proxy, abyste potvrdili, že neblokují internetový přístup k aplikacím sady Office.</span><span class="sxs-lookup"><span data-stu-id="189af-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="189af-105">Viz [adresy URL sady Office 365 a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="189af-105">See [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="189af-106">Přejděte ke \*\*\*\* > spuštění**a zadejte**příkaz **Services. msc**.</span><span class="sxs-lookup"><span data-stu-id="189af-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="189af-107">Zkontrolujte, zda jsou spuštěny následující služby:</span><span class="sxs-lookup"><span data-stu-id="189af-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="189af-108">Automatické nastavení zařízení připojených k síti</span><span class="sxs-lookup"><span data-stu-id="189af-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="189af-109">Služba Network list Service</span><span class="sxs-lookup"><span data-stu-id="189af-109">Network List Service</span></span>
    - <span data-ttu-id="189af-110">Povědomí o síťovém umístění</span><span class="sxs-lookup"><span data-stu-id="189af-110">Network Location Awareness</span></span>
    - <span data-ttu-id="189af-111">Protokol událostí systému Windows</span><span class="sxs-lookup"><span data-stu-id="189af-111">Windows Event Log</span></span>

<span data-ttu-id="189af-112">Není-li některá z těchto služeb spuštěna, pokuste se jej spustit.</span><span class="sxs-lookup"><span data-stu-id="189af-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="189af-113">Pokud při spouštění služby dojde k potížím, spusťte pomocí příkazového řádku se zvýšenými oprávněními následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="189af-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="189af-114">**sfc/scannow**</span><span class="sxs-lookup"><span data-stu-id="189af-114">**sfc /scannow**</span></span>

<span data-ttu-id="189af-115">Po dokončení tohoto příkazu restartujte počítač.</span><span class="sxs-lookup"><span data-stu-id="189af-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="189af-116">Podrobné informace naleznete v tématu ["Lituji, ale nemůžeme se připojit k vašemu účtu. Při aktivaci sady Office ze sady Office 365 opakujte akci později](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="189af-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>