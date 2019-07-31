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
- "2574"
ms.openlocfilehash: 3622a3408b25b43090e9414ae5ffcfc2760264ee
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938166"
---
# <a name="issues-signing-in-to-office-apps"></a><span data-ttu-id="c5dc0-102">Problémy s přihlášením do aplikace sady Office</span><span class="sxs-lookup"><span data-stu-id="c5dc0-102">Issues signing in to Office apps</span></span>

<span data-ttu-id="c5dc0-103">K opravě potíží při přihlašování s aplikací sady Office, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="c5dc0-103">To fix sign-in issues with Office apps, try the following:</span></span>

- <span data-ttu-id="c5dc0-104">Odeberte všechny účty práce, s výjimkou ohrožený účet, pomocí > nastavení systému Windows, **přístup k práci nebo ve škole**.</span><span class="sxs-lookup"><span data-stu-id="c5dc0-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="c5dc0-105">[Office vymazat pověření](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.</span><span class="sxs-lookup"><span data-stu-id="c5dc0-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="c5dc0-106">**Poznámka:** 16.0 změnily cesty registru pro Office 2016.</span><span class="sxs-lookup"><span data-stu-id="c5dc0-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="c5dc0-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="c5dc0-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="c5dc0-108">Otevřete aplikaci sady Office, zvolte **soubor** > **účtu** > **Odhlásit**. Pak se přihlaste pomocí uživatelského účtu s platnou licencí.</span><span class="sxs-lookup"><span data-stu-id="c5dc0-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="c5dc0-109">Podrobné informace naleznete v tématu [účty v sadě Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="c5dc0-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="c5dc0-110">Mac viz [nelze přihlásit Office 2016 pro Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="c5dc0-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>
- <span data-ttu-id="c5dc0-111">Pokud dojde k chybám při připojování k Office 2013 pomocí služeb Office 365, moderní pro ověření klienta sady Office.</span><span class="sxs-lookup"><span data-stu-id="c5dc0-111">If the errors occurs while connecting to Office 365 using Office 2013, enable modern authentication for Office client.</span></span>

<span data-ttu-id="c5dc0-112">Další informace najdete tady:</span><span class="sxs-lookup"><span data-stu-id="c5dc0-112">For more information, see:</span></span>
- [<span data-ttu-id="c5dc0-113">Se nelze přihlásit do služeb Office 365, Azure nebo Intune</span><span class="sxs-lookup"><span data-stu-id="c5dc0-113">You can't sign in to Office 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [<span data-ttu-id="c5dc0-114">Problémy s připojením v přihlášení po aktualizaci Office 2016 sestavení 16.0.7967 v systému Windows 10</span><span class="sxs-lookup"><span data-stu-id="c5dc0-114">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- [<span data-ttu-id="c5dc0-115">"Bohužel jiný účet z organizace je již přihlášen v tomto počítači" v sadě Office</span><span class="sxs-lookup"><span data-stu-id="c5dc0-115">"Sorry, another account from your organization is already signed in on this computer" in Office</span></span>](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [<span data-ttu-id="c5dc0-116">Řešení problémů přihlásit s Office moderní ověřování při použití službou AD FS</span><span class="sxs-lookup"><span data-stu-id="c5dc0-116">Troubleshoot sign-in issues with Office modern authentication when you use ADFS</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)