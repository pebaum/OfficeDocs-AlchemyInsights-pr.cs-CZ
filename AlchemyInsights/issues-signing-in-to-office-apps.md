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
- "2560"
ms.openlocfilehash: de0a1b78724db9a8e93d8d599ce3b503abcb86e2
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938165"
---
# <a name="fixing-the-office-apps-sorry-another-account-from-your-organization-is-already-signed-in-message"></a><span data-ttu-id="9745f-102">Stanovení "Bohužel jiný účet z organizace je již přihlášen" zprávy aplikací sady Office</span><span class="sxs-lookup"><span data-stu-id="9745f-102">Fixing the Office apps "Sorry, another account from your organization is already signed in" message</span></span>

<span data-ttu-id="9745f-103">Chcete-li tuto chybu vyřešit, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="9745f-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="9745f-104">Odeberte všechny účty práce, s výjimkou ohrožený účet, pomocí > nastavení systému Windows, **přístup k práci nebo ve škole**.</span><span class="sxs-lookup"><span data-stu-id="9745f-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="9745f-105">[Office vymazat pověření](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.</span><span class="sxs-lookup"><span data-stu-id="9745f-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="9745f-106">**Poznámka:** 16.0 změnily cesty registru pro Office 2016.</span><span class="sxs-lookup"><span data-stu-id="9745f-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="9745f-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="9745f-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="9745f-108">Otevřete aplikaci sady Office, zvolte **soubor** > **účtu** > **Odhlásit**. Pak se přihlaste pomocí uživatelského účtu s platnou licencí.</span><span class="sxs-lookup"><span data-stu-id="9745f-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="9745f-109">Podrobné informace naleznete v tématu [účty v sadě Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="9745f-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="9745f-110">Mac viz [nelze přihlásit Office 2016 pro Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="9745f-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>

<span data-ttu-id="9745f-111">Další informace naleznete v tématu ["Bohužel jiný účet z organizace je již přihlášen v tomto počítači" v Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).</span><span class="sxs-lookup"><span data-stu-id="9745f-111">For more information, see ["Sorry, another account from your organization is already signed in on this computer" in Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).</span></span>