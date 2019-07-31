---
title: Problémy s přihlášením do aplikace sady Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938167"
---
# <a name="blank-sign-in-screen-in-office-apps"></a><span data-ttu-id="c2901-102">Prázdná obrazovka přihlášení do aplikací sady Office</span><span class="sxs-lookup"><span data-stu-id="c2901-102">Blank sign-in screen in Office apps</span></span>

<span data-ttu-id="c2901-103">Chcete-li tento problém vyřešit, zkuste následující postup:</span><span class="sxs-lookup"><span data-stu-id="c2901-103">To fix this issue, try the following:</span></span>
- <span data-ttu-id="c2901-104">Nainstalujte nejnovější aktualizace pro [systém Windows](https://support.microsoft.com/help/4027667/windows-10-update) a [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="c2901-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="c2901-105">Obnovení nastavení aplikace Internet Explorer: přejděte na **Nástroje** > **Možnosti Internetu** > **Upřesnit** > **Obnovení nastavení aplikace Internet Explorer** (Všimněte si, že dojde ke ztrátě vlastního nastavení) a potom zkuste znovu přihlásit k Office.</span><span class="sxs-lookup"><span data-stu-id="c2901-105">Reset Internet Explorer options: Go to **Tools** > **Internet Options** > **Advanced** > **Reset Internet Explorer Settings** (note that you will lose custom settings), and then try signing in to Office again.</span></span>
- <span data-ttu-id="c2901-106">Zakázání součásti Windows Defender aplikace Guard (WDAG) nebo podobný program brány firewall nebo antivirového programu:</span><span class="sxs-lookup"><span data-stu-id="c2901-106">Disable the Windows Defender Application Guard (WDAG) or any similar firewall or anti-virus program:</span></span>
    1. <span data-ttu-id="c2901-107">V Ovládacích panelech přejděte na položku **programy**a pak zvolte **Zapnout funkce systému Windows zapnout nebo vypnout**.</span><span class="sxs-lookup"><span data-stu-id="c2901-107">In Control Panel, go to **Programs**, and then choose **Turn Windows features on or off**.</span></span>
    2. <span data-ttu-id="c2901-108">Pokud je povolena ochrana aplikace Windows Defender, zkuste ji vypnout.</span><span class="sxs-lookup"><span data-stu-id="c2901-108">If Windows Defender Application Guard is enabled, try disabling it.</span></span><br/>
    <span data-ttu-id="c2901-109">**Poznámka:** Musíte restartovat počítač.</span><span class="sxs-lookup"><span data-stu-id="c2901-109">**Note:** You may need to restart the computer.</span></span>
- <span data-ttu-id="c2901-110">Ujistěte se, že Microsoft.AAD.BrokerPlugin [WAM Poplašné plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) nejsou blokovány všechny aplikace nebo program brány firewall nebo antivirové.</span><span class="sxs-lookup"><span data-stu-id="c2901-110">Ensure that the Microsoft.AAD.BrokerPlugin [AAD WAM plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) is not being blocked by any application or firewall/anti-virus program.</span></span>
- <span data-ttu-id="c2901-111">[Office vymazat pověření](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.</span><span class="sxs-lookup"><span data-stu-id="c2901-111">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="c2901-112">**Poznámka:** 16.0 změnily cesty registru pro Office 2016.</span><span class="sxs-lookup"><span data-stu-id="c2901-112">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="c2901-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="c2901-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>

<span data-ttu-id="c2901-114">Další informace naleznete v tématu [připojení problémy v přihlášení po aktualizaci Office 2016 sestavení 16.0.7967 v systému Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="c2901-114">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>