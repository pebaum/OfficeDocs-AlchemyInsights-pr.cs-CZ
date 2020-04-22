---
title: Problémy s přihlášením k aplikacím Office
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
ms.openlocfilehash: 695d449a876c22ff441da2367ef67aaea470eb66
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43762974"
---
# <a name="issues-signing-in-to-office-apps"></a><span data-ttu-id="8b935-102">Problémy s přihlášením k aplikacím Office</span><span class="sxs-lookup"><span data-stu-id="8b935-102">Issues signing in to Office apps</span></span>

<span data-ttu-id="8b935-103">Pokud chcete vyřešit problémy s přihlášením k aplikacím Office, vyzkoušejte následující:</span><span class="sxs-lookup"><span data-stu-id="8b935-103">To fix sign-in issues with Office apps, try the following:</span></span>

- <span data-ttu-id="8b935-104">Odebrání všech pracovních účtů s výjimkou ovlivněných účtů pomocí nastavení systému Windows > **práci nebo škole aplikace Access**.</span><span class="sxs-lookup"><span data-stu-id="8b935-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="8b935-105">[Zrušte přihlašovací údaje Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.</span><span class="sxs-lookup"><span data-stu-id="8b935-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="8b935-106">**Poznámka:** Cesty registru pro Office 2016 se změnily na 16.0.</span><span class="sxs-lookup"><span data-stu-id="8b935-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="8b935-107">(Např.: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="8b935-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="8b935-108">Otevřete aplikaci Office a zvolte**Odhlásit**se z**účtu** >  **.** >  Poté se přihlaste pomocí uživatelského účtu s platnou licencí.</span><span class="sxs-lookup"><span data-stu-id="8b935-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="8b935-109">Podrobné informace najdete v článku [Účty v Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="8b935-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="8b935-110">V případě Macu si projděte téma [Nejde se přihlásit k aplikaci Office 2016 pro Mac](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="8b935-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>
- <span data-ttu-id="8b935-111">Pokud dojde k chybám při připojování k Microsoftu 365 pomocí Office 2013, povolte moderní ověřování pro klienta Office.</span><span class="sxs-lookup"><span data-stu-id="8b935-111">If the errors occurs while connecting to Microsoft 365 using Office 2013, enable modern authentication for Office client.</span></span>

<span data-ttu-id="8b935-112">Další informace najdete tady:</span><span class="sxs-lookup"><span data-stu-id="8b935-112">For more information, see:</span></span>
- [<span data-ttu-id="8b935-113">Nemůžete se přihlásit k Microsoftu 365, Azure nebo Intune.</span><span class="sxs-lookup"><span data-stu-id="8b935-113">You can't sign in to Microsoft 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)
- [<span data-ttu-id="8b935-114">Problémy s připojením při přihlášení po aktualizaci office 2016 sestavení 16.0.7967 ve Windows 10</span><span class="sxs-lookup"><span data-stu-id="8b935-114">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)
- [<span data-ttu-id="8b935-115">"Omlouváme se, ale jiný účet z vaší organizace je již přihlášen v tomto počítači" v Office</span><span class="sxs-lookup"><span data-stu-id="8b935-115">"Sorry, another account from your organization is already signed in on this computer" in Office</span></span>](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in)
- [<span data-ttu-id="8b935-116">Poradce při potížích s přihlášením s moderním ověřováním Office při použití služby ADFS</span><span class="sxs-lookup"><span data-stu-id="8b935-116">Troubleshoot sign-in issues with Office modern authentication when you use ADFS</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-issue-with-modern-auth)