---
title: 2681 Attack Simulator v Microsoftu 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 74bd2dd62b24aaf6c9d7b387ab1d97ddab31e902
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713459"
---
# <a name="attack-simulator-in-microsoft-365"></a><span data-ttu-id="bb0f0-102">Simulátor útoku v Microsoftu 365</span><span class="sxs-lookup"><span data-stu-id="bb0f0-102">Attack Simulator in Microsoft 365</span></span>

- <span data-ttu-id="bb0f0-103">Chybí vám Attack Simulator?</span><span class="sxs-lookup"><span data-stu-id="bb0f0-103">Are you missing Attack Simulator?</span></span> <span data-ttu-id="bb0f0-104">Simulátor útoků vyžaduje **plán ochrany před pokročilými hrozbami Office 365 2 (ATP Plan 2)** nebo **Office 365 Enterprise E5**.</span><span class="sxs-lookup"><span data-stu-id="bb0f0-104">Attack Simulator requires **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** or **Office 365 Enterprise E5**.</span></span> <span data-ttu-id="bb0f0-105">Attack Simulator **není** součástí Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3 nebo žádné předplatná Microsoft 365 Apps pro firmy.</span><span class="sxs-lookup"><span data-stu-id="bb0f0-105">Attack Simulator is **not** included in Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3, or any Microsoft 365 Apps for business subscriptions.</span></span>

- <span data-ttu-id="bb0f0-106">Účet, který používáte ke spuštění simulovaných útoků, vyžaduje oprávnění globálního správce nebo správce zabezpečení a vícefaktorové ověřování (MFA).</span><span class="sxs-lookup"><span data-stu-id="bb0f0-106">The account you use to launch simulated attacks requires global administrator or security administrator permissions and multi-factor authentication (MFA).</span></span> <span data-ttu-id="bb0f0-107">Další informace o požadavcích simulátoru útoku naleznete v [tomto tématu](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span><span class="sxs-lookup"><span data-stu-id="bb0f0-107">For more information about Attack Simulator requirements, see [this topic](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span></span>

- <span data-ttu-id="bb0f0-108">Důležité věci, které je třeba vědět o simulacích útoku **Brute Force Password:**</span><span class="sxs-lookup"><span data-stu-id="bb0f0-108">Important things to know about **Brute Force Password** attack simulations:</span></span>

  - <span data-ttu-id="bb0f0-109">Pokud cílový účet má mfa povoleno a heslo bylo uhádnuto správně, účet se nezobrazí jako ohrožena (druhý faktor ověřování bude neúplné).</span><span class="sxs-lookup"><span data-stu-id="bb0f0-109">If the target account has MFA enabled and the password was guessed correctly, the account will not show as compromised (the second authentication factor will be incomplete).</span></span>

  - <span data-ttu-id="bb0f0-110">Soubor s heslem nesmí být větší než 10 MB.</span><span class="sxs-lookup"><span data-stu-id="bb0f0-110">The password file can't be larger than 10 MB.</span></span> <span data-ttu-id="bb0f0-111">Použijte jedno heslo na řádek a za poslední heslo v seznamu uveďte prázdný řádek (návrat vozíku).</span><span class="sxs-lookup"><span data-stu-id="bb0f0-111">Use one password per line, and include a blank line (carriage return) after the last password in the list.</span></span>

- <span data-ttu-id="bb0f0-112">Důležité informace o **spear phishing připojit** simulace:</span><span class="sxs-lookup"><span data-stu-id="bb0f0-112">Important things to know about **Spear Phishing** attach simulations:</span></span>

  - <span data-ttu-id="bb0f0-113">Podle návrhu nelze zadat vlastní hodnotu adresy **URL přihlašovacího serveru phishing**.</span><span class="sxs-lookup"><span data-stu-id="bb0f0-113">By design, you can't provide a custom value for **Phishing login server URL**.</span></span>

  - <span data-ttu-id="bb0f0-114">Pokud příjemce používá [doplněk Povolit zprávu sestavy](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) k nahlášení zprávy jako phishing, nemusí se vám na zprávu zobrazit upozornění (protože se jedná o simulovaný útok).</span><span class="sxs-lookup"><span data-stu-id="bb0f0-114">If a recipient uses the [Enable the Report Message add-in](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) to report the message as phishing, you might not receive alerts for the message (because this is a simulated attack).</span></span>

- <span data-ttu-id="bb0f0-115">Sestavy: Po dokončení simulovaného útoku můžete přehled zobrazit kliknutím na **Podrobnosti útoku.**</span><span class="sxs-lookup"><span data-stu-id="bb0f0-115">Reports: After the simulated attack is complete, you can click **Attack Details** to see the report.</span></span>

- <span data-ttu-id="bb0f0-116">Podrobné pokyny a nové funkce v Attack Simulator, naleznete [v tématu Attack Simulator v Microsoftu 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="bb0f0-116">For detailed instructions and new features in Attack Simulator, see [Attack Simulator in Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>
