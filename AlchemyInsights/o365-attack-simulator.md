---
title: Simulátor útoku 2681 v Microsoftu 365
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
ms.openlocfilehash: 3dae4768ca62757ce7f92dfc527078c963d72742
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506731"
---
# <a name="attack-simulator-in-microsoft-365"></a><span data-ttu-id="b8446-102">Simulátor útoku v Microsoftu 365</span><span class="sxs-lookup"><span data-stu-id="b8446-102">Attack Simulator in Microsoft 365</span></span>

- <span data-ttu-id="b8446-103">Chybí vám simulátor útoku?</span><span class="sxs-lookup"><span data-stu-id="b8446-103">Are you missing Attack Simulator?</span></span> <span data-ttu-id="b8446-104">Simulátor útoku vyžaduje **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** nebo **Office 365 Enterprise E5**.</span><span class="sxs-lookup"><span data-stu-id="b8446-104">Attack Simulator requires **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** or **Office 365 Enterprise E5**.</span></span> <span data-ttu-id="b8446-105">Simulátor útoku **není** součástí plánu ochrany před pokročilými hrozbami Office 365 1 (plán ATP 1), Office 365 Enterprise E3 ani v žádných předplatných aplikací Microsoft 365 pro firmy.</span><span class="sxs-lookup"><span data-stu-id="b8446-105">Attack Simulator is **not** included in Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3, or any Microsoft 365 Apps for business subscriptions.</span></span>

- <span data-ttu-id="b8446-106">Účet, který používáte ke spuštění simulovaných útoků, vyžaduje oprávnění globálního správce nebo správce zabezpečení a vícefaktorové ověřování (MFA).</span><span class="sxs-lookup"><span data-stu-id="b8446-106">The account you use to launch simulated attacks requires global administrator or security administrator permissions and multi-factor authentication (MFA).</span></span> <span data-ttu-id="b8446-107">Další informace o požadavcích simulátoru útoku naleznete [v tomto tématu](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="b8446-107">For more information about Attack Simulator requirements, see [this topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>

- <span data-ttu-id="b8446-108">Důležité věci vědět o simulacích útoku **hesla Hrubou silou:**</span><span class="sxs-lookup"><span data-stu-id="b8446-108">Important things to know about **Brute Force Password** attack simulations:</span></span>

  - <span data-ttu-id="b8446-109">Pokud má cílový účet povoleno vícefaktorové ověřování a heslo bylo správně uhodnout, účet se nezobrazí jako ohrožené (druhý faktor ověřování bude neúplný).</span><span class="sxs-lookup"><span data-stu-id="b8446-109">If the target account has MFA enabled and the password was guessed correctly, the account will not show as compromised (the second authentication factor will be incomplete).</span></span>

  - <span data-ttu-id="b8446-110">Soubor s heslem nesmí být větší než 10 MB.</span><span class="sxs-lookup"><span data-stu-id="b8446-110">The password file can't be larger than 10 MB.</span></span> <span data-ttu-id="b8446-111">Použijte jedno heslo na řádek a za poslední heslo v seznamu zahrňte prázdný řádek (návrat vozíku).</span><span class="sxs-lookup"><span data-stu-id="b8446-111">Use one password per line, and include a blank line (carriage return) after the last password in the list.</span></span>

- <span data-ttu-id="b8446-112">Důležité věci vědět o **Spear Phishing** připojit simulace:</span><span class="sxs-lookup"><span data-stu-id="b8446-112">Important things to know about **Spear Phishing** attach simulations:</span></span>

  - <span data-ttu-id="b8446-113">Podle návrhu nelze poskytnout vlastní hodnotu adresy URL serveru pro **přihlášení k podvodným zprávám**.</span><span class="sxs-lookup"><span data-stu-id="b8446-113">By design, you can't provide a custom value for **Phishing login server URL**.</span></span>

  - <span data-ttu-id="b8446-114">Pokud příjemce používá [doplněk Povolit zprávu](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) k nahlášení zprávy jako phishingu, nemusí se na zprávu zobrazit upozornění (protože se jedná o simulovaný útok).</span><span class="sxs-lookup"><span data-stu-id="b8446-114">If a recipient uses the [Enable the Report Message add-in](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) to report the message as phishing, you might not receive alerts for the message (because this is a simulated attack).</span></span>

- <span data-ttu-id="b8446-115">Zprávy: Po dokončení simulovaného útoku můžete zprávu zobrazit kliknutím na **Podrobnosti útoku.**</span><span class="sxs-lookup"><span data-stu-id="b8446-115">Reports: After the simulated attack is complete, you can click **Attack Details** to see the report.</span></span>

- <span data-ttu-id="b8446-116">Podrobné pokyny a nové funkce v simulátoru útoků naleznete v [tématu Attack Simulator v Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="b8446-116">For detailed instructions and new features in Attack Simulator, see [Attack Simulator in Microsoft 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>
