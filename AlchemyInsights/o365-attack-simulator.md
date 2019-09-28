---
title: 2681 simulátor útoků v sadě Office 365
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "2681"
ms.assetid: ''
ms.openlocfilehash: 07d7622c00074f7bd0d567185824db448f1eeef3
ms.sourcegitcommit: 7232b48bcd8bb9867d52a2f055a46ce76a58b8da
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/27/2019
ms.locfileid: "37305325"
---
# <a name="attack-simulator-in-office-365"></a><span data-ttu-id="2b0db-102">Simulátor útoků v sadě Office 365</span><span class="sxs-lookup"><span data-stu-id="2b0db-102">Attack Simulator in Office 365</span></span>

- <span data-ttu-id="2b0db-103">Chybí simulátor útoku?</span><span class="sxs-lookup"><span data-stu-id="2b0db-103">Are you missing Attack Simulator?</span></span> <span data-ttu-id="2b0db-104">Simulátor útoku vyžaduje **sadu office 365 pokročilý plán ochrany proti ohrožení 2 (plán ATP 2)** nebo **Office 365 Enterprise E5**.</span><span class="sxs-lookup"><span data-stu-id="2b0db-104">Attack Simulator requires **Office 365 Advanced Threat Protection Plan 2 (ATP Plan 2)** or **Office 365 Enterprise E5**.</span></span> <span data-ttu-id="2b0db-105">Simulátor útoků **není zahrnut v** sadě Office 365 pokročilý plán ochrany proti ohrožení 1 (plán ATP 1), Office 365 Enterprise E3 nebo jakýkoli Office 365 firemní předplatné.</span><span class="sxs-lookup"><span data-stu-id="2b0db-105">Attack Simulator is **not** included in Office 365 Advanced Threat Protection Plan 1 (ATP Plan 1), Office 365 Enterprise E3, or any Office 365 Business subscriptions.</span></span>

- <span data-ttu-id="2b0db-106">Účet, který používáte ke spouštění simulovaných útoků, vyžaduje globální správce nebo oprávnění správce zabezpečení a vícefaktorové ověřování (MFA).</span><span class="sxs-lookup"><span data-stu-id="2b0db-106">The account you use to launch simulated attacks requires global administrator or security administrator permissions and multi-factor authentication (MFA).</span></span> <span data-ttu-id="2b0db-107">Další informace o požadavcích na simulátor útoku naleznete v [tomto tématu](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span><span class="sxs-lookup"><span data-stu-id="2b0db-107">For more information about Attack Simulator requirements, see [this topic](https://docs.microsoft.com/office365/securitycompliance/attack-simulator#before-you-begin).</span></span>

- <span data-ttu-id="2b0db-108">Důležité věci, které je třeba vědět o simulacích útoků na **hrubou sílu hesla** :</span><span class="sxs-lookup"><span data-stu-id="2b0db-108">Important things to know about **Brute Force Password** attack simulations:</span></span>

  - <span data-ttu-id="2b0db-109">Pokud má cílový účet povoleno MFA a heslo bylo uhodeno správně, účet se nezobrazí jako narušený (druhý ověřovací faktor bude neúplný).</span><span class="sxs-lookup"><span data-stu-id="2b0db-109">If the target account has MFA enabled and the password was guessed correctly, the account will not show as compromised (the second authentication factor will be incomplete).</span></span>

  - <span data-ttu-id="2b0db-110">Soubor s hesly nesmí být větší než 10 MB.</span><span class="sxs-lookup"><span data-stu-id="2b0db-110">The password file can't be larger than 10 MB.</span></span> <span data-ttu-id="2b0db-111">Pro každý řádek použijte jedno heslo a za poslední heslo v seznamu zahrňte prázdný řádek (návrat vozíku).</span><span class="sxs-lookup"><span data-stu-id="2b0db-111">Use one password per line, and include a blank line (carriage return) after the last password in the list.</span></span>

- <span data-ttu-id="2b0db-112">Důležité věci, které byste měli vědět o **útoku typu Spephishing** :</span><span class="sxs-lookup"><span data-stu-id="2b0db-112">Important things to know about **Spear Phishing** attach simulations:</span></span>

  - <span data-ttu-id="2b0db-113">Podle návrhu nelze zadat vlastní hodnotu pro **adresu URL přihlašovacího serveru služby phishing**.</span><span class="sxs-lookup"><span data-stu-id="2b0db-113">By design, you can't provide a custom value for **Phishing login server URL**.</span></span>

  - <span data-ttu-id="2b0db-114">Pokud příjemce používá k hlášení zprávy jako podvodnou zprávu pomocí [doplňku povolit zprávu sestavy](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) , nebudete pravděpodobně dostávat upozornění na zprávu (protože se jedná o simulovaný útok).</span><span class="sxs-lookup"><span data-stu-id="2b0db-114">If a recipient uses the [Enable the Report Message add-in](https://docs.microsoft.com/microsoft-365/security/office-365-security/enable-the-report-message-add-in) to report the message as phishing, you might not receive alerts for the message (because this is a simulated attack).</span></span>

- <span data-ttu-id="2b0db-115">Sestavy: po dokončení simulovaného útoku můžete klepnutím na tlačítko **Podrobnosti útoku** zobrazit sestavu.</span><span class="sxs-lookup"><span data-stu-id="2b0db-115">Reports: After the simulated attack is complete, you can click **Attack Details** to see the report.</span></span>

- <span data-ttu-id="2b0db-116">Podrobné pokyny a nové funkce v simulátoru útoku naleznete v tématu [Attack simulátoru v sadě Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span><span class="sxs-lookup"><span data-stu-id="2b0db-116">For detailed instructions and new features in Attack Simulator, see [Attack Simulator in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/attack-simulator).</span></span>
