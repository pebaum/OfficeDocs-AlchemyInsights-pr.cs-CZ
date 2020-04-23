---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 2159feb4aa3999072de57d76790a2959c7355976
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43720761"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="ea233-102">Jak zakázat externí skupiny</span><span class="sxs-lookup"><span data-stu-id="ea233-102">How to disable External Groups</span></span>

<span data-ttu-id="ea233-103">Yammer externí zasílání zpráv platí Exchange Transport Rules (ETRs), sada proaktivních ovládacích prvků, aby se zabránilo sdílení informací o společnosti.</span><span class="sxs-lookup"><span data-stu-id="ea233-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="ea233-104">Chcete-li uživatelům zabránit ve vytváření externích skupin, je třeba nakonfigurovat pravidlo přenosu serveru Exchange (ETR) a potom nakonfigurovat Yammer tak, aby používal pravidlo přenosu exchange k blokování externího zasílání zpráv.</span><span class="sxs-lookup"><span data-stu-id="ea233-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span>
  
<span data-ttu-id="ea233-105">Po vytvoření pravidla v Centru pro správu Exchange Online nastavte eTR takto, aby se použilo v Yammeru:</span><span class="sxs-lookup"><span data-stu-id="ea233-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="ea233-106">Přihlaste se k Yammeru jako ověřený správce a v **Centru pro správu Yammeru**přejděte na **Nastavení obsahu a zabezpečení \> C.**</span><span class="sxs-lookup"><span data-stu-id="ea233-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **Content and Security \> Security Settings.**</span></span>

- <span data-ttu-id="ea233-107">V části **Externí zasílání zpráv**vyberte v **Yammeru vynutit pravidla přenosu Exchange online (ETRs).**</span><span class="sxs-lookup"><span data-stu-id="ea233-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>

- <span data-ttu-id="ea233-108">Zvolte **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="ea233-108">Choose **Save**.</span></span>

<span data-ttu-id="ea233-109">Další informace naleznete [v tématu Zakázání externích zpráv v síti Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span><span class="sxs-lookup"><span data-stu-id="ea233-109">For more information, see [Disable external messaging in a Yammer network](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span></span>
  