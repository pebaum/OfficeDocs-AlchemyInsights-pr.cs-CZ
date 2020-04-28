---
title: Používání DLP v pravidlech přenosu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5153"
ms.openlocfilehash: 124b031e2e029b745c66a71f681f57134739eafe
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915091"
---
# <a name="using-dlp-in-transport-rules"></a><span data-ttu-id="121fb-102">Používání DLP v pravidlech přenosu</span><span class="sxs-lookup"><span data-stu-id="121fb-102">Using DLP in transport rules</span></span>

<span data-ttu-id="121fb-103">Pokud chcete do existujícího přenosu integrovat ochranu před únikem informací (DLP), v nastavení pravidla přenosu použijte podmínku „**Pokud zpráva obsahuje… citlivé informace**“.</span><span class="sxs-lookup"><span data-stu-id="121fb-103">To integrate Data Loss Prevention (DLP) into an existing transport, use the condition "**If the message contains...Sensitive Information**" in the Transport rule setting.</span></span>

<span data-ttu-id="121fb-104">**Podrobnosti viz:**</span><span class="sxs-lookup"><span data-stu-id="121fb-104">**For more details, see:**</span></span>

- <span data-ttu-id="121fb-105">Typy citlivých informací integrované DLP v pravidlech přenosu: [Integrace pravidel pro citlivé informace](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/integrate-sensitive-information-rules).</span><span class="sxs-lookup"><span data-stu-id="121fb-105">Integrated DLP sensitive information types in transport rules: [Integrate Sensitive Information Rules](https://docs.microsoft.com/exchange/security-and-compliance/data-loss-prevention/integrate-sensitive-information-rules).</span></span>

<span data-ttu-id="121fb-106">Pravidlo také můžete otestovat pomocí testovacího režimu, a to s testem zásad, nebo bez něj.</span><span class="sxs-lookup"><span data-stu-id="121fb-106">You can also test the rule with or without policy test using Test Mode on the rule.</span></span>  <span data-ttu-id="121fb-107">Než nově vytvořené pravidlo otestujete, musíte počkat 30 minut.</span><span class="sxs-lookup"><span data-stu-id="121fb-107">You should wait 30 mins after creating the rule before testing it.</span></span>

- <span data-ttu-id="121fb-108">Viz článek [Testování pravidel toku pošty / přenosu](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/test-mail-flow-rules).</span><span class="sxs-lookup"><span data-stu-id="121fb-108">See [Test Mail Flow/Transport rules](https://docs.microsoft.com/exchange/security-and-compliance/mail-flow-rules/test-mail-flow-rules)</span></span>

<span data-ttu-id="121fb-109">**Poznámka**: Pokud se pro pravidla přenosu v EAC pokoušíte zavést novou zásadu DLP, použijte místo toho [Zásady DLC v Centru zabezpečení a dodržování předpisů](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies?view=o365-worldwide).</span><span class="sxs-lookup"><span data-stu-id="121fb-109">**Note**: If you are trying to implement a new DLP policy with transport rules in the EAC, use [DLP Policies in the Security and Compliance center](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies?view=o365-worldwide) instead.</span></span>
