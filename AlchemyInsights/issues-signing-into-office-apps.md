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
- "2559"
ms.openlocfilehash: 5f500ecf1f779fb1be4d257fd050a3ad054087dc
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938168"
---
# <a name="fixing-the-office-apps-your-computers-trusted-platform-module-is-not-functioning-properly-message"></a><span data-ttu-id="364da-102">Řešení Office apps "modul důvěryhodné platformy v počítači nepracuje správně" zpráva</span><span class="sxs-lookup"><span data-stu-id="364da-102">Fixing the Office apps "Your computer's Trusted Platform module is not functioning properly" message</span></span>

<span data-ttu-id="364da-103">Chcete-li tuto chybu vyřešit, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="364da-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="364da-104">Nainstalujte nejnovější aktualizace pro [systém Windows](https://support.microsoft.com/help/4027667/windows-10-update) a [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="364da-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="364da-105">[Office vymazat pověření](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.</span><span class="sxs-lookup"><span data-stu-id="364da-105">[Clear Office credentials](https://docs.microsoft.com/eoffice/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="364da-106">**Poznámka:** 16.0 změnily cesty registru pro Office 2016.</span><span class="sxs-lookup"><span data-stu-id="364da-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="364da-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="364da-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="364da-108">Zkuste [proces obnovení uživatele](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) Chcete-li opravit chyby Trusted Platform Module (TPM).</span><span class="sxs-lookup"><span data-stu-id="364da-108">Try the [user recovery process](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-2) to fix Trusted Platform Module (TPM) failures.</span></span>
- <span data-ttu-id="364da-109">Nastavit EnableADAL = 0, pomocí následujících kroků:</span><span class="sxs-lookup"><span data-stu-id="364da-109">Set the EnableADAL = 0 using the following steps:</span></span>  
    1. <span data-ttu-id="364da-110">Klepněte pravým tlačítkem myši na tlačítko Start systému Windows, zvolte **Spustit**, zadejte **příkaz regedit**a klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="364da-110">Right-click the Windows Start button, choose **Run**, type **regedit**, and then choose **OK**.</span></span>
    2. <span data-ttu-id="364da-111">Vyberte **Ano** editoru registru provádět změny zařízení.</span><span class="sxs-lookup"><span data-stu-id="364da-111">Select **Yes** to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="364da-112">V editoru registru přidejte hodnotu DWORD **EnableADAL** na hodnotu **0** v HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="364da-112">In Registry Editor, add a DWORD value of **EnableADAL** with a setting of **0** under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>

<span data-ttu-id="364da-113">Další informace naleznete v tématu [připojení problémy v přihlášení po aktualizaci Office 2016 sestavení 16.0.7967 v systému Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="364da-113">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>