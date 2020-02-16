---
title: Oprava aplikací Office Váš účet je ve špatné zprávě o stavu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: e591c56dd207a5bcb3979be3f66052121100b162
ms.sourcegitcommit: 2572c4e5a981d5f3f556835061c568cfd08b78da
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/27/2019
ms.locfileid: "41969319"
---
# <a name="fixing-the-office-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="e3506-102">Oprava chyby aplikací Office "Váš účet je ve špatném stavu"</span><span class="sxs-lookup"><span data-stu-id="e3506-102">Fixing the Office apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="e3506-103">Chcete-li tuto chybu opravit, vyzkoušejte v ohroženém počítači následující možnosti:</span><span class="sxs-lookup"><span data-stu-id="e3506-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="e3506-104">Otevřete aplikaci Office a vyberte **Souborový** > **účet** > **Odhlásit ze všech účtů**.</span><span class="sxs-lookup"><span data-stu-id="e3506-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="e3506-105">Znovu se přihlaste pomocí uživatelského účtu s platnou licencí.</span><span class="sxs-lookup"><span data-stu-id="e3506-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="e3506-106">Podrobné informace naleznete v tématu [Účty v Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="e3506-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="e3506-107">[Vymazání přihlašovacích údajů sady Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) pomocí Správce pověření systému Windows.</span><span class="sxs-lookup"><span data-stu-id="e3506-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="e3506-108">**Poznámka:** Cesty registru pro Office 2016 se změnily na 16.0.</span><span class="sxs-lookup"><span data-stu-id="e3506-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="e3506-109">Například \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="e3506-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="e3506-110">V ohroženém počítači nastavte enableadal = 0 pomocí následujících kroků:</span><span class="sxs-lookup"><span data-stu-id="e3506-110">On the affected computer, set the EnableADAL = 0 using the following steps:</span></span>  
     1. <span data-ttu-id="e3506-111">Klepněte pravým tlačítkem myši na tlačítko Windows a vyberte **Spustit**.</span><span class="sxs-lookup"><span data-stu-id="e3506-111">Right-click the Windows button and select **Run**.</span></span> <span data-ttu-id="e3506-112">Do pole **Otevřít** zadejte **příkaz regedit**a vyberte **OK**.</span><span class="sxs-lookup"><span data-stu-id="e3506-112">In the **Open** box, type **regedit**, and then select **OK**.</span></span>
     2. <span data-ttu-id="e3506-113">Vyberte **Ano,** pokud budete vyzváni, aby editor registru mohl v zařízení provádět změny.</span><span class="sxs-lookup"><span data-stu-id="e3506-113">Select **Yes** when prompted to allow Registry Editor to make changes to your device.</span></span>
    3. <span data-ttu-id="e3506-114">V Editoru registru přidejte hodnotu DWORD enableadal s nastavením 0 v části HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span><span class="sxs-lookup"><span data-stu-id="e3506-114">In the Registry Editor, add a DWORD value of EnableADAL with a setting of 0 under HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\Identity.</span></span>
- <span data-ttu-id="e3506-115">Pokud k chybě dojde při připojování k Office 365 pomocí Office 2013, [povolte moderní ověřování](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) pro klienta Office.</span><span class="sxs-lookup"><span data-stu-id="e3506-115">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="e3506-116">Další informace najdete v tématu [Řešení potíží s aplikacemi, které nepoužívají prohlížeče a které se nemohou přihlásit k Office 365, Azure nebo Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span><span class="sxs-lookup"><span data-stu-id="e3506-116">For more information, see [How to troubleshoot non-browser apps that can't sign in to Office 365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>

