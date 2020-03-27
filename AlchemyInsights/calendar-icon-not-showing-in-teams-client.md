---
title: Nezobrazující se ikona kalendáře v klientovi Teams
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001219"
- "4375"
ms.openlocfilehash: 21692639fb746b2e5aab3dfc8894293d5dc890ac
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931977"
---
# <a name="calendar-icon-not-showing-in-teams-client"></a><span data-ttu-id="2b37c-102">Nezobrazující se ikona kalendáře v klientovi Teams</span><span class="sxs-lookup"><span data-stu-id="2b37c-102">Calendar icon not showing in Teams client</span></span>

<span data-ttu-id="2b37c-103">Karta kalendáře v Teams vyžaduje přístup k poštovní schránce Exchange prostřednictvím webových služeb Exchange.</span><span class="sxs-lookup"><span data-stu-id="2b37c-103">The Calendar Tab in Teams requires access to an Exchange mailbox via Exchange Web Services.</span></span> <span data-ttu-id="2b37c-104">Poštovní schránka Exchange může být online nebo místní.</span><span class="sxs-lookup"><span data-stu-id="2b37c-104">The Exchange mailbox can be Online or On-Premises.</span></span> <span data-ttu-id="2b37c-105">V případě online uživatelů, kteří nevidí kartu Kalendář, zkontrolujte, jestli [mají licenci pro poštovní schránku Exchange Online a že poštovní schránka je povolena](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="2b37c-105">For Online users who do not see the Calendar Tab, make sure they [are licensed for an Exchange Online mailbox and the mailbox is enabled](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes).</span></span>

<span data-ttu-id="2b37c-106">Pokud má uživatel v Exchange Online platnou poštovní schránku, ale karta Kalendář se pořád nezobrazuje, je možné, že dochází k potížím se sítí.</span><span class="sxs-lookup"><span data-stu-id="2b37c-106">If the user has a valid mailbox in Exchange Online, but still cannot see the Calendar tab, you may be experiencing a network issue.</span></span> <span data-ttu-id="2b37c-107">U ovlivněných uživatelů použijte nástroj [Microsoft Remote Connectivity Analyzer](https://testconnectivity.microsoft.com/) a spusťte **testy připojení Webových služeb systému Microsoft Exchange**.</span><span class="sxs-lookup"><span data-stu-id="2b37c-107">Use the [Microsoft Remote Connectivity Analyzer](https://testconnectivity.microsoft.com/) and run the **Microsoft Exchange Web Services Connectivity Tests** for the impacted user.</span></span>

<span data-ttu-id="2b37c-108">Nakonec zaškrtnutím políčka [Aplikace Teams – zásady nastavení aplikací](https://admin.teams.microsoft.com/policies/app-setup) zajistíte, že se aplikace Kalendář neodebere ze zásad použitých u uživatele (nejpravděpodobněji **Globální (výchozí nastavení celé organizace)**.</span><span class="sxs-lookup"><span data-stu-id="2b37c-108">Finally check the [Teams Apps – App setup policies](https://admin.teams.microsoft.com/policies/app-setup) to ensure the Calendar app has not been removed from the policy applied to the user (most likely the **Global (Org-wide default)**.</span></span>

<span data-ttu-id="2b37c-109">Pokud jsou vaši uživatelé místní, budete muset ověřit, jestli je hybridní konfigurace v pořádku.</span><span class="sxs-lookup"><span data-stu-id="2b37c-109">If your users are homed On-Premises, you need to confirm your Hybrid configuration is healthy.</span></span> <span data-ttu-id="2b37c-110">K řešení potíží použijte [průvodce hybridní konfigurací](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent).</span><span class="sxs-lookup"><span data-stu-id="2b37c-110">Use the [Hybrid Configuration Wizard](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent) to troubleshoot.</span></span>

<span data-ttu-id="2b37c-111">Poznámka: [Teams vyžaduje Exchange 2016 CU3 nebo novější](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).</span><span class="sxs-lookup"><span data-stu-id="2b37c-111">Note that [Teams requires Exchange 2016 CU3 or higher](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).</span></span>
