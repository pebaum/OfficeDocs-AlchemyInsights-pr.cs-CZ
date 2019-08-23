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
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36545152"
---
# <a name="issues-with-mfa"></a><span data-ttu-id="a748a-102">Problémy s MFA</span><span class="sxs-lookup"><span data-stu-id="a748a-102">Issues with MFA</span></span>
<span data-ttu-id="a748a-103">Existuje několik věcí, chcete-li zkontrolovat, pokud uživatelé nelze přihlásit pomocí vícenásobné ověření (MFA)</span><span class="sxs-lookup"><span data-stu-id="a748a-103">There are a couple of things to check if users cannot login using multi-factor authentication (MFA)</span></span>

1. <span data-ttu-id="a748a-104">V Azure Active Directory portálu mohou být blokovány příslušného uživatele.</span><span class="sxs-lookup"><span data-stu-id="a748a-104">The affected user may be blocked in Azure Active Directory Portal.</span></span> <span data-ttu-id="a748a-105">Pokud tomu tak je, pokusy o ověření, pro který bude uživatel automaticky zamítnut.</span><span class="sxs-lookup"><span data-stu-id="a748a-105">If that is the case, Authentication attempts for that specific user will be automatically denied.</span></span> [<span data-ttu-id="a748a-106">Postupujte podle kroků v tomto článku, chcete-li zrušit jejich blokování.</span><span class="sxs-lookup"><span data-stu-id="a748a-106">Please follow the steps in this article to unblock them.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-mfasettings#block-and-unblock-users)

2. <span data-ttu-id="a748a-107">Pokud vám nepomohlo odblokování uživatele nebo uživatel nebyl blokován můžete zkusit obnovit MFA pro uživatele a přejde prostřednictvím procesu zapsat znovu.</span><span class="sxs-lookup"><span data-stu-id="a748a-107">If unblocking the user didn't help or the user is not blocked you can try to reset MFA for the user and they will go through the enroll process again.</span></span> [<span data-ttu-id="a748a-108">Postupujte podle kroků v tomto článku.</span><span class="sxs-lookup"><span data-stu-id="a748a-108">Please follow the steps in this article.</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/howto-mfa-userdevicesettings#require-users-to-provide-contact-methods-again)

<span data-ttu-id="a748a-109">Pokud je to poprvé MFA povoleno a uživatelé se nelze se přihlásit k jiné prohlížeče klientů aplikace Outlook, Skype atd, případně ADAL (Active Directory ověřování knihovny) není povolena na předplatné O365.</span><span class="sxs-lookup"><span data-stu-id="a748a-109">If this is the first time you enabled MFA and your users are unable to login to non-browsers clients such as Outlook, Skype, etc, perhaps ADAL (Active Directory Authentication Library) is not enabled on your O365 subscription.</span></span> <span data-ttu-id="a748a-110">V takovém případě musíte se připojit k serveru Exchange Online Powershell a spustit tuto rutinu:  *Set-OrganizationConfig-OAuth2ClientProfileEnabled: $true*</span><span class="sxs-lookup"><span data-stu-id="a748a-110">In this case you will need to connect to Exchange Online Powershell and run this cmdlet:  *Set-OrganizationConfig -OAuth2ClientProfileEnabled:$true*</span></span>