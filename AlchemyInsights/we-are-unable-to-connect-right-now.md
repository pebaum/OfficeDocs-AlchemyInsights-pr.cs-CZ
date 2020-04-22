---
title: Problém s aktivací – nedaří se nám připojit právě teď
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
ms.openlocfilehash: 56accf68f2cf41dbe6119281b74e2cb56b702789
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716165"
---
# <a name="fixing-the-office-apps-we-are-unable-to-connect-right-now-message"></a><span data-ttu-id="10492-102">Oprava zprávy Opravou aplikací Office "Nejsme se teď schopni připojit"</span><span class="sxs-lookup"><span data-stu-id="10492-102">Fixing the Office apps "We are unable to connect right now" message</span></span>

<span data-ttu-id="10492-103">Pokud se zobrazí tato zpráva, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="10492-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="10492-104">Zkontrolujte bránu firewall, antivirový software a nastavení proxy serveru a ověřte, zda neblokují přístup k Internetu aplikacím Office.</span><span class="sxs-lookup"><span data-stu-id="10492-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Office apps.</span></span> <span data-ttu-id="10492-105">Viz [Adresy URL společnosti Microsoft a rozsahy IP adres](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="10492-105">See [Microsoft URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="10492-106">Přejděte na **spustit** > **a**zadejte **services.msc**.</span><span class="sxs-lookup"><span data-stu-id="10492-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="10492-107">Ujistěte se, že jsou spuštěny všechny následující služby:</span><span class="sxs-lookup"><span data-stu-id="10492-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="10492-108">Automatické nastavení síťových připojených zařízení</span><span class="sxs-lookup"><span data-stu-id="10492-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="10492-109">Služba Seznam sítí</span><span class="sxs-lookup"><span data-stu-id="10492-109">Network List Service</span></span>
    - <span data-ttu-id="10492-110">Povědomí o umístění v síti</span><span class="sxs-lookup"><span data-stu-id="10492-110">Network Location Awareness</span></span>
    - <span data-ttu-id="10492-111">Protokol událostí systému Windows</span><span class="sxs-lookup"><span data-stu-id="10492-111">Windows Event Log</span></span>

<span data-ttu-id="10492-112">Pokud některá z těchto služeb není spuštěna, zkuste ji spustit.</span><span class="sxs-lookup"><span data-stu-id="10492-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="10492-113">Pokud máte problém se spuštěním služby, spusťte následující příkaz otevřením příkazového řádku se zvýšenými oprávněními:</span><span class="sxs-lookup"><span data-stu-id="10492-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="10492-114">**sfc /scannow**</span><span class="sxs-lookup"><span data-stu-id="10492-114">**sfc /scannow**</span></span>

<span data-ttu-id="10492-115">Po dokončení tohoto příkazu restartujte počítač.</span><span class="sxs-lookup"><span data-stu-id="10492-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="10492-116">Podrobné informace najdete [v tématu "Omlouváme se, ale nemůžeme se připojit k vašemu účtu. Zkuste to prosím znovu později" chyba při aktivaci Office z Microsoft u 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="10492-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate Office from Microsoft 365](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>