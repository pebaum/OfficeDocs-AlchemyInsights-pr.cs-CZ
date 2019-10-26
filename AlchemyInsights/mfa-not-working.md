---
title: Problémy s MFA
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.custom:
- "2417"
- "9000557"
ms.openlocfilehash: 276f6b2212c9d85df726cb46a46dee7828b34c89
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "36545152"
---
# <a name="issues-with-mfa"></a><span data-ttu-id="e35d1-102">Problémy s MFA</span><span class="sxs-lookup"><span data-stu-id="e35d1-102">Issues with MFA</span></span>
<span data-ttu-id="e35d1-103">Existuje několik věcí ke kontrole, zda se uživatelé nemohou přihlásit pomocí vícefaktorového ověřování (MFA).</span><span class="sxs-lookup"><span data-stu-id="e35d1-103">There are a couple of things to check if users cannot login using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="e35d1-104">Ohrožený uživatel může být blokován na portálu Azure Active Directory Portal.</span><span class="sxs-lookup"><span data-stu-id="e35d1-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="e35d1-105">V takovém případě budou pokusy o ověření pro tohoto konkrétního uživatele automaticky odepřeny.</span><span class="sxs-lookup"><span data-stu-id="e35d1-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="e35d1-106">Chcete-li je odblokovat, postupujte podle kroků v tomto článku.</span><span class="sxs-lookup"><span data-stu-id="e35d1-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="e35d1-107">Pokud odblokování uživateli nepomůže nebo uživatel není blokován, můžete se pokusit resetovat MFA pro uživatele a znovu projít procesem zápisu.</span><span class="sxs-lookup"><span data-stu-id="e35d1-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="e35d1-108">Postupujte prosím podle pokynů v tomto článku.</span><span class="sxs-lookup"><span data-stu-id="e35d1-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="e35d1-109">V případě, že jste poprvé povolili službu MFA a uživatelé se nemohou přihlásit k jiným klientům než prohlížečům, jako je například aplikace Outlook, Skype atd., není v odběru O365 pravděpodobně povolena služba AD Al (Active Directory Authentication Library).</span><span class="sxs-lookup"><span data-stu-id="e35d1-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="e35d1-110">V takovém případě se budete muset připojit k serveru Exchange Online PowerShell a spustit tuto rutinu:  *set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*</span><span class="sxs-lookup"><span data-stu-id="e35d1-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>