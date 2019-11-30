---
title: Problém aktivace-momentálně se nelze připojit
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3408"
- "9001423"
ms.openlocfilehash: 84e3a7700558ad8a5fad5b7ded6354fe8736e0f7
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/27/2019
ms.locfileid: "39628235"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a><span data-ttu-id="35f36-102">Oprava aplikací sady Office "nelze se nyní připojit".</span><span class="sxs-lookup"><span data-stu-id="35f36-102">Fixing the Office apps "We are unable to connect right now" message</span></span>

<span data-ttu-id="35f36-103">Zobrazí-li se tato zpráva, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="35f36-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="35f36-104">Zkontrolujte bránu firewall, antivirový software a nastavení serveru proxy, abyste potvrdili, že neblokují internetový přístup k aplikacím sady Office.</span><span class="sxs-lookup"><span data-stu-id="35f36-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="35f36-105">Viz [adresy URL sady Office 365 a rozsahy adres IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="35f36-105">See [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="35f36-106">Přejděte ke \*\*\*\* > spuštění**a zadejte**příkaz **Services. msc**.</span><span class="sxs-lookup"><span data-stu-id="35f36-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="35f36-107">Zkontrolujte, zda jsou spuštěny následující služby:</span><span class="sxs-lookup"><span data-stu-id="35f36-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="35f36-108">Automatické nastavení zařízení připojených k síti</span><span class="sxs-lookup"><span data-stu-id="35f36-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="35f36-109">Služba Network list Service</span><span class="sxs-lookup"><span data-stu-id="35f36-109">Network List Service</span></span>
    - <span data-ttu-id="35f36-110">Povědomí o síťovém umístění</span><span class="sxs-lookup"><span data-stu-id="35f36-110">Network Location Awareness</span></span>
    - <span data-ttu-id="35f36-111">Protokol událostí systému Windows</span><span class="sxs-lookup"><span data-stu-id="35f36-111">Windows Event Log</span></span>

<span data-ttu-id="35f36-112">Není-li některá z těchto služeb spuštěna, pokuste se jej spustit.</span><span class="sxs-lookup"><span data-stu-id="35f36-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="35f36-113">Pokud při spouštění služby dojde k potížím, spusťte pomocí příkazového řádku se zvýšenými oprávněními následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="35f36-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="35f36-114">**sfc/scannow**</span><span class="sxs-lookup"><span data-stu-id="35f36-114">**sfc /scannow**</span></span>

<span data-ttu-id="35f36-115">Po dokončení tohoto příkazu restartujte počítač.</span><span class="sxs-lookup"><span data-stu-id="35f36-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="35f36-116">Podrobné informace naleznete v tématu ["Lituji, ale nemůžeme se připojit k vašemu účtu. Při aktivaci sady Office ze sady Office 365 opakujte akci později](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="35f36-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Office 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>